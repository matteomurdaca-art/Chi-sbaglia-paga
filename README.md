# Chi Sbaglia Paga

**Scommetti sull'errore degli altri!**

Prototipo digitale di un gioco di quiz, bluff e scommessa.
Non basta sapere le risposte: bisogna prevedere **quando gli altri sbaglieranno**.

---

## Come si gioca (modalità Sfida al Banco)

Partita da 10 turni, si parte con 15 monete. Il ruolo si alterna a ogni turno:

- **Da Rispondente** — rispondi alla domanda entro 15 secondi. Il Banco ha già
  piazzato la sua scommessa su di te, coperta.
- **Da Puntatore** — il Banco deve rispondere: scegli la posta (1, 2 o 3 monete)
  e scommetti se indovinerà o sbaglierà.

### Punteggio

| Situazione | Esito |
|---|---|
| Rispondente, risposta corretta | 0, più 1 moneta per ogni puntata SBAGLIATO subìta |
| Rispondente, risposta errata | −2 monete |
| Puntatore, scommessa corretta | + la posta puntata |
| Puntatore, scommessa errata | − la posta puntata |
| Tempo scaduto | vale come errore / puntata persa |

Vince chi ha più monete al termine dei 10 turni.

### Il Banco ha un carattere

Ogni partita il Banco assume una personalità nascosta — **prudente**, **spavaldo**
o **lunatico** — che ne cambia il comportamento sia quando risponde sia quando
scommette. Sta a te capire con chi hai a che fare: il carattere viene rivelato
soltanto a fine partita.

---

## Provalo

Apri il link della versione online, oppure scarica `index.html` e aprilo con un
browser. Non richiede installazione né connessione dopo il primo caricamento.

## Stato del progetto

Prototipo v0.5, in fase di playtest. 200 domande su 7 categorie.
Esiste anche una versione fisica del gioco (carte, gettoni, regolamento) in Print & Play.

Feedback benvenuti: cosa funziona, cosa annoia, se il Banco è troppo prevedibile
o troppo casuale, e se il tempo a disposizione è quello giusto.

## Contatti

Per feedback, segnalazioni o proposte editoriali:
**info.chisbagliapaga@gmail.com**

---

## Licenza

© 2026 Matteo Murdaca — Tutti i diritti riservati.
Materiale reso disponibile ai soli fini di playtest su invito.
Vedi [LICENSE.txt](LICENSE.txt) per le condizioni d'uso.
