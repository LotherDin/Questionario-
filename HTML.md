### 100 domande sull'HTML a cui uno Sviluppatore deve sapere rispondere

1. Cos'è HTML?

1- Hyper Text Markup Language ovvero un linguggio di formattazione(permette di impaginare e formattare pagine collagate tra di loro,attraverso link, come i siti web.)

2. Qual è l'attuale versione standard di HTML?

2- HTML5 

3. Qual è la differenza tra HTML e XHTML?

3- Sintassi XML valida:

HTML è basato su una sintassi più flessibile e permissiva. Tollererà errori di markup e non richiede rigorosamente la chiusura degli elementi o l'uso di virgolette intorno agli attributi.
XHTML, d'altra parte, segue una sintassi più rigorosa e valida secondo le regole XML. Richiede la corretta chiusura degli elementi e l'uso di virgolette intorno agli attributi.

Parsing del documento:

HTML è generalmente più tollerante agli errori durante il parsing. Se il browser incontra un errore di markup, cerca comunque di interpretare e visualizzare la pagina.
XHTML è più rigoroso e se incontra errori durante il parsing, potrebbe non visualizzare correttamente la pagina o generare errori.

Case sensitivity:

HTML non è case-sensitive, il che significa che non fa distinzione tra maiuscole e minuscole nei tag e negli attributi.
XHTML è case-sensitive e richiede la coerenza nell'uso di maiuscole e minuscole nei tag e negli attributi.

DOCTYPE dichiaration:

HTML può funzionare senza una dichiarazione DOCTYPE, ma la sua presenza aiuta a specificare quale versione di HTML si sta utilizzando.
XHTML richiede una dichiarazione DOCTYPE, e deve essere dichiarato correttamente come XHTML per essere interpretato correttamente.

Supporto ai commenti:

HTML accetta commenti anche se non sono correttamente formattati come XML.
XHTML richiede che i commenti siano correttamente formattati come <!-- commento -->, seguendo la sintassi XML.

Uso di tag vuoti:

In HTML, è comune utilizzare tag vuoti (senza chiusura esplicita) come <br>, <img>, <hr>, ecc.
In XHTML, i tag vuoti devono essere chiusi correttamente usando uno slash, ad esempio <br />, <img />, <hr />

4. Che cosa significa DOCTYPE e a cosa serve?

4- Document Type Declaration e' una dichirazione speciale nel markup di un documento HTML o XHTML.

 Essa serve a informare il browser su quale versione specifica di HTML o XHTML viene utilizzata nel documento e a quale standard di sintassi deve conformarsi durante l'interpretazione del codice.


5. Come si struttura un documento HTML di base?

5- Un documento HTML di base segue una struttura standard che include diverse sezioni fondamentali:

<!DOCTYPE html>: Questa è la dichiarazione DOCTYPE che indica al browser che il documento è scritto in HTML5.

<html lang="it">: Questo è l'elemento radice che racchiude l'intero documento HTML. L'attributo lang specifica la lingua del documento (in questo caso, italiano).

<head>: Questa sezione contiene informazioni meta sul documento, come il set di caratteri utilizzato (<meta charset="UTF-8">), la dichiarazione del viewport per la responsività (<meta name="viewport" content="width=device-width, initial-scale=1.0">), il titolo della pagina (<title>Titolo della Pagina</title>), e collegamenti a fogli di stile CSS o altri elementi head.

<body>: Questa è la sezione principale del documento che contiene il contenuto effettivo della pagina, come testo, immagini, link, ecc.

Elementi HTML all'interno del <body>: All'interno di <body>, puoi aggiungere tutti gli elementi HTML necessari, come titoli (<h1>, <h2>, ecc.), paragrafi (<p>), immagini (<img>), link (<a>), liste (<ul>, <ol>, <li>), form (<form>, <input>, ecc.), e molti altri.

6. Qual è la differenza tra un elemento e un tag?

6- Un "tag" è una parte del codice HTML che viene utilizzata per definire un elemento. I tag sono delimitati da parentesi angolari < e >. Ad esempio, <p> è un tag che indica l'inizio di un elemento paragrafo, mentre </p> è un tag di chiusura che indica la fine dell'elemento paragrafo.

