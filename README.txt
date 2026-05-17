MOOD SPACE - WEBSITE PROJECT

DESCRIZIONE DEL PROGETTO:

Mood Space è un sito web pensato per accompagnare l’utente in un viaggio attraverso le emozioni.

Il sito invita a esplorare diversi stati d’animo: calm, sad, happy e angry, ognuno con una propria atmosfera visiva e contenuti dedicati.

L’esperienza è semplice e intuitiva, pensata per far sentire l’utente dentro ogni emozione e guidarlo da una pagina all’altra in modo naturale.

L’obiettivo è mostrare come il web possa trasmettere sensazioni ed emozioni oltre alle informazioni.

Navigando nel sito, l’utente può rilassarsi, riflettere, migliorare il proprio umore o gestire la rabbia, vivendo un piccolo percorso emotivo interattivo.

Le pagine sono collegate tra loro e permettono di tornare sempre alla home.

-index.xhtml è la Home Page del sito, da cui l’utente può scegliere e accedere alle diverse emozioni. 
Include la pagina Explore Moods per raggiungere moods.xhtml.

-calm.xhtml rappresenta la calma e il rilassamento, con elementi visivi e un’animazione che aiuta a respirare e rilassarsi.

-sad.xhtml rappresenta la tristezza e offre messaggi di supporto emotivo; da qui si può accedere alla pagina di conforto hug.xhtml.

-hug.xhtml è una pagina di supporto che offre immagini e frasi rassicuranti per trasmettere conforto e positività.

-happy.xhtml rappresenta la felicità e propone attività e idee positive per mantenere un buon umore. 
In questa sezione alcuni elementi sono cliccabili e portano a contenuti esterni di ispirazione.

-angry.xhtml rappresenta la rabbia e fornisce consigli per gestirla; da qui è possibile tornare alla pagina calm.xhtml per ritrovare la tranquillità.

-moods.xhtml raccoglie tutti i mood in un'unica pagina. 
Presenta le emozioni disponibili come card disposte con Flexbox, ognuna con un commento e un link alla pagina corrispondente. 
Include anche una sezione di mood futuri, visivamente distinti, che anticipano i prossimi sviluppi del sito.

TECNOLOGIE UTILIZZATE:

-XHTML per la struttura delle pagine
-CSS per grafica e layout
-Animazioni CSS (keyframes) per effetti dinamici
-Flexbox per il layout della pagina moods
-Collegamenti tra le pagine (multi-page website)

TECNICHE APPROFONDITE:

-Classi body per pagina -> ogni body ha una classe propria per isolare gli stili senza conflitti in un unico CSS
-@keyframes breathe -> il cerchio di calm si espande e contrae con scale() in 12s, simulando il respiro, solo CSS
-Flexbox nella pagina Moods -> flex-wrap e gap dispongono le card automaticamente senza media query
-Glassmorphism -> sfondo rgba + backdrop-filter blur(6px) per effetto vetro smerigliato sulle card
-Hover su elemento annidato -> .mood-card:hover .mood-comment rivela il commento con transizione opacity 0→1
-Sfondo GIF fixed -> background-attachment fixed tiene lo sfondo fermo durante lo scroll


DIFFICOLTÀ INCONTRATE:

-Gestire il layout CSS per pagine visivamente molto diverse, scegliendo sfondi, colori e dimensioni giuste per ogni emozione mantenendo coerenza nel sito.
-Flexbox e i selettori annidati per l'hover sono stati i punti più tecnici, studiati e applicati per la prima volta in questo progetto.


SVILUPPI FUTURI:
Nella pagina moods.xhtml sono già presenti card segnaposto per: Love, Anxiety, Fear.
Ogni nuovo mood seguirà la stessa struttura con atmosfera visiva e contenuti propri.

AUTORI:
- Ashmeet Kaur

REPOSITORY GITHUB:
-https://github.com/xAsh404/MOOD-SPACE