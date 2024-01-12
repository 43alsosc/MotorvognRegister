Dette prosjektet er et motorvognregister implementert ved hjelp av Spring Boot (Java) på serversiden og HTML med JavaScript på klientsiden. Målet med prosjektet er å opprette, lagre, hente og slette motorvognsdata gjennom en nettleserbasert brukergrensesnitt.

Serversiden (Java):

Motorvogn-klasse:

Representerer en motorvogn med attributter som navn, adresse, personnummer, kjennetegn, bilmerke og biltype.
Har gettere og settere for alle attributtene.

MotorvognController-klasse:

En Spring Boot-kontroller som håndterer HTTP-forespørsler.
Har metoder for å lagre en ny motorvogn, hente alle lagrede motorvogner og slette alle lagrede motorvogner.

MotorvognRegisterApplication-klasse:

Hovedklassen som starter Spring Boot-applikasjonen.
Klientsiden (HTML og JavaScript):

HTML-fil:

Bruker HTML for å opprette et enkelt brukergrensesnitt med input-felter for eier- og kjøretøyinformasjon.
Inkluderer Tailwind CSS for styling.

JavaScript-funksjoner:

lagreMotorvogn(): Samler data fra input-felter, sender en POST-forespørsel til serveren for å lagre motorvognen, og oppdaterer deretter visningen av alle motorvogner.
hentAlleMotorvogner(): Sender en GET-forespørsel for å hente alle motorvogner fra serveren og viser resultatet i en tabell.
formaterData(motorvogner): Formatterer motorvognsdataene og viser dem i HTML-tabellen.
slettAlleMotorvogner(): Sender en GET-forespørsel for å slette alle motorvogner, og oppdaterer deretter visningen av alle motorvogner.



Brukertesting Skjema

### 1. Introduksjon:

Prosjektnavn: [Prosjektnavnet ditt]
Dato for testing: [Dato]

### 2. Generell informasjon:

##### Testdeltakerens navn:
##### Alder:
##### Yrkesbakgrunn:
##### Tidligere erfaring med lignende systemer:

### 3. Oppgaver:

#### 1. Registrere en ny motorvogn:
- Instruksjon: Prøv å registrere en ny motorvogn ved å fylle ut alle feltene i skjemaet.

- #### Observasjoner: 
 - - Hvordan navigerte testdeltakeren gjennom skjemaet?
 - - Var det noen spesifikke felt som virket forvirrende eller vanskelige å fylle ut?
 - - Ble alle nødvendige felt forstått?

#### 2. Se på oversikten over registrerte motorvogner:

- Instruksjon: Se på oversikten over registrerte motorvogner.
- #### Observasjoner:
- - Hvordan reagerte testdeltakeren på tabellen?
- - Var informasjonen lett å forstå?
- - Fikk testdeltakeren en god oversikt over registrerte motorvogner?

### 4. Tilbakemeldinger:

- Hva likte testdeltakeren best med systemet?
- Hva var mest utfordrende eller forvirrende?
- Eventuelle forslag til forbedringer:

### 5. Generelle spørsmål:

- Hvordan vil du beskrive din generelle opplevelse med systemet?
- På en skala fra 1 til 10, hvor enkelt var det å bruke systemet?
- Vil du ha noen endringer eller tillegg til funksjonaliteten?

### 6. Avslutning:

- Er det noe annet du ønsker å legge til eller kommentere?

### 7. Takk for deltakelsen!


Testdeltaker 1: Magnhild (45 år, Lærer)

Introduksjon:

Prosjektnavn: Motorvognregister
Dato for testing: 2024-01-10

Generell informasjon:

Testdeltakerens navn: Magnhild
Alder: 45
Yrkesbakgrunn: Lærer
Tidligere erfaring med lignende systemer: Lite, har ikke brukt lignende systemer så mye tidligere.

Oppgaver:

Registrere en ny motorvogn:

Observasjoner:
Magnhild navigerte enkelt gjennom skjemaet.
Ingen spesifikke felt virket forvirrende eller vanskelige å fylle ut.
Alle nødvendige felt ble forstått.

Se på oversikten over registrerte motorvogner:

Observasjoner:
Magnhild reagerte positivt på tabellen.
Informasjonen var lett å forstå.
Hun fikk en god oversikt over registrerte motorvogner.
Tilbakemeldinger:

