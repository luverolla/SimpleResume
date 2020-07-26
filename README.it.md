# SimpleResume

Leggi in un'altra lingua: [English](README.md) | Italiano

![Preview](/res/screen.png)

Modello per CV semplice e pulito. Completamente personalizzabile.
Realizzato con elementi di terze parti a sorgente aperto come 
- Poppins Google Font
- Icone LineAwesome

Questi sono posti nella cartella `/vendor`. Ognuno ha è sottoposto alle proprie condizioni di licenza.

## Colori

Questo modello è dotato di tre colori di base: <var>orange</var>, <var>blue</var> e <var>green</var>. Altri colori possono essere facilmente aggiunti. Ad esempio, il codice CSS con l'aggiunta di un nuovo colore <var>red</var> sarà il seguente:

```css
:root
{
    /* altri colori e variabili */

    --color-red: #f00;
    --color-red-dark: #d00;
}

/* altre classi */

.resume.resume-red
{
    --theme-color: var(--color-red);
    --theme-color-dark: var(--color-red-dark);
}
```

Il colore del tema verrà applicato automaticamente una volta aggiunta la classe `.resume-red` nel documento HTML.

## Formati

Esistono due classi CSS per rappresentare i due formati possibili:
- `.resume_iso-a4` per il formato carta "A4" (210 &amp; 297 mm), come descritto nello standard ISO.
- `.resume_us-letter` per il formato carta "US Letter" (216 &amp; 297 mm), come descritto nello standard americano. Può essere utilizzato anche per il formato "US Legal".

Chiedere alla propria azienda/scuola (o chiunque debba ricevere il curriculum) il formato corretto da utilizzare.

Nella finestra di stampa, puoi anche scegliere di stampare con un formato di carta diverso da quello indicato dalla classe CSS. Ma, in questo caso, non sono garantiti buoni risultati.

## Stampa o Creazione PDF

Una volta aperto il file `resume.html`, premere <kbd>Ctrl</kbd> , <kbd>P</kbd> (o <kbd>Command</kbd> <kbd>P</kbd> su MacOS), per aprire la finestra di stampa. Da lì, è possibile impostare il formato carta (A4, US Letter).

Nella parte sinistra è possibile visualizzare l'anteprima di stampa. Se vedi alcune linee intorno al documento, allora imposta l'opzione <var>Margine</var> su '0' o 'Nessuno' (puoi trovare queste opzioni nella parte destra della finestra).

Inoltre, andrà posta l'opzione <var>Grafica di sfondo</var> su `Si`, altrimenti non sarà possibile visualizzare sfondi colorati.

Una volta impostato tutto correttamente, è possibile stampare il documento, indicando la stampante scelta. Se invece si desidera generare un PDF, scegliere <var>Salva come PDF</var> come stampante.
