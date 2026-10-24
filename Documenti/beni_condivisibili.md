# Beni condivisibili

> I beni condivisibili non cambiano proprietario: cambiano custode.
> Questo documento definisce il meccanismo di **custodia rotante**
> e il ruolo dei **centri culturali** come nodi fisici dei mercatini.

---

## 1. Il terzo spazio del mercatino

Fino a ora il mercatino ha due circuiti:

- **Beni usati** — cambiano proprietario, si prenotano (24h), si scambiano con crediti.
- **Buoni** — emessi dalla fondazione, usati per ricevere beni a casa o nel mercatino più vicino.

Si aggiunge un **terzo circuito**:

- **Beni condivisibili** — non cambiano proprietario, cambiano **custode**.
  Non si vendono, non si donano: si **custodiscono** e si **rimettono in circolo**.

La differenza fondamentale:

| | Beni usati | Beni condivisibili |
|---|---|---|
| **Cambia** | proprietario | custode |
| **Stato** | disponibile / prenotato / venduto | in circolo / in custodia / archiviato |
| **Valore** | crediti | indice di trasmissione |
| **Meccanismo** | prenotazione (24h) | custodia (periodo massimo) |
| **Tono** | transazione | patto |

---

## 2. Il patto di custodia

Non serve un contratto legale. Serve un **patto** — una frase che chi prende
il bene accetta:

> "Questo bene è di tutti. Lo custodisco finché lo uso.
> Quando non lo uso più, lo rimetto in circolo.
> Non lo vendo, non lo dono, non lo tengo per sempre."

Il patto è **registrato sulla blockchain** al momento della prima custodia.
Non è un contratto: è una **dichiarazione di intenti**.
La blockchain lo rende visibile e verificabile.

---

## 3. La custodia rotante

### 3.1 Gli stati del bene

Un bene condiviso ha **tre stati**:

- **`in_circolo`** — il bene è disponibile sullo scaffale, chiunque può prenderlo.
- **`in_custodia`** — il bene è con una persona, che lo sta usando.
- **`archiviato`** — il bene non è più in circolo (perduto, danneggiato, o non rimesso in circolo).

### 3.2 La durata della custodia

Chi prende un bene lo custodisce per un **periodo massimo** (es. 30 giorni,
o "finché non lo uso più"). Al termine:

- Il bene **torna automaticamente in circolo** (stato: `in_circolo`).
- Se chi custodisce non lo rimette in circolo entro X giorni, il bene viene
  **segnalato** (non punito) e passa a `archiviato` — ma resta tracciato
  sulla blockchain.

### 3.3 Nessun blocco

A differenza della prenotazione dei beni usati, la custodia **non ha blocchi**.
Il bene condiviso non è un bene da "prenotare": è un bene da "custodire".
Il tono è diverso: non c'è un prezzo che incentiva la restituzione,
c'è solo il **patto**.

### 3.4 La bellezza della socialità e della condivisione

La blockchain registra la **storia delle custodie**:
chi l'ha custodito prima, per quanto, se è stato rimesso in circolo.
Questo crea la **bellezza della socialità e della condivisione**:
chi prende un bene "vede" la sua storia, e può **chiedere un'opinione**
sulla lettura a chi l'ha custodito prima.

Non è una pressione: è un **invito**. Chi ha letto il libro
può raccontare la sua esperienza, condividere un passaggio,
raccontare perché lo ha rimesso in circolo.
La storia del bene diventa una **storia di persone**,
non un elenco di transazioni.

> "Questo libro è passato per le mani di 12 persone.
> Chiedi a Maria: lei l'ha letto in inverno,
> e dice che il capitolo 7 è il più bello."

La blockchain non punisce: **racconta**.
E chi prende il bene non prende solo il bene:
prende anche la **storia** di chi l'ha custodito prima.

---

## 4. Il valore di trasmissione

Ogni bene condiviso ha un **indice di trasmissione**:

- **T** = numero di custodie completate
- **P** = numero di persone diverse che l'hanno custodito
- **D** = durata totale in circolo (giorni)

Questi numeri sono **visibili sulla blockchain** e **non si accumulano**
(a differenza dei crediti). Servono per:

- **Misurare il capitale cognitivo** del mercatino
  (quanti beni, quante custodie, quante persone).
- **Incentivare la condivisione** (chi rimette in circolo un bene
  "guadagna" visibilità, non crediti).
- **Decidere quali beni tenere in circolo** (un bene con T=20 e P=15
  è più "vivo" di uno con T=1 e P=1).

**I beni condivisibili non hanno un prezzo in crediti**:
hanno un **indice di trasmissione**. Più sono condivisi, più "valgono"
in termini di capitale reale. Non in crediti — in **visibilità**.

---

## 5. I centri culturali come nodi fisici

### 5.1 Il mercatino e il suo corpo

