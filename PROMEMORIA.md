# Strumenti didattici — promemoria

A cura del prof. Vittorio Riccardi · economia aziendale
Ultimo aggiornamento: ottobre 2026

Questo file serve a ritrovare in fretta come funziona tutto, fra sei mesi o
se il lavoro passa a qualcun altro. Sta nel repository insieme al codice.

---

## 1. Che cosa c'è

**Piano dei conti S.p.A.** — consultazione, schema di bilancio, allenamento.
Sito: `https://profvr1.github.io/piano-dei-conti/`
Repository: `profvr1/piano-dei-conti`, file unico `index.html`

**Gestionale di contabilità** — libro giornale, mastri, situazione, chiusura, bilancio.
Sito: `https://profvr1.github.io/gestionale/`
Pannello docente: `https://profvr1.github.io/gestionale/?prof`
Repository: `profvr1/gestionale`, file `index.html` + cartella `esercizi/`

**Tre fascicoli di slide** (file .pptx, tenuti su Drive)
1. La partita doppia e le scritture di gestione — 76 slide
2. Le scritture di assestamento — 71 slide
3. Epilogo e chiusura dei conti — 28 slide

Ogni pagina è un **unico file HTML senza dipendenze esterne**: si apre anche
con un doppio clic, senza internet, e continuerà a funzionare negli anni.

---

## 2. Come si aggiorna un sito

1. Rinomina il file nuovo in `index.html`
2. Nel repository: **Add file → Upload files**
3. Trascina il file e conferma con **Commit changes**
4. Aspetta due minuti, poi ricarica con `Cmd + Shift + R`

Sostituisce il vecchio perché ha lo stesso nome. Il link non cambia mai.

Sul Mac tieni due cartelle distinte, `sito-piano-dei-conti` e `sito-gestionale`,
perché i file si chiamano entrambi `index.html` e nei Download si confondono.

---

## 3. Come si pubblica un esercizio

1. Apri il gestionale con `?prof` in fondo all'indirizzo
2. Scheda **Esercizio** → *Per il docente*
3. Compila titolo, consegna, data di chiusura, fase di partenza
4. Incolla la situazione di partenza nel riquadro (una riga per conto:
   nome o codice, importo, D oppure A) e premi **Leggi le righe incollate**
5. Controlla che i totali Dare e Avere coincidano
6. **Scarica il file dell'esercizio** — compare anche il link da condividere
7. Carica il file nella cartella `esercizi` del repository `gestionale`
   (entra prima nella cartella, poi Add file → Upload files)
8. Pubblica su Classroom il link `.../gestionale/?es=NOMEFILE` (senza `.json`)

Nomi dei file senza spazi, accenti e maiuscole. Meglio `5A-assestamento-01`.
Ricaricando un file con lo stesso nome si sostituisce e il link resta valido.

---

## 4. Modifiche al piano dei conti rispetto al libro

Il piano è quello della S.p.A. industriale di Barale-Ricci (284 conti),
verificato riga per riga anche contro il piano del volume di quinta:
codici, denominazioni, natura, destinazione ed eccedenza coincidono.

Sono stati aggiunti **8 conti**, per un totale di 292:

| Codice | Conto | Perché |
|---|---|---|
| 04.07 | Merci | il piano industriale non ha i conti delle merci, |
| 20.06 | Merci c/vendite | ma quasi tutti gli esercizi del libro sono su |
| 20.07 | Merci c/vendite on line | imprese commerciali. Presi dal piano della S.n.c. |
| 30.05 | Merci c/acquisti | che sta nello stesso PDF, con codici liberi negli |
| 30.06 | Merci c/apporti | stessi raggruppamenti perché quelli originali |
| 37.04 | Merci c/esistenze iniziali | erano già occupati dai conti industriali. |
| 37.13 | Merci c/rimanenze finali | |
| 41.09 | Disaggio su prestiti | usato dalla soluzione dell'esercizio 98 ma assente dal piano pubblicato |

**Una correzione:** `10.20 Versamenti azionisti c/capitale` è stato spostato
da *A I Capitale* ad *A VI Altre riserve*, come nel piano di quinta. I
versamenti in conto capitale non aumentano il capitale sociale.

**Due sviste del manuale, corrette nei dati:** i proventi finanziari
(40.01–40.03) e le rimanenze finali di materie (37.10–37.12) erano
etichettati "costo d'esercizio" pur avendo eccedenza Avere.

---

## 5. Da dire in classe la prima volta

- **Nome, cognome e classe** nella scheda Stampa: senza, il PDF non parte
- **Salva per continuare dopo** a fine ora. Il pallino in alto dice come stanno:
  arancione vuol dire non salvato
- **Non ricliccare il link** di Classroom dopo aver cominciato: ricarica
  l'esercizio da capo
- Il **PDF** serve per consegnare, il **file .json** per riprendere il lavoro.
  Sono due cose diverse

---

## 6. Cose da sapere

**I pulsanti che scaricano file non funzionano nell'anteprima di claude.ai.**
Vanno provati sul sito pubblicato. Stessa cosa per la stampa.

**Il lavoro degli studenti vive nel browser.** In laboratorio i computer sono
condivisi: senza il file salvato, il lavoro resta sulla macchina.

**Modificare una scrittura dopo epilogo e chiusura** annulla le scritture
automatiche, che vanno rieseguite. Il programma avvisa.

**Esercizio 98 (Fiorini spa):** il risconto sulle assicurazioni nella soluzione
dell'editore è 4.368, ma il calcolo corretto dà **4.380** (sei mesi di 8.760).
L'utile corretto è 111.863,58 invece di 111.851,58.

**Negli esercizi con ammortamenti** indica sempre a parte il valore del
fabbricato: `terreni e fabbricati 180.000, di cui 140.000 il fabbricato`.
Altrimenti si somma il fondo al costo storico.

---

## 7. Se un giorno servisse di più

Quello che oggi manca e richiederebbe un server a pagamento (circa 25 dollari
al mese): accesso personale degli studenti, salvataggio in cloud, consegne
automatiche, pannello per vedere chi ha fatto cosa.

Finché il controllo lo fai girando fra i banchi, non serve.

Il passo successivo più utile a costo quasi zero è un **dominio proprio**
(una ventina di euro l'anno): da quel momento i link non cambiano più,
qualunque cosa succeda sotto.
