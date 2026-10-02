# Resistenza

> Un sistema anticapitalista che usa il capitalismo per fottere il sistema.

## L'idea

Creare un **mercatino dell'usato** gestito con server e blockchain, dove i partecipanti ricevono **crediti** in base alle donazioni. Il sistema funziona come un circuito chiuso di beni e crediti, con regole che tendono a zero il profitto a fine anno.

## Come funziona

### Blockchain proprietaria e centralizzata
- Ogni mercatino ha una **blockchain proprietaria e centralizzata** con **controllo totale** del server locale.
- I **client dei partecipanti** mantengono **copie** della blockchain locale per trasparenza e verifica.
- Quando un partecipante visita o interagisce con un mercatino, il client **seleziona automaticamente** il blocco locale con cui interagire e **scala i buoni** in base alle interazioni.
- La blockchain serve per **trasparenza e fiducia**, non per speculazione.

### Crediti
- Ogni partecipante che **dona** beni riceve **crediti** proporzionali al valore stimato della donazione.
- I crediti sono tracciati sulla **blockchain locale** del mercatino per trasparenza e immutabilità.
- I crediti **non sono denaro**: sono un diritto di acquisto interno al mercatino.

### Acquisti
- Gli acquisti si basano su:
  - **Cassa del mercatino**: il budget disponibile in quel momento.
  - **Periodo dell'anno**: stagionalità e domanda (es. più richieste in inverno, meno in estate).
- I prezzi sono calcolati in modo da **svuotare le casse** e portare il **no-profit a 0**.

### Sistema di % per la gestione delle finanze
- Per regolare le finanze dei mercatini e gestire **spese vive in denaro reale**, i buoni e il prezzo delle merci con denaro reale utilizzano un **sistema di percentuale**.
- La percentuale è **regolata in base alle necessità del mercatino** e viene **esposta ogni giorno aggiornata**.
- Questo meccanismo permette di bilanciare le uscite in denaro reale con i crediti interni, mantenendo la cassa in equilibrio.

### Prenotazione dei beni
- Un bene può essere **prenotato** da un partecipante.
- La prenotazione ha una **durata massima di 24 ore** (fermo).
- Se il bene **non viene ritirato** entro 24 ore:
  - La prenotazione **scade** e il bene torna disponibile.
  - Il cliente viene **bloccato per 1 settimana** dalle nuove prenotazioni.
  - Il blocco si applica **solo se il cliente possiede i buoni richiesti** per quel bene al momento della scadenza.

### Fine anno
- La **percentuale di credito** viene tesa verso lo zero: si svuotano le casse.
- Se **avanzano soldi**, si acquistano **beni nuovi** da mettere nel **reparto nuovo**.
- Obiettivo: **no-profit = 0** a fine esercizio.

### Legalità
- Si usano **metodi legali** in stile **buoni** (es. buoni pasto, buoni spesa, buoni libro).
- **Stato: Italia** — il sistema si inserisce nel quadro normativo italiano (es. cooperative, associazioni, 501(c) equivalenti italiani).

### Il capitale sono le persone
- Il **capitale del sistema** non è il denaro, ma le **persone che vi aderiscono**.
- Se i partecipanti diventano **dipendenti del sistema**, non ricevono solo uno stipendio, ma anche **buoni** dal rendimento del complesso.
- Questi buoni sono usati in una **seconda sovrastruttura di distribuzione**: la **fondazione**.
- La fondazione **invia i beni richiesti** con i buoni di secondo livello:
  - **Direttamente a casa** del dipendente
  - **Nel mercatino più vicino**

## Le Fasi

### Fase 1 — Consolidamento iniziale
- Definizione del modello economico
- Prototipo server + blockchain
- Test con gruppo pilota
- Lancio pubblico del primo mercatino

### Fase 2 — Fondazione e espansione
Dopo il consolidamento iniziale:

- **Fondazione non-profit** per raccogliere fondi e creare:
  - **Consorzi** di produttori e rivenditori
  - **Nuovi mercatini dell'usato**
- **Investimenti in edilizia sociale** per ospitare i partecipanti
- I mercatini possono **scambiarsi beni** e **sincronizzare le blockchain**
- Ogni blockchain è **locale** (ogni mercatino ha il proprio ledger)
- Lo scambio avviene **per beni**, non per buoni o moneta
- **Buoni di secondo livello**: la fondazione emette buoni che i dipendenti del sistema possono usare per ricevere beni direttamente a casa o nel mercatino più vicino

#### Consorzio autogestito
- La fondazione crea un **consorzio autogestito** per aiutare:
  - **Piccole e medie imprese**
  - **Chi fornisce le materie prime**: contadini, piccole realtà operaie, artigiani
- Obiettivo: **eliminare gli intermediari** tra produttore e consumatore
- Il consorzio **certifica** le catene di approvvigionamento e distribuzione **autonome e autogestite**
- La blockchain registra **non solo i buoni**, ma anche:
  - Le **catene di approvvigionamento** (da chi arriva il bene, da quale produttore)
  - Le **catene di distribuzione** (come il bene arriva al mercatino o al consumatore)
  - La **certificazione** della fondazione per ogni catena
