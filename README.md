# Valutazione casa

Pagina singola per valutare un immobile durante la visita: superficie commerciale,
coefficienti di merito, costi d'acquisto e confronto col prezzo richiesto.

**Online:** https://UTENTE.github.io/valutazione-casa/ (sostituisci `UTENTE`)

## Cosa fa

- **Superficie commerciale** — mq principali più le voci accessorie che aggiungi
  (balcone 30%, terrazzo 35%, giardino 15%, cantina 25%, box 50%, posto auto 25%,
  sottotetto 30%, taverna 50%). Percentuali di prassi di mercato, tutte modificabili.
- **Prezzo di zona come forbice** min–max, nel formato delle quotazioni OMI.
- **Coefficienti di merito** — piano, conservazione, luminosità, esposizione, età ed
  edificio, riscaldamento, stato locativo, più una rettifica libera.
- **Due modi di cumulo** — somma sulla base `base × (1 + c1 + c2 + …)` oppure a cascata
  `base × (1+c1) × (1+c2) × …`. La pagina mostra sempre quanto farebbe l'altro.
- **Costo di possesso** — capitalizza la spesa annua eccedente il riferimento indicato.
- **Costo d'acquisto** — registro 2%/9% da privato (prezzo-valore se inserisci la rendita),
  IVA 4%/10% da impresa, notaio, agenzia, lavori.
- **Archivio** — salva più case e le ordina per scarto, esborso, valore o €/mq.

## Limiti dichiarati

Non è una perizia. Le imposte sono una stima: mancano l'imposta sostitutiva sul mutuo
e le categorie di lusso A/1, A/8, A/9. La classe energetica non è convertita in euro in
automatico. Il risultato vale quanto il prezzo al mq di partenza: usa le quotazioni OMI
della zona, non il prezzo richiesto per quella casa.

## Tecnica

Un solo file, nessuna dipendenza tranne il font da Google Fonts (senza rete usa quello di
sistema). Le case salvate restano nel browser di chi apre la pagina: non vengono condivise
e non passano da nessun server.