Elemento:
Un "elemento" è la combinazione di un tag di apertura, il suo contenuto e un tag di chiusura (se necessario). Ad esempio, considera il seguente elemento paragrafo:

<p>Questo è un paragrafo.</p>

7. Come si inseriscono i commenti in un documento HTML?

-7 Si inseriscono con <!---->

8. Quali sono gli elementi `<head>` più comuni in un documento HTML?

8- i meta tag "meta charset, meta name, contetnt e title"( ma possiamo usare anche i tag script, link per collegare le pagine di js, o css )

9. Che cosa fa l'elemento `<title>`?

9- Ci permette di dare il titolo al nostro documento html

10. Come si collega un foglio di stile CSS a un documento HTML?

10- Con <link href="style.css">

11. Come si collega uno script JavaScript a un documento HTML?

11- Con consigliabile inserire il tag nel body, cosi faccendo i browser leggerando lo script doo aver caricato tutto <script src="script.js"> 

12. Qual è la differenza tra elementi di blocco e elementi inline?

12- Usiamo un esempio per capirlo : gli elementi di blocco sono come delle scatole, invece gli elementi inline sono il contenuto che puoi mettedere all'interno.

13. Come si crea un link ipertestuale in HTML?

13- Utilizzando il tag <a></a> mettendo all'interno l'indirizzo 

14. Che cos'è un attributo in HTML?

14-  E' una caratteristica/informazione associata all'elemento (nome-attributo = valore-attributo)

15. Come si inserisce un'immagine in una pagina HTML?

15- con il tag <img> ed e' un elemento "inline"

16. Che cos'è l'attributo `alt` in un'immagine e perché è importante?

16- Testo alternativo per un'immagine. Serve a descrivere un'immagine o ciò che essa rappresenta (ad esempio usato per quando non viene caricata correttamente un immgine)

17. Come si crea una lista ordinata o non ordinata in HTML?

17- Lista ordinata : <ol>ordinate list</ol>, lista non ordinata <ul>unrodinate list</ul>

18. Qual è la differenza tra `<div>` e `<span>`?

18- Ci sono differenze tra il tag span ed il tag div. Il tag span è utilizzato per elementi inline, mentre il tag div è utilizzato per contenuto a livello di blocco.

19. Che cos'è un iframe e come si utilizza?

19- Stringa di codice che allega un elemento esterno senza il bisogno di caricare nulla sul tuo database. Per esempio anziché caricare un video di YouTube, appesantendo il sito, lo incorpori direttamente tramite tag iFrame.

20. Come si può inserire un video o un file audio in HTML?

20- <video width="320" height="240" controls> <source src="video.mp4" type="video/mp4"></video> Per audio cosi <audio controls><source src="musica.mp3" type="audio/mp3"></audio>
  
21. Che cos'è il modello a box di CSS e come interagisce con HTML?

21- Si tratta del meccanismo che governa la presentazione dei vari elementi di una pagina.

22. Come si crea una tabella in HTML?

22- <table></table> si utilizzano i tag <tr> table row - riga della tabella e <td> table data - la cella che contine i valori all'interno della riga.

23. Qual è la differenza tra `thead`, `tbody` e `tfoot` in una tabella?

