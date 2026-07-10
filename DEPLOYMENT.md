# Pubblicazione online con GitHub Pages

Questa versione è già configurata per essere pubblicata online tramite GitHub Actions.

## Procedura

1. Crea un repository pubblico su GitHub.
2. Carica tutti i file e le cartelle presenti in questo progetto.
3. Assicurati che il branch principale si chiami `main`.
4. Apri `Settings`.
5. Vai in `Pages`.
6. In `Build and deployment`, scegli `GitHub Actions`.
7. Apri la scheda `Actions`.
8. Attendi il completamento del workflow `Deploy CTO Cockpit to GitHub Pages`.

L'indirizzo pubblico sarà simile a:

```text
https://TUO-USERNAME.github.io/NOME-REPOSITORY/
```

## Accesso dall'esterno

La pagina sarà raggiungibile:

- da computer esterni
- da smartphone e tablet
- da reti aziendali o domestiche
- tramite HTTPS

Il repository deve essere pubblico per utilizzare GitHub Pages gratuitamente con la configurazione standard.

## Importante: condivisione dei dati

GitHub Pages pubblica l'applicazione, ma non centralizza i dati.

Il LocalStorage è specifico per:

- browser
- dispositivo
- profilo utente
- dominio della pagina

Questo significa che due utenti che aprono la stessa pagina vedranno inizialmente gli stessi dati pre-caricati, ma le modifiche successive resteranno locali sul loro browser.

Per avere un portafoglio realmente condiviso e sincronizzato tra più utenti serve aggiungere un backend o un servizio cloud, ad esempio:

- Supabase
- Firebase
- Microsoft Dataverse
- SharePoint / Microsoft Lists
- API aziendale con database
