# 🚀 Come Pubblicare il Link Privato per Apex Corse v3.0

Questa guida ti spiega come avere un **link privato online** per il gestionale di scuderia in **meno di 2 minuti**, **100% gratuito**, senza usare GitHub e senza scrivere una sola riga di codice.

---

## 🌟 Opzione 1: Netlify Drop (La più veloce al mondo: 30 secondi)
Non richiede installazioni, né GitHub, né carta di credito.

1. Apri il browser e vai su: **[app.netlify.com/drop](https://app.netlify.com/drop)**
2. Trascina la cartella intera `v3.0_Sistema_Aggiornamenti` nel cerchio al centro della pagina.
3. **Fatto!** In 5 secondi Netlify ti genera un link sicuro tipo:
   `https://apex-corse-team.netlify.app`
4. **Come fai gli aggiornamenti futuri?**
   - Quando facciamo una modifica qui, apri la pagina del tuo sito su Netlify, vai nella scheda *Deploys* e trascini di nuovo la cartella aggiornata.
   - A tutti i tuoi ragazzi spunterà all'istante il banner:  
     🔔 *"Nuovo Aggiornamento Disponibile! [ Aggiorna Ora ]"*

---

## 🏛️ Opzione 2: Sul vostro sito ufficiale (apexcorse.it)
Se avete l'accesso al pannello di gestione del sito `apexcorse.it` (es. cPanel, Plesk, FTP o Hosting Aruba/SiteGround):

1. Accedi alla gestione file del vostro hosting (o via FTP con FileZilla).
2. All'interno della cartella principale (es. `public_html` o `www`), crea una cartella chiamata `gestionale` (o `team`).
3. Carica tutti i file presenti dentro `v3.0_Sistema_Aggiornamenti`.
4. Il link per il team sarà:
   `https://www.apexcorse.it/gestionale`
5. Per aggiornare: basta sovrascrivere i file caricandoli di nuovo nella cartella.

---

## 📱 Come usarlo come App su Telefono e PC (PWA)
Grazie al file `manifest.json` e `sw.js` che abbiamo inserito nella v3.0:
- **Su Google Chrome / Microsoft Edge (PC/Mac)**:
  Nella barra degli indirizzi in alto a destra o nel menu spunterà l'icona con il pulsante **"Installa Apex Corse"**. Cliccandoci, l'app si installa come programma vero e proprio sul desktop con la sua icona!
- **Su Smartphone (Android / iPhone)**:
  Aprendo il link da Safari o Chrome, basta premere *Condividi* o *Menu* &rarr; **"Aggiungi a schermata Home"**. Comparirà l'icona ufficiale della scuderia.
