# Chi Sbaglia Paga

**Scommetti sull'errore degli altri!**

Prototipo digitale di un gioco di quiz, bluff e scommessa.
Non basta sapere le risposte: bisogna prevedere **quando gli altri sbaglieranno** —
e ingannarli quando tocca a te.

---

## Tre modalità

- **🎩 Sfida al Banco** — da solo contro il computer, 10 turni, con progressione a livelli,
  monete accumulate e categorie sbloccabili.
- **👥 Tra amici** — da 3 a 6 giocatori con un solo telefono che gira al tavolo: le puntate
  si inseriscono di nascosto e il bluff torna quello vero, guardandosi in faccia. Il numero
  di turni proposto si adatta sempre al numero di giocatori, così nessuno risponde più
  degli altri.
- **🃏 In due + Banco** — 2 giocatori reali più il computer come terzo giocatore: risponde
  a turno, scommette e può vincere la partita.

---

## Come si gioca

Il ruolo si alterna a ogni turno.

**Nelle modalità multigiocatore** l'ordine è questo:

1. Il **Rispondente** legge la domanda ad alta voce — vede la domanda ma non le risposte — e
   dichiara pubblicamente **quanto ci crede** (posta 1, 2 o 3), mentre gli altri lo guardano in faccia.
2. Gli altri, uno alla volta e **di nascosto**, scelgono la propria posta e scommettono se
   **indovinerà** o **sbaglierà**.
3. Il Rispondente vede **quanto** hanno puntato gli altri (non su cosa) e ha **15 secondi**
   per rispondere davanti a tutti.

Nella Sfida al Banco, dove il telefono resta in mano a te, scegli la posta e rispondi
direttamente entro 15 secondi.

Ogni domanda mostra accanto alla categoria la sua **difficoltà** (facile / media / tosta):
è l'indizio che aiuta a leggere sia le proprie scommesse sia il comportamento del Banco.

### Punteggio

| Situazione | Esito |
|---|---|
| Rispondente, risposta corretta | +1 moneta per ogni avversario che aveva puntato SBAGLIATO |
| Rispondente, risposta errata | − la posta scelta, più 1 di penale per ogni avversario che aveva puntato GIUSTO |
| Puntatore, scommessa corretta | + la posta puntata |
| Puntatore, scommessa errata | − la posta puntata |
| Tempo scaduto | vale come errore |

Il premio è per chi **sorprende** l'avversario: rispondere bene quando tutti se lo
aspettavano non frutta nulla. Sbagliare apposta non conviene mai, perché la penale
la paga solo chi ha sbagliato.

Monete iniziali: 15 (18 in quattro giocatori, 20 da cinque in su).
Vince chi ne ha di più al termine.

### Il Banco ha un carattere

Ogni partita il Banco assume una personalità nascosta tra cinque — **prudente**,
**spavaldo**, **lunatico**, **specialista** (fortissimo in certe categorie, pessimo
in altre) e **opportunista** (ti punta contro quando sei in vantaggio). Aspetto e
frasi sono sempre identici: l'unico indizio è l'*identikit* che registra il suo
comportamento. Il carattere viene rivelato soltanto a fine partita.

### Progressione (modalità Sfida al Banco)

Le monete vinte finiscono in un salvadanaio che resta salvato sul dispositivo.
Cinque livelli da **Novellino** a **Squalo**: salendo, il Banco diventa più astuto.
Si sbloccano inoltre tre categorie speciali (⚽ Calcio italiano a 60 monete,
📼 Anni '80 e '90 a 140, 🏆 Record estremi a 240) e un aiuto a 90 monete che permette
di sbirciare la puntata coperta del Banco una volta a partita.

---

## Provalo

Apri il link della versione online, oppure scarica `index.html` e aprilo con un browser.
Non richiede installazione né connessione dopo il primo caricamento; può essere aggiunto
alla schermata Home come app.

## Stato del progetto

Prototipo in fase di playtest.
**920 domande** su 13 categorie (800 base + 120 nelle categorie sbloccabili),
5 caratteri del Banco, tre modalità di gioco.
Esiste anche una versione fisica del gioco (carte, gettoni, regolamento) in Print & Play.

Feedback benvenuti: cosa funziona, cosa annoia, se il Banco è troppo prevedibile
o troppo casuale, e se 15 secondi sono il tempo giusto.

## Contatti

Per feedback, segnalazioni o proposte editoriali:
**info.chisbagliapaga@gmail.com**

---

## Licenza

© 2026 Matteo Murdaca — Tutti i diritti riservati.
Materiale reso disponibile ai soli fini di playtest su invito.
Vedi [LICENSE.txt](LICENSE.txt) per le condizioni d'uso.
