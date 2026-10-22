# Decisioni sotto pressione — Sicurezza IA nella PA

Simulatore didattico autonomo per la **Giornata 3** del corso sull'intelligenza artificiale nella Pubblica Amministrazione: **sicurezza, privacy e gestione del rischio nell'uso quotidiano**.

È una rielaborazione del simulatore iniziale «Sicurezza IA & Privacy nella PA», che presentava 4 casi con un timer di 40 secondi. La nuova versione amplia gli scenari e sostituisce le risposte istantanee con **decisioni in due tempi**.

## Avvio rapido

1. Scarica `index.html`.
2. Aprilo con un browser moderno (Chrome, Firefox, Edge o Safari), anche senza connessione.
3. Seleziona **Inizia il laboratorio**.

Non occorre installare software né configurare API o account. È un'applicazione statica in un unico file HTML, con CSS e JavaScript incorporati. Non usa librerie o CDN esterni.

## Pubblicazione con GitHub Pages

1. Crea un repository GitHub, ad esempio `sicurezza-ia-pa` (oppure utilizza un repository già esistente dedicato all'esercitazione).
2. Carica nella **radice** del repository `index.html` e `Readme.MD`.
3. Apri **Settings → Pages**.
4. In **Build and deployment** imposta **Deploy from a branch**, seleziona `main` e la cartella `/(root)`, quindi salva.
5. Una volta pubblicato, l'indirizzo seguirà la forma `https://NOME-UTENTE.github.io/NOME-REPOSITORY/`.

Se GitHub Pages non è disponibile per il repository/account, verifica le impostazioni e i permessi del repository. Il sito non necessita di build.

> Puoi rinominare il repository come vuoi; mantieni invece `index.html` tutto minuscolo perché GitHub Pages lo riconosca come pagina iniziale.

## Struttura didattica

**Destinatari:** personale della Pubblica Amministrazione italiana, senza prerequisiti tecnici avanzati.  
**Durata consigliata:** **40–55 minuti**, adattabile.  
**Modalità:** discussione per piccoli gruppi e confronto in plenaria; non è necessario utilizzare strumenti di IA reali.  
**Numerosità indicativa:** 22 partecipanti divisi in 4 gruppi da 5–6 persone.

| Fase | Tempo indicativo | Come condurla |
| --- | ---: | --- |
| Regole del gioco e organizzazione | 4–5 minuti | Spiegare le quattro opzioni A/B/C/D |
| Otto casi in due tempi | 32–40 minuti | Scelta iniziale → dettaglio nuovo → nuova scelta → debrief |
| Restituzione finale | 5–10 minuti | Confrontare motivazioni e variazioni di decisione |

**Suggerimento per le tre ore del corso:** se il tempo disponibile è limitato, utilizza i casi 1, 3, 4, 6 e 8; per un laboratorio esteso usa tutti e otto. Puoi passare da un caso all'altro tramite la navigazione laterale.

### I casi

1. **Ho tolto il nome** — pseudonimizzazione, dato sanitario, segnalazione dopo un invio improprio.
2. **Il report sembra innocuo** — report pubblico aggregato e file di origine con dati identificativi.
3. **Nessun nome, ma è riservato** — capitolato di gara non pubblicato, riservatezza e scelta dello strumento.
4. **La norma sembra giusta** — riferimenti normativi non verificati e conseguenze di una risposta già comunicata.
5. **Il criterio apparentemente neutro** — distorsioni, priorità di accesso e supervisione sostanziale.
6. **Chi dà gli ordini all'assistente?** — prompt injection in una pagina web e potenziale incidente tecnico.
7. **È integrato nel programma: sarà consentito?** — funzionalità di IA non valutata e informazioni mancanti.
8. **È già successo** — caricamento improprio di dati, conservazione delle tracce e procedura di segnalazione.

### Cosa significano le opzioni

- **A** — Procedo, dopo le normali verifiche.
- **B** — Mi fermo e correggo il metodo.
- **C** — Segnalo tramite il canale interno.
- **D** — Chiedo un'informazione decisiva.

**D non è un errore di per sé:** talvolta è la scelta più ragionevole. La risposta proposta cambia quando emergono fatti nuovi. In casi reali, fermarsi e chiedere chiarimenti possono andare insieme.

## Funzioni dell'app

- Due decisioni per ogni scenario, con un nuovo elemento rivelato solo dopo la prima scelta.
- Soluzione e note per il formatore nascoste fino alla fine del caso.
- Timer opzionale con durate di 1, 2, 3 o 5 minuti; avvio, pausa e azzeramento.
- Navigazione libera tra gli otto casi (utile per gruppi che lavorano in parallelo).
- Contatore dei casi discussi e riepilogo finale con confronto tra scelte e soluzioni suggerite.
- Campo facoltativo per appunti *solo nella pagina corrente*.
- Download locale di un riepilogo `.txt` **senza gli appunti liberi**.
- Modalità schermo intero, layout responsive e supporto a tasti A/B/C/D fuori dai campi di inserimento.
- Nessuna richiesta di account, nessun backend, nessuna API di IA, nessuna raccolta centralizzata delle risposte.

### Un limite da tenere presente

L'app non sincronizza le risposte tra dispositivi. Per un'aula si consiglia la proiezione dal computer del docente e la raccolta delle scelte a voce, per alzata di mano o tramite la chat già in uso nel corso. Il contatore e le risposte si riferiscono **solo al browser aperto**.

Le risposte **non vengono salvate automaticamente**: un ricaricamento della pagina le azzera. Se vuoi conservarne un riepilogo, scaricalo prima di chiudere o aggiornare la pagina.

## Coerenza con il corso

Il laboratorio riprende la prima parte della Giornata 3: riconoscibilità delle persone, distinzione tra dato anonimo e informazione riservata, bias, prompt injection, affidabilità degli output e gestione degli incidenti. Due passaggi sono particolarmente importanti:

- **La sicurezza comincia prima di premere Invio.** Bisogna verificare dati, documento, strumento e finalità.
- **Controllare non significa soltanto rileggere.** Fonti, dati, contesto e conseguenze vanno verificati in modo sostanziale.

La simulazione non approfondisce la checklist e la registrazione documentale in modo sistematico, perché questi temi sono previsti nella **Giornata 4**. È un ponte, non una ripetizione.

## Fonti per i principi richiamati

- [GDPR — Regolamento (UE) 2016/679, articoli 4, 5, 32 e 33](https://eur-lex.europa.eu/legal-content/IT/TXT/?uri=CELEX:32016R0679)
- [Legge 23 settembre 2025, n. 132 — articolo 14 (IA nella PA)](https://www.normattiva.it/eli/id/2025/09/25/25G00143/CONSOLIDATED)
- [OWASP — LLM01:2025 Prompt Injection](https://genai.owasp.org/llmrisk/llm01-prompt-injection/)
- [Regolamento (UE) 2024/1689 — AI Act](https://eur-lex.europa.eu/eli/reg/2024/1689/oj?locale=it)

Le fonti servono a inquadrare i principi. **Non tutte le decisioni simulate discendono automaticamente da un singolo articolo di legge**: sono scelte operative motivate dal contesto ipotetico e subordinate alle procedure dell'ente.

In particolare, l'invio improprio di dati personali va segnalato internamente senza ritardo. Spetta al titolare del trattamento e alle funzioni competenti verificare se ricorra una violazione di dati personali e, nei casi previsti dall'articolo 33 GDPR, se sia necessaria la notifica all'autorità di controllo, senza ingiustificato ritardo e, ove possibile, entro 72 ore dalla conoscenza.

## Privacy e sicurezza dell'applicazione

- L'app è **solo didattica** e usa esclusivamente scenari inventati.
- Non invia informazioni a server e non richiede permessi di accesso a documenti.
- Non utilizzare nomi, dati sanitari o informazioni riservate reali negli appunti.
- Lo scaricamento del riepilogo è un'operazione locale del browser.
- In fase di pubblicazione su GitHub, evita di aggiungere file contenenti dati d'ufficio o documenti interni.
- Il sito non sostituisce policy, valutazioni, autorizzazioni e procedure ufficiali dell'amministrazione.

## Personalizzare gli scenari

Nel file `index.html`, trova la costante JavaScript `CASES`.

Per ogni caso puoi modificare:

- `scene`: scenario iniziale;
- `question1`, `best1`, `why1`: domanda, risposta proposta e motivazione iniziali;
- `twist`: nuovo elemento;
- `question2`, `best2`, `why2`: seconda decisione;
- `discuss`: domanda per la discussione;
- `steps`: azioni operative da ricordare;
- `lesson`: messaggio conclusivo.

Le opzioni A/B/C/D sono definite nella costante `OPTIONS`. Il numero dei casi è ricavato automaticamente dall'array `CASES`, ma il riepilogo contiene la dicitura statica **16 decisioni**, che va aggiornata se cambi il numero dei casi.

## Verifiche consigliate prima della lezione

1. Apri `index.html` senza connessione per verificare che non dipenda dalla rete.
2. Prova da un computer collegato a un proiettore e verifica leggibilità a distanza.
3. Fai una prova del timer e del pulsante **Mostra soluzione e discussione**.
4. Verifica che il docente conosca il percorso di segnalazione effettivo previsto dall'ente: l'app non ne inventa uno.
5. Verifica gli aggiornamenti normativi prima dell'edizione del corso.

---

**Versione:** 1.0 · Ottobre 2026  
**Formato:** HTML5/CSS/JavaScript, senza dipendenze esterne  
**Ambito:** formazione del personale della Pubblica Amministrazione italiana
