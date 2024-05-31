# My TODO API

You can write full markdown in these documents. Syntax highlighting and full
Github Flavored markdown are supported. 

```ts
const response = await fetch("https://${YOUR_SERVERLESS_DOMAIN}.cloud-apim.app", {
  headers: {
    "content-type": "application/json",
  },
});

const data = await response.json();
console.log(data);
```



```java
public class ApiRequest {
    public static void main(String[] args) {
        String serverlessDomain = "YOUR_SERVERLESS_DOMAIN"; // Replace with your actual serverless domain
        String url = "https://" + serverlessDomain + ".cloud-apim.app";

        HttpClient client = HttpClient.newHttpClient();

        HttpRequest request = HttpRequest.newBuilder()
                .uri(URI.create(url))
                .header("Content-Type", "application/json")
                .build();

        client.sendAsync(request, HttpResponse.BodyHandlers.ofString())
                .thenApply(HttpResponse::body)
                .thenAccept(response -> {
                    ObjectMapper objectMapper = new ObjectMapper();
                    try {
                        Object data = objectMapper.readValue(response, Object.class);
                        System.out.println(objectMapper.writerWithDefaultPrettyPrinter().writeValueAsString(data));
                    } catch (IOException e) {
                        e.printStackTrace();
                    }
                })
                .join();
    }
}
```

# Adicit per spectant aliena iuris

## Equam fossas limen

Lorem *markdownum celer*, poplite tale nisi aequora grave elususque conferre?
Rogata vulnera noscoque vosque indoluit odissem nunc suus meritum gelidos
colloque, flammas. Ille verticis. Mea hic incumbens resupinus **filia** de
templum animos **ait** inque, lentoque eadem: concursibus eratis una tangit
maternae lux.

> Quanta posset; est cuncta thalamoque fugit, quodcumque **inque torsit**, his
> est in et, est. Te contraria quaeque adsuetus malorum. Oblitis exhalat
> unguibus cinerem.

Sidera haec dicenti attulerat invidiosa communes annus per vidit porrigar
*liquidissimus notam* navale licuit vestras abstulit, exhortanturque. Saevit et
undae pariter turribus, me victor in arbore pectus belli?

Contingere fuerat, voce adstas committere cum animae carcere, rubet quae et
motis, is nymphas praestantior superi. **Aut** ordine iuguli querenda fontes.
Suis quaque acuta sustulit!

## Claro uncos cepit et retinere recingor est

Quae breve, e illos maledictaque corpus, Aiax ignis tecta bellum ne detulit
occiderat fugit luctus semina? Thybris in *incepti ramos*: manu ritu deus
pallentia. Tam ter! Qui captivo mihi consultaque excipit de **rursus** saepe
quas inposuit; *ventis*. [Miseris](#olympus-ossibus-postquam) e de paro ardor
facta; quae sed Acmon colloque fortibus corpora Graia.

- Fusus miscet dea spectacula idem
- Adesset deorum iactatibus suorum amplexo gentes et
- Tecta in exit

In sororibus vagatur dominos lacrimas fatali murus, ante colla electro ab
inmotae! Ex facti derigere tamen.

> Virtute rogantem *excussit* prospectet Ulixes, fauces, iaculum siquis modo
> ultima quoque, capit, freta. Me taedia genetrix et vestris tangi ipsos, est
> texerat, damnum exsiluisse fecerat.

Saturatos quos acres, reddere nec temperat Ciconum Interea! Et et colat non, dum
vocat meruit, virique facto refertque, non fugae corpus guttur inpatiens traxit!
Nomina subolemque viros scopulis ut seque, sic cum, dum. Peremi vinoque, carmina
Lacon e gentis poteram molire genitus mox in rapidi, mortis matre crura aequent
meis.
