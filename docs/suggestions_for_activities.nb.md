# Forslag til aktiviteter

## Debatt

Velg et emne innen fysikk som er egnet for debatt. For eksempel 'styrker og svakheter ved Bohrs atommodell' eller 'kvantemekanikk vs. generell relativitetsteori - hvilken er bedre,' og del klassen i to grupper. Deretter ber du studentene om å bruke 30 minutter med språkmodellen for å forberede seg til debatten, for eksempel ved å få den til å generere motargumenter.

| Kompetanser trent | Prinsipper for prompt-teknikk trent |
|----------------------|-------------------|
| [C1: Forklare teknologien](learning_outcomes.md#C1:-Forklare-teknologien) | [Kontekst](prompt_engineering.md#kontekst) |
| | [Rolle](prompt_engineering.md#rolle) |



## Forene ulike perspektiver

Velg noen fysikkfenomener som kan virke motintuitive. For eksempel: 'Newtons tredje lov sier at kraft er lik motkraft i en kollisjon,' 'Det tar 8 minutter fra solen slutter å eksistere til vi merker noe som helst,' og 'Du kan ikke feste en magnet til en bil for å trekke deg frem.' La deretter studentene skrive ned hva de allerede vet som gjør disse fakta vanskelige å forstå. For eksempel: 'I en kollisjon mellom et tog og en bil er det verre for bilen,' 'Når jeg slår av lyset på badet, merker jeg det med en gang,' og 'Jeg kan løfte ting med magneter; det virker som magi.' Be deretter studentene om å bruke språkmodellen for å forene disse motsigelsene. Kanskje du kan skissere hele spekteret i betydningens rom?

## Lesestøtte

Gi studentene en vitenskapelig artikkel som er interessant (eller la dem finne en selv, hvis de er ekstra motiverte). Kopier tekstinnholdet og lim det inn i en språkmodell. Be den om å forklare artikkelen for deg. Foreslått prompt:
Her er en fysikkartikkel jeg fant interessant:
"""
X
"""
Jeg er en videregående skole-student med begrenset kunnskap om fysikk. Jeg vil at du skal forklare denne artikkelen for meg på en pedagogisk måte. Jeg vil at du skal svare på spørsmålene mine veldig kortfattet.
Merk hvordan vi har gitt språkmodellen kontekst, roller og formatet for hvordan den skal svare. Preferansen for korte svar er et personlig valg


## Forberedelse til lab 

Laboratoriearbeid er ofte veldig vanskelig fordi det er mange ferdigheter som må trenes samtidig: forståelse av fysikk, tekniske ferdigheter, lese instruksjoner og beregne usikkerhet. Derfor kan det være nyttig å sette av 30 minutter før laben til å lime inn labinstruksjonene i språkmodellen og deretter stille spørsmål til den. Her er en foreslått prompt:
Jeg skal gjøre dette laboratorieeksperimentet snart. Her er labinstruksjonene:
“””
X
“””
Jeg er en videregående skole-student med begrenset kunnskap om fysikk. Jeg vil at du skal forklare disse labinstruksjonene for meg på en pedagogisk måte. Jeg vil at du skal svare på spørsmålene mine veldig kortfattet.

## Skriving av laboratorierapport 

Studenter synes kanskje ikke det er den mest spennende aktiviteten å skrive laboratorierapporter, men med språkmodeller har du muligheten til at studentene dine først kan få grov tilbakemelding fra roboten. Be studentene om å lime inn svaret sitt i språkmodellen, sammen med kriteriene dine for hvordan du vil at rapporten skal være (kontekst). Hvis studentene leverer rapporter med åpenbare mangler, send dem tilbake umiddelbart og be dem om å få slik tilbakemelding fra språkmodellen før du gir din tilbakemelding. Selvfølgelig bør vi ikke slutte å gi personlig tilbakemelding, men kanskje vi er på vei inn i en tid der vi ikke lenger trenger å stadig minne studenter på å inkludere bildetekster og utstyrslist

## Beregningsessays

Differensiering er nøkkelen i programmeringsoppgaver. La studentene utforske et fysisk fenomen ved hjelp av programmering og si at det de har oppdaget, skal presenteres foran klassen eller leveres som en Google Colab-notatbok. Det kan kanskje ikke være opplagt hva det betyr å utforske et fysisk fenomen ved hjelp av programmering, men et utgangspunkt kunne være å se på denne samlingen av såkalte 'Beregningsessays'. Gi studentene flere alternativer:

Lag en simulering av en dobbel pendel i Python (ha et fungerende minimalt eksempel for hånden i tilfelle noen studenter sliter med å komme i gang). Finn et spørsmål du er nysgjerrig på angående pendelens bevegelse (f.eks. når bevegelsen overgår til å bli 'kaotisk') og lag en presentasjon hvor du samler det du har funnet.
Simuler et kast med luftmotstand! Finn et interessant spørsmål og lag en presentasjon om det du har oppdaget.
Finn ditt eget fysiske system og spørsmål. Lag en presentasjon om det du har funnet.