Il mercatino è il **sistema** (blockchain, crediti, regole).
Il centro culturale è il **corpo** del mercatino.

- Il mercatino può esistere anche senza un centro culturale
  (es. online, o in un altro spazio).
- Il centro culturale può ospitare più di un mercatino
  (es. un mercatino di libri + un mercatino di utensili).
- La **fondazione** può "adottare" centri culturali esistenti
  (non costruirli), riducendo il costo iniziale.

### 5.2 Cosa ospita il centro culturale

Ogni centro culturale ospita:

- **Lo scaffale** — fisico, visibile, accessibile a tutti
  (anche a chi non ha il client).
- **Il server locale** — la blockchain del mercatino, come già previsto.
- **I custodi** — volontari che gestiscono lo scaffale, registrano le custodie,
  segnalano i beni da rimettere in circolo.

### 5.3 I custodi

I **custodi** sono i volontari che:

- Gestiscono lo scaffale fisico.
- Registrano le custodie sulla blockchain.
- Segnalano i beni da rimettere in circolo.
- Accolgono chi arriva per la prima volta.
- Non sono dipendenti: sono **custodi** del mercatino,
  come i beni che custodiscono.

---

## 6. I libri come primo caso

I **libri** sono il primo bene condiviso, perché:

1. **Sono capitale cognitivo puro** — "le competenze, le conoscenze,
   le pratiche condivise. Non si può esaurire: si può solo trasmettere"
   (capitale.md, glossario).
2. **Sono il primo bene che rompe la fictione del valore** — un libro ha
   un prezzo di copertina (capitale fittizio) ma il suo valore usale
   è la conoscenza che contiene. Condividerlo gratuitamente è l'atto
   più diretto di conversione da capitale fittizio a capitale reale.
3. **Sono il bene più "scambiabile" possibile** — a differenza di un utensile
   o un mobile, un libro non ha un solo proprietario "vero":
   ha tanti lettori quanti ne esistono. La proprietà è la fictione
   più evidente.

### 6.1 L'espansione ai beni condivisibili

Il meccanismo si estende a:

- **CD/DVD** (musica, film, documentari)
- **Mappe e guide** (turismo, orientamento)
- **Manual e libri di tecnica** (riparazione, cucina, giardinaggio)
- **Semi da riprodurre** (il bene per eccellenza: si moltiplica)
- **Strumenti di misura** (metro, livella, termometro — si usano
  e si rimettono in circolo)

La regola è sempre la stessa: **il bene non si consuma, si custodisce**.

---

## 7. La stagionalità dei beni condivisibili

Come per i beni usati, anche i beni condivisibili hanno stagionalità:

- **Inverno**: più custodie (la gente sta in casa).
- **Estate**: meno custodie, ma più "scambio" (la gente viaggia, porta beni).

La **percentuale** (sistema di % per la gestione delle finanze) si adatta:
in inverno il mercatino dei libri ha più "domanda", in estate meno.
Questo non cambia il meccanismo, ma cambia il **ritmo** dello scaffale.

---

## 8. Domande aperte

1. **Chi gestisce lo scaffale?** I custodi sono volontari, dipendenti,
   o un mix?
2. **Quanto dura la custodia?** 30 giorni? 60? Dipende dal tipo di bene?
3. **Cosa succede a un bene "morto"** (T=1, P=1, D=30)?
   Si archivia, si scarta, si "riattiva"?
4. **I beni condivisibili hanno un "prezzo" in crediti?** No, ma hanno
   un **indice di trasmissione**. Come si visualizza?
5. **Il centro culturale è un "nodo" della blockchain?** Sì, ma è il
   **corpo** del mercatino, non il mercatino stesso. Come si registra?
6. **I beni condivisibili sono "prenotabili"?** No: sono **custodibili**.
   La prenotazione è per i beni usati (che cambiano proprietario).
   La custodia è per i beni condivisibili (che cambiano custode).

---

## 9. Il tradeoff

**Vantaggio**: il meccanismo dei beni condivisibili è **più semplice**
di quello dei beni usati (niente crediti, niente prenotazioni,
niente blocchi). È un **sistema a tre stati** (in circolo / in custodia /
archiviato), senza blocchi e scadenze punitive.

**Svantaggio**: richiede **fiducia**. Chi prende il bene deve rimetterlo
in circolo. Non c'è un "prezzo" che incentiva la restituzione:
c'è solo il **patto**. La blockchain rende il patto visibile,
ma non lo impone.

**Compromesso**: la blockchain registra la **storia delle custodie**,
così chi prende un bene "vede" la sua storia (chi l'ha custodito prima,
per quanto, se è stato rimesso in circolo). Questo crea la
**bellezza della socialità e della condivisione**: chi prende il bene
può chiedere un'opinione sulla lettura a chi l'ha custodito prima.
La storia del bene diventa una **storia di persone**,
non un elenco di transazioni.