- **Né intermediari né magazzini**: il bene passa direttamente dal produttore al mercatino o al consumatore, con tracciabilità completa sulla blockchain
- Il consorzio **non detiene stock**: opera come coordinatore e certificatore, non come depositario

### Fase 3 — SPA per servizi pubblici
- Formare una **SPA** per gestire:
  - **Servizi acqua pubblica**
  - **Servizi in concorrenza** con le multinazionali
- La SPA usa i **trucchetti** che le multinazionali usano per non pagare le tasse
- La SPA è **controllata al 100%** dalla fondazione

## Stato del progetto

| Fase | Descrizione | Stato |
|------|-------------|-------|
| 1 | Consolidamento iniziale (modello, prototipo, test, lancio) | 🔄 In corso |
| 2 | Fondazione non-profit, consorzi, edilizia sociale, espansione | ⏳ Da fare |
| 3 | SPA per servizi pubblici (acqua, concorrenza) | ⏳ Da fare |

## Roadmap

### Fase 1
- [ ] Definire la formula di calcolo dei crediti
- [ ] Progettare la **blockchain proprietaria e centralizzata** (ledger locale per mercatino)
- [ ] Progettare il **client** con copie della blockchain e selezione automatica del blocco locale
- [ ] Progettare il server (API, database, autenticazione)
- [ ] Definire le regole di stagionalità e svuotamento casse
- [ ] Definire il **sistema di percentuale** per la gestione delle finanze e delle spese vive in denaro reale
- [ ] Implementare il **sistema di prenotazione** dei beni (24h di fermo, blocco 1 settimana se non ritirato)
- [ ] Verificare il quadro legale italiano (cooperativa, associazione, 501(c))
- [ ] Prototipo MVP
- [ ] Test pilota
- [ ] Lancio

### Fase 2
- [ ] Costituire la fondazione non-profit
- [ ] Creare i consorzi di produttori e rivenditori
- [ ] Aprire nuovi mercatini dell'usato
- [ ] Investire in edilizia sociale
- [ ] Implementare lo scambio di beni tra mercatini
- [ ] Sincronizzazione delle blockchain locali
- [ ] Implementare i **buoni di secondo livello** della fondazione (distribuzione a casa o nel mercatino più vicino)
- [ ] Definire il **sistema di scalatura dei buoni** in base alle interazioni con i mercatini
- [ ] Definire il **meccanismo di selezione automatica del blocco locale** da parte del client
- [ ] Definire le **regole di sincronizzazione** tra blockchain locali
- [ ] Definire il **meccanismo di emissione e distribuzione** dei buoni della fondazione
- [ ] Definire il **sistema di incentivi** per i mercatini
- [ ] Definire il **sistema di incentivi** per i nodi
- [ ] Definire il **sistema di incentivi** per i validatori
- [ ] Definire il **sistema di incentivi** per i creatori di contenuti
- [ ] Definire il **sistema di incentivi** per i traduttori
- [ ] Definire il **sistema di incentivi** per i curatori
- [ ] Definire il **sistema di incentivi** per i moderatori
- [ ] Definire il **sistema di incentivi** per i contributor
- [ ] Definire il **sistema di incentivi** per i reviewer
- [ ] Definire il **sistema di incentivi** per i maintainer
- [ ] Definire il **sistema di incentivi** per i sponsor
- [ ] Definire il **sistema di incentivi** per i revisori
- [ ] Definire il **sistema di incentivi** per i redattori
- [ ] Definire il **sistema di incentivi** per i traduttori

### Fase 3
- [ ] Costituire la SPA
- [ ] Definire i servizi (acqua pubblica, concorrenza)
- [ ] Strategia fiscale (trucchetti anti-multinazionali)
- [ ] Lancio dei servizi

## Note

- Il sistema è **anticapitalista** nel senso che usa i meccanismi del capitalismo (offerta, domanda, prezzi) ma li piega al servizio della comunità.
- La **blockchain** serve per trasparenza e fiducia, non per speculazione.
- Il **no-profit** è il principio guida: ogni euro che entra deve uscire come bene o servizio.

## Domande aperte

- Qual è la formula esatta per calcolare i crediti in base al valore della donazione?
- Come strutturare la **blockchain proprietaria e centralizzata** (ledger locale per mercatino)?
- Come implementare il **client** con copie della blockchain e selezione automatica del blocco locale?
- Come gestire la stagionalità e lo svuotamento delle casse?
- Qual è il quadro legale italiano più adatto (cooperativa, associazione, 501(c))?
- Come strutturare la fondazione e i consorzi?
- Come implementare lo scambio di beni tra mercatini?
- Come sincronizzare le blockchain locali?
- Come emettere e distribuire i **buoni di secondo livello** della fondazione?
- Come strutturare il **consorzio autogestito** e la **certificazione delle catene di approvvigionamento** sulla blockchain?
- Come garantire la **tracciabilità completa** dal produttore al consumatore senza magazzini né intermediari?
