# OPPGAVE 3
- Denne ukens oppgave vil være å kombinere de to temaene vi skal lære denne uken som er parallax og multimedia.

- Dere kan velge tema på oppgaven selv, eksempler er destinasjon, film, bok, serie, dyr. Mulighetene er mange, men innholdet må samsvare    hverandre. Så bruk media og tekst om et samme tema.

 - Denne oppgaven vil også være designet en skjermstørelse - og det er mobil. Så tenk over størrelser, og hint hint jeg ga dere en veldig enkel måte å gjøre det på i undervisningen mandag😉

# Krav:
 - HTML dokument med minimum tre deler (tre media med tilsvarende tre tekster)
 - CSS fil som blir lenket inn HTML dokumentet

# Leverings Metode:
 - Lenke til GitHub Repo (Dette repositoriet må være Public)
 - Lenke til live nettside (Netlify)

Tenk på det vi har lært til nå med å bruke semantisk html og korrekt navngiving, det vil være noe vi kommer til å se etter i oppgavene fra nå av.
NB: Denne oppgaven trenger ikke header og footer, i hovedsak er dette en side som ligger i main.

 - Due Sep 15



 # Notat:
  - Fikk en ide om å lage en nettside som oppleves mer som mellomting mellom en bildebok og en video, men oppdaget fortløpende at jeg vil trenge JS for å fullføre.
  - Konklusjon: forløpig css kode går ut fra parallax effecten vi lærte å kode mandag 11 sept, søker opp andre måter å gjøre effekten på, kanskje jeg kan få den til å oppføre seg som en tetris block? (-!_i-!, utropstegn og "i" indikerer loddrett linje, med prikken som "pilrettning")
  - Tema: Unus Annus

  # Helomvending: 
  - Da jeg kom over flere komplikasjoner med første prosjektet bestemte jeg meg for å lage en enklere nettside med et annet tema. Denne siden har temaet Japan. Vil påpeke at eg har kopiert tekstene fra nettsteder som wikipedia og albatros.no, da jeg har fokusert på min kode prosess i dette proskjektet. 
  - Sliter med at h1 of h2 elemeter blir veldig små og vet ikke hvorfor, har juster størrelse i css.
  - margin-bottom i iframe (css) var ikke med på å ha main backgrunnsfargen, fungerte greit når jeg la inn en <br> etter iframe taggen. 
  - Har prøvd å gjøre koden noe tørrere, var bare litt tekst i tillegg til bilde css som kunne komprimeres så vidt jeg ser.
  - Har holdet meg unna <picture> da vi opplevde problemer når vi ble undervist og venter på tilbakemelding ang løsning.
  - Korrigerte bakgrunnsfarge til å samsvare med det Japanske flagget.
  - Audio: Musikk laget av Aleksey Chistilin  hentet fra Pixabay, låtnavn: Inspiring Cinematic Asia.
  - Video: fra youtube-kanal "rj aguirre"
  (første video som ble tatt ut av koden: hentet fra youtube, fra kanal "The Travel Intern".)

  - Prøver å justere iframe width og height, fjerner all justering om det ikkje virker. ...Later ikke til å utgjøre store forskjeller, men jeg lar justering bli i koden. Usikker på om width og height justering i html har gjort noen forskjell, men fikk juster størrelse i css.
  - Var ikke fornøyd med første videoen eg fant, så gikk på let etter ny... Når eg fant ny video, ser jeg at mine justeringer i iframe taggen utgjør en forskjell i sammenheng med css height width justeringen. 

  - Fikk feedback på at teksten bør ha max-width så den ikke strekker seg over hele nettsiden, noe jeg er enig i, men så snart jeg setter på max-width trekker all skrift seg til venstre selv om jeg har satt teksten i en div som igjen står i display-flex.
  - etterspurte veiledning og fikk beskjed om at display-flex på være i parent-elementet som den skal justere, noe jeg egentlig burde visst/husket. Så da lager eg ny class til section for å justere dette og håpet at problemet løser seg.

  - Har nå samlet alle bildene i en mappe, om det er spørsmål til hvorfor det er så mange bilder, så er det fordi jeg ønsket utgvalg og mulighet til å lett kunne bygge videre på prosjektet.