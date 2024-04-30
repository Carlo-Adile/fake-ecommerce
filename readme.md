PROGETTO: fake-ecommerce

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

DEFINIZIONE:
Realizzare un sito fantoccio che simuli l'interfaccia e le funzionalità di base di un e-commerce combinando le recenti tecnologie usate sia lato front-end che back-end come vue-vite e php.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

COMPONENTI BASE INDIVIDUABILI IN QUALSIASI E-COMMERCE:

//componenti che richiedono lo sviluppo combinato lato front e back

- REGISTRAZIONE E LOGIN

- IL MIO ACCOUNT E WISHLIST

- PRODOTTI (database, cards);

- CARRELLO

- PAGAMENTI

//componenti strettamente lato front

- SISTEMA DI NAVIGAZIONE

//componenti strettamente lato back

- DATABASE DELLE TRANSAZIONI

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

TECNOLOGIE E STRUMENTI INDIVIDUATI PER LO SVILUPPO:

- Vue Vite:
Per lo sviluppo dell'interfaccia utente e componenti dinamici

- Servizi API:
Per l'ottenimento di una lista dignitosamente lunga di prodotti con relative informazioni.

- PHP:
Per i servizi di autenticazione, sessione attiva (es.carrello) e gestione delle transazioni.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

ROOT:

- APP (main)
  - NAVBAR
  - ACCOUNT
    - REGISTRAZIONE E LOGIN
      - LOGOUT
      - WISHLIST
      - I MIEI ORDINI
  - CARRELLO
    - SEZIONE PAGAMENTO
    - RIMUOVI ITEM
  - VETRINA
    - SEZIONE PRODOTTI ATTIVA (default: TUTTI)
      - FILTRI
      - ORDINA (es.prezzo, alfabetico, recensioni...)
  - SERVIZIO CLIENTI
  - DATABASE
    - ORDINI
    - PAGAMENTI
    - RECENSIONI
    - SPEDIZIONI
    - RECENSIONI
    - ANALISI DATI COMMERCIALI


