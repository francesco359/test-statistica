# StatLab – Statistica per l’Economia (GitHub Pages)

Versione web **statica** dell'app di ripasso per l'esame della prof.ssa Barbieri. Include i quiz della versione 3.0, il formulario dei 9 capitoli, la teoria, le simulazioni e le statistiche personali. **Non serve alcun server, database, framework o installazione.**

## Pubblicazione su GitHub Pages

1. Accedi a https://github.com/new e crea un repository pubblico, per esempio `statlab-economia`.
2. **Estrai lo ZIP** scaricato da ChatGPT sul computer. Non caricare il file ZIP come tale: devi caricare i file che contiene.
3. Su GitHub apri il repository e scegli **Add file → Upload files**. Carica `index.html` e `README.md` nella **radice del repository** (aggiungi anche `.nojekyll`, se visibile). Conferma con **Commit changes**.
4. Apri **Settings → Pages**. In **Build and deployment**, imposta **Source: Deploy from a branch**, seleziona il branch `main` e la cartella **/(root)**, poi **Save**.
5. Dopo la pubblicazione, il sito sarà raggiungibile a un indirizzo simile a `https://TUO-USERNAME.github.io/statlab-economia/`. Copia questo link e condividilo con i compagni.

> Se il nome del repository è `TUO-USERNAME.github.io`, l'URL sarà `https://TUO-USERNAME.github.io/`.

## Cosa c'è nel pacchetto

- `index.html`: tutta l'applicazione in **un unico file**, completo di quiz, teoria, formulario, stile e script.
- `.nojekyll`: disattiva l'elaborazione Jekyll; utile per la pubblicazione diretta su GitHub Pages.
- `README.md`: queste istruzioni.

## Dati e privacy

- Lo storico, le percentuali di errori per capitolo e i profili sono salvati tramite `localStorage` **nel browser di ciascun utente**. Nessun risultato viene inviato a GitHub o reso visibile agli altri.
- I salvataggi NON sono condivisi tra dispositivi, browser o utenti e NON vengono sincronizzati. Per trasferirli, utilizzare la funzione **Esporta backup JSON** e successivamente **Importa backup** nell'app.
- Se hai già usato StatLab come file `.html` sul computer, il salvataggio precedente **non verrà trasferito automaticamente** all'URL GitHub Pages, perché l'origine web è diversa. Fai prima un backup JSON dalla vecchia versione e importalo nella versione online.
- Pulire i dati del browser può cancellare lo storico locale. Esegui backup periodici.
- GitHub Pages pubblica il contenuto del repository pubblicamente. Non inserire qui file di backup personali con risposte o nomi reali degli studenti.

## Aggiornamenti

Per aggiornare la banca dati o l'app, sostituisci `index.html` nel repository con la versione più recente e conferma il commit. I risultati nel browser rimangono disponibili se l'URL del sito e la chiave di salvataggio interna non cambiano.

## Note

Il materiale è un ausilio di studio non ufficiale, non un servizio della docente o dell'università. La banca dati della versione 3.0 contiene **228 quesiti** e un formulario di **86 schede**. GitHub Pages permette soltanto l'hosting statico: per account cloud, classifiche comuni o sincronizzazione tra compagni servirebbero servizi aggiuntivi.
