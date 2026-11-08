# La Taqueria Del Beso · Torino

Sito vetrina per La Taqueria Del Beso, in Piazza Madama Cristina 3/A, San Salvario, Torino. Tutto il codice della pagina è in [dist/index.html](dist/index.html): HTML, stile, menu e interazioni. Le immagini sono già collegate e si trovano in [dist/assets](dist/assets).

Per aprire il sito basta un browser. Non servono pacchetti, variabili d’ambiente o database. Google Fonts, Tailwind, GSAP, ScrollTrigger e Lucide sono caricati via CDN. Il menu e i prezzi rimangono consultabili senza JavaScript; le animazioni rispettano la preferenza di movimento ridotto.

## Caricare su Vercel

Importa la repository **siti-web-torino/la-taqueria-del-beso** con la cartella principale alla radice. [vercel.json](vercel.json) imposta il preset **Other** e serve **dist**, senza installazione né compilazione. Non sono necessarie impostazioni di ambiente.

## Il menu

Le 28 voci con prezzi in euro sono trascritte dal listino fornito: tacos, degustazioni, antipasti, quesadillas, flautas e bevande. La foto del listino non fa parte del sito. L’intensità delle fiammelle è indicativa; per confermare ingredienti e allergeni bisogna chiedere allo staff. La sezione Michelada permette di scegliere una preferenza di piccantezza da comunicare al banco; il listino fornito non indica un prezzo per la personalizzazione.

Per aggiornare il menu modifica le schede e le righe della sezione con ID `menu` in `dist/index.html`. Indirizzo, orari e contatti provengono dal brief fornito; il locale può confermarne l’attualità.

## Foto e marchio

| File nel sito | Provenienza | Utilizzo |
| --- | --- | --- |
| `logo-hd.jpg` | Restauro IA del `logo.jpg` fornito, da 150 × 150 a 1254 × 1254 | Testata e apertura |
| `tacos-trio.jpg` | `tacos.png` | Foto principale e galleria |
| `tortilla-salsa.jpg` | `tacos 2.png` | Sezione sul locale e galleria |
| `tacos-da-condividere.jpg` | `tacos 3.png` | Storia e galleria |
| `salse.jpg` | `salse.png` | Storia e galleria |
| `michelada.jpg` | Immagine illustrativa generata a partire dalla foto delle salse | Scheda Bebidas |

Il restauro del logo ha mantenuto l’impianto circolare, le scritte «LA TAQUERIA», il cuore e i raggi gialli su fondo bianco. Il tratto è stato ricostruito a partire dalla foto. La facciata ha ispirato la cornice rossa a lampadine, la base crema e i dettagli scuri del sito.

Il marchio e le fotografie del locale sono materiali forniti dall’utente; questa repository non attribuisce una licenza di riutilizzo degli asset.