Hva likte Magnhild best med systemet?
Magnhild likte enkelheten og brukervennligheten.
Hva var mest utfordrende eller forvirrende?
Magnhild hadde ingen spesifikke utfordringer eller forvirringer.
Eventuelle forslag til forbedringer:
Gjør slett knappen rød.

Generelle spørsmål:

Hvordan vil du beskrive din generelle opplevelse med systemet?
Magnhild beskrev opplevelsen som positiv og effektiv.
På en skala fra 1 til 10, hvor enkelt var det å bruke systemet?
9 av 10.
Vil du ha noen endringer eller tillegg til funksjonaliteten?
Magnhild ønsker ingen endringer for øyeblikket.

Avslutning:

Er det noe annet du ønsker å legge til eller kommentere?
Magnhild hadde ingen ytterligere kommentarer.
Takk for deltakelsen!


Testdeltaker 2: Sebasitan (17 år, Elev)

Introduksjon:

Prosjektnavn: Motorvognregister
Dato for testing: 2024-01-10
Generell informasjon:

Testdeltakerens navn: Sebasitan
Alder: 17
Yrkesbakgrunn: Elev
Tidligere erfaring med lignende systemer: Har ingen erfaring med lignende systemer.

Oppgaver:

Registrere en ny motorvogn:

Observasjoner:
Sebasitan navigerte raskt gjennom skjemaet.
Ingen spesifikke felt virket forvirrende.
Alle nødvendige felt ble forstått uten problemer.
Se på oversikten over registrerte motorvogner:

Observasjoner:
Sebasitan reagerte positivt på tabellen.
Informasjonen var lett å forstå.
Fikk en god oversikt over registrerte motorvogner.

Tilbakemeldinger:

Hva likte du best med systemet?
Sebasitan likte effektiviteten og hvordan systemet hjelper med registrering.
Hva var mest utfordrende eller forvirrende?
Sebasitan hadde ingen utfordringer eller forvirringer.
Eventuelle forslag til forbedringer:
Gjør slik at man må bekefte sletting av bilder

Generelle spørsmål:

Hvordan vil du beskrive din generelle opplevelse med systemet?
Sebasitan beskrev opplevelsen som profesjonell og tidseffektiv.
På en skala fra 1 til 10, hvor enkelt var det å bruke systemet?
8 av 10.
Vil du ha noen endringer eller tillegg til funksjonaliteten?
Sebasitan ønsker ingen endringer for øyeblikket.
Avslutning:

Er det noe annet du ønsker å legge til eller kommentere?
Sebasitan hadde ingen ytterligere kommentarer.
Takk for deltakelsen!


Introduksjon:

Prosjektnavn: Motorvognregister
Dato for testing: 2024-01-11
Generell informasjon:

Testdeltakerens navn: Sara
Alder: 28
Yrkesbakgrunn: Student i informatikk
Tidligere erfaring med lignende systemer: Begrenset erfaring med lignende systemer.
Oppgaver:

Registrere en ny motorvogn:

Observasjoner:
Sara navigerte greit gjennom skjemaet, men tok litt tid.
Noen felt virket litt forvirrende, spesielt personnummer.
Hun forsto til slutt alle nødvendige felt.

Se på oversikten over registrerte motorvogner:

Observasjoner:
Sara reagerte positivt på tabellen.
Informasjonen var overkommelig å forstå.
Fikk til slutt en god oversikt over registrerte motorvogner.

Tilbakemeldinger:

Hva likte Sara best med systemet?
Sara likte enkelheten, men syntes noen felt var litt forvirrende.
Hva var mest utfordrende eller forvirrende?
Personnummerfeltet var litt utfordrende for Sara.
Eventuelle forslag til forbedringer:
Sara foreslo å legge til hjelpetekster for noen felt.
Generelle spørsmål:

Hvordan vil du beskrive din generelle opplevelse med systemet?
Sara beskrev opplevelsen som positiv, men med noen små utfordringer.
På en skala fra 1 til 10, hvor enkelt var det å bruke systemet?
7 av 10.
Vil du ha noen endringer eller tillegg til funksjonaliteten?
Sara ønsker hjelpetekster eller mer forklaring på noen felt.
Avslutning:

Er det noe annet du ønsker å legge til eller kommentere?
Sara hadde ingen ytterligere kommentarer.
Takk for deltakelsen!

Glemte å trykke på commit på brukertestingen :/
