# Suggerimenti

> Lasciare qui i vostri suggerimenti e documenti da implementare nel progetto Resistenza.

## Scopo

Questa cartella è lo **spazio di raccolta** per tutto ciò che le persone vogliono contribuire al progetto: suggerimenti, idee, esperienze, correzioni, documenti, proposte. È il punto d'ingresso tra la comunità e il lavoro operativo.

Non è un archivio morto: è un **flusso vivo**. Ogni suggerimento che entra qui viene letto, valutato e, se pertinente, trasformato in un task e implementato.

## Cosa si può lasciare

- **Suggerimenti** — idee, proposte, miglioramenti, correzioni.
- **Documenti** — testi, analisi, ricerche, esperienze vissute.
- **Domande** — dubbi, questioni aperte, punti da chiarire.
- **Esperienze** — racconti di chi vive il sistema da dentro (disoccupato, studente, operaio, piccolo imprenditore, avvocato, ...).
- **Proposte di struttura** — nuove fasi, nuovi circuiti, nuovi meccanismi.

## Come

### Formato

- **Markdown** (`.md`).
- **Una voce per file**: un suggerimento, un documento, una domanda — uno per file.
- **Nominare il file** con: `autore-titolo.md` (es. `maria-crediti-per-bambini.md`). Se l'autore è anonimo, usare `anonimo-titolo.md`.

### Struttura consigliata

Ogni file dovrebbe contenere almeno:

```markdown
# Titolo del suggerimento

- **Autore**: (nome o anonimo)
- **Data**: AAA-MM-GG
- **Stato**: da-vedere

## Descrizione

Cosa suggerisci, cosa proponi, cosa chiedi.

## Motivazione

Perché. Da dove viene. Quale problema risolve o quale opportunità apre.

## Riferimenti

Link, documenti, pagine del progetto a cui si riferisce.
```

### Stati

Ogni suggerimento attraversa questi stati:

| Stato | Significato |
|---|---|
| `da-vedere` | Appena depositato. In attesa di triage. |
| `in-lavorazione` | Rael lo sta valutando o trasformando in task. |
| `implementato` | Il suggerimento è stato implementato nel progetto. |
| `archiviato` | Il suggerimento è stato letto e ritenuto non pertinente (o già coperto). |

**Rael** aggiorna lo stato nel file del suggerimento quando lo processa.

## Cosa succede dopo

1. **Triage** — Rael legge il suggerimento e lo valuta in base alla pertinenza con il progetto.
2. **Classificazione** — se pertinente, viene trasformato in un task in `Strumenti/piani/index.md`.
3. **Implementazione** — il task viene eseguito e il suggerimento viene aggiornato con lo stato `implementato`.
4. **Archiviazione** — se non pertinente, il suggerimento viene aggiornato con lo stato `archiviato` e una breve nota sul perché.

## Regole

- **Una voce per file.** Non mescolare più suggerimenti in un unico file.
- **Data obbligatoria.** Ogni suggerimento deve avere una data.
- **Autore opzionale.** Se vuoi restare anonimo, usa `anonimo`.
- **Lingua libera.** Italiano, inglese, o qualsiasi altra lingua. Rael traduce se necessario.
- **Non è un forum.** Non serve rispondere ad altri suggerimenti. Ogni file è una voce autonoma.
- **Non è un obbligo.** Puoi lasciare un suggerimento e non tornare. Il triage è di Rael, non tuo.

## Esempio

```markdown
# Crediti per bambini

- **Autore**: maria
- **Data**: 2026-10-26
- **Stato**: da-vedere

## Descrizione

I bambini non dovrebbero avere crediti propri, ma i genitori dovrebbero poter
trasferire crediti ai figli per beni condivisibili (libri, giochi, semi).

## Motivazione

I bambini sono il futuro del sistema. Se non possono accedere ai beni
condivisibili, il circuito si spezza alla generazione successiva.

## Riferimenti

- `Documenti/beni_condivisibili.md`
- `Documenti/crediti.md`
```

## Dove si trova

- **Cartella**: `Suggerimenti/` (root del progetto).
- **Indice**: questo file (`Suggerimenti/readme.md`).
- **README principale**: `README.md` (root) — sezione "Suggerimenti".