24. Come si può migliorare l'accessibilità in una pagina HTML?
25. Che cos'è ARIA in HTML e a cosa serve?
26. Come si crea un modulo in HTML?
27. Quali sono i vari tipi di input che si possono usare in un modulo HTML?
28. Che cos'è il metodo GET rispetto al metodo POST in un modulo?
29. Come si può validare l'input del modulo in HTML5?
30. Che cos'è e come si utilizza il canvas in HTML?
31. Quali sono le nuove caratteristiche introdotte in HTML5?
32. Che cos'è il web storage in HTML5?
33. Che cos'è e come si utilizza l'elemento `<datalist>` in HTML?
34. Come si può incorporare un file SVG in una pagina HTML?
35. Qual è la differenza tra `cookies`, `sessionStorage` e `localStorage`?
36. Che cos'è la geolocalizzazione in HTML5 e come si utilizza?
37. Che cos'è il drag-and-drop in HTML5 e come si implementa?
38. Come si può implementare la paginazione in un documento HTML?
39. Che cosa sono le meta tag e a cosa servono?
40. Come si imposta il charset in un documento HTML?
41. Qual è la differenza tra elementi `<b>` e `<strong>`?
42. Qual è la differenza tra elementi `<i>` e `<em>`?
43. Come si crea un elenco a definizioni in HTML?
44. Che cos'è un attributo globale in HTML?
45. Che cosa fa l'attributo `data-*` in HTML?
46. Come si implementa una barra di navigazione in HTML?
47. Come si crea un breadcrumb in HTML?
48. Che cos'è il semantic markup in HTML?
49. Come si utilizza l'elemento `<article>` in HTML5?
50. Come si utilizza l'elemento `<section>` in HTML5?
51. Come si utilizza l'elemento `<aside>` in HTML5?
52. Che cos'è e come si utilizza l'elemento `<footer>` in HTML5?
53. Che cos'è e come si utilizza l'elemento `<header>` in HTML5?
54. Come si implementa un layout a griglia con HTML?
55. Qual è lo scopo dell'elemento `<nav>` in HTML?
56. Come si possono creare forme personalizzate con HTML e CSS?
57. Che cos'è e come si utilizza l'elemento `<figure>` in HTML5?
58. Che cos'è l'elemento `<figcaption>` e come si utilizza?
59. Come si implementa l'ottimizzazione delle immagini in una pagina web?
60. Che cosa sono le responsive images in HTML5?
61. Come si utilizza l'elemento `<picture>` in HTML5?
62. Che cos'è il lazy loading delle immagini e come si implementa?
63.Come si gestiscono i font web in HTML? 
64. Che cos'è e come si utilizza l'elemento `<main>` in HTML5? 
65. Che cosa sono e come si usano i Web Components? 
66. Come si utilizza l'elemento `<template>` in HTML5?
67. Come si possono creare dei tooltip personalizzati con HTML e CSS? 
68. Che cos'è un polyfill e a cosa serve? 
69. Come si implementa l'animazione con HTML e CSS? 
70. Che cos'è e come si usa l'attributo `role` in HTML? 
71. Come si implementa l'accessibilità per le immagini in HTML? 
72. Che cos'è e come si usa l'elemento `<progress>` in HTML5? 
73. Che cos'è e come si usa l'elemento `<meter>` in HTML5? 
74. Come si implementa una barra di ricerca in HTML? 
75. Che cos'è un Document Type Definition (DTD) in HTML? 
76. Come si utilizza l'elemento `<output>` in HTML5? 
77. Che cos'è il cross-origin resource sharing (CORS) in HTML? 
78. Come si imposta un favicon per un sito web? 
79. Che cos'è e come si usa l'attributo `tabindex` in HTML? 
80. Come si implementa un controllo di zoom personalizzato in una pagina web?
81. Che cos'è e come si usa l'elemento `<dialog>` in HTML5? 
82. Come si può migliorare la leggibilità del testo in HTML? 
83. Che cos'è e come si usa l'elemento `<mark>` in HTML5? 
84. Come si possono creare tabelle responsive in HTML e CSS? 
85. Che cos'è e come si usa l'elemento `<summary>` e `<details>` in HTML5? 
86. Come si implementano le mappe interattive in HTML? 
87. Che cos'è e come si usa l'elemento `<time>` in HTML5? 
88. Come si possono gestire le icone in una pagina HTML? 
89. Che cos'è e come si usa l'attributo `contenteditable` in HTML? 
90. Come si può creare un layout multi-colonna in HTML e CSS? 
91. Che cos'è e come si implementa il controllo ortografico in HTML? 
92. Che cos'è un framework CSS e come interagisce con HTML? 
93. Come si possono creare animazioni di testo in HTML e CSS? 
94. Che cos'è e come si implementa un parallax scrolling in HTML e CSS? 
95. Come si possono creare effetti di ombreggiatura in HTML e CSS? 
96. Che cos'è e come si utilizza l'attributo `download` in HTML5? 
97. Come si possono creare breadcrumb dinamici in HTML? 
98. Che cos'è e come si usa l'attributo `pattern` in un input HTML? 
99. Come si può ottimizzare una pagina web per la stampa utilizzando HTML e CSS? 
100. Che cos'è e come si usa l'elemento `<noscript>` in HTML?