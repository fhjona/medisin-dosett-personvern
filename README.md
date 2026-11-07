# Personvernerklæring — Medisin Dosett

Siden som ligger på
<https://fhjona.github.io/medisin-dosett-personvern/>
og som er oppgitt som personvernerklæring for appen **Medisin Dosett**
(`com.frankjonassen.medisindosett`) i Google Play og App Store.

Norsk og engelsk på samme side, med en velger øverst. Den engelske utgaven har
sin egen adresse med `#english` på slutten.

Hele siden er `index.html` — ingen byggesteg, ingen avhengigheter utenom
skriftene fra Google Fonts.

## Når den må endres

Hvis en senere utgave av appen begynner å behandle data på en annen måte, skal
denne siden oppdateres og datoen øverst endres **før** utgaven slippes.

Det som står i dag bygger på disse forholdene i appen:

- Ingen `INTERNET`-tillatelse i Android-manifestet, så appen kan ikke sende noe
- Ingen analyse- eller annonsebiblioteker blant avhengighetene
- `android:allowBackup="true"` uten regler for hva som utelates, så dosettfila
  følger med i telefonens egen sikkerhetskopi til brukerens Google-konto
- Varsler planlegges lokalt, ingen pushtjeneste
- Eksport skjer bare når brukeren selv trykker på det

Endres noen av dem, må teksten følge etter.
