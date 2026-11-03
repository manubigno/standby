# StandBy Player – guida all'installazione

Riproduttore musicale in stile StandBy di iPhone, collegato a Spotify, con schermo sempre acceso.
Funziona in orizzontale e in verticale. Senza collegamento mostra una **modalità demo**.

## Cosa ti serve
- Un account **Spotify Premium**: Spotify lo richiede per le app personali e per i comandi play/pausa/salta.
- Un account **GitHub** gratuito, per mettere l'app online in https.

---

## 1. Mettere l'app online (GitHub Pages, gratis)
1. Vai su https://github.com/new e crea un repository **pubblico**, ad esempio `standby`.
2. Clicca su **"uploading an existing file"** e trascina **tutti** i file di questa cartella:
   `index.html`, `manifest.webmanifest`, `icon-180.png`, `icon-192.png`, `icon-512.png`. Poi clicca su **Commit changes**.
3. Apri **Settings → Pages**. In "Branch" scegli `main` e la cartella `/ (root)`, poi clicca su **Save**.
4. Dopo circa un minuto l'app è raggiungibile all'indirizzo:
   `https://TUO-UTENTE.github.io/standby/`

## 2. Creare l'app su Spotify (5 minuti)
1. Vai su https://developer.spotify.com/dashboard, accedi e clicca su **Create app**.
2. Compila i campi:
   - **App name**: StandBy Player (il nome è libero)
   - **Redirect URI**: l'indirizzo esatto del punto 1.4, **con la `/` finale**
     (es. `https://tuo-utente.github.io/standby/`). Clicca su **Add**.
   - In "Which API/SDKs are you planning to use?" spunta **Web API**.
3. Clicca su **Save**, poi apri **Settings** e copia il **Client ID**.
4. *(Solo se lo usa anche qualcun altro)* In **User Management** aggiungi l'email Spotify di quella persona (al massimo 5 utenti).

> Suggerimento: apri l'app, vai in ⚙︎ Impostazioni e premi **Copia** accanto a "Redirect URI". Così copi l'indirizzo esatto da incollare su Spotify.

## 3. Collegare l'app
1. Sul telefono apri l'indirizzo dell'app.
2. Tocca lo schermo, poi ⚙︎ → incolla il **Client ID** → premi **Collega** → accetta su Spotify.
3. Avvia la musica dall'app Spotify, anche su un altro dispositivo: il player la mostra e la controlla.

## 4. Installarla come app a schermo intero
- **iPhone (Safari)**: tasto Condividi → **Aggiungi alla schermata Home**. Aprila dall'icona.
  Se l'accesso a Spotify ti riporta in Safari invece che nell'app, fai il collegamento direttamente da Safari e usa l'app da lì.
- **Android (Chrome)**: menu ⋮ → **Installa app** (oppure "Aggiungi a schermata Home").

## Uso
- **Tocca** lo schermo per mostrare i pulsanti: ☀︎ schermo sempre acceso, 🔈 dispositivi, ⛶ schermo intero, ⚙︎ impostazioni.
- **Scorri** a sinistra o a destra per cambiare vista: orologio + player → copertina grande → solo orologio.
- Tocca la barra di avanzamento per spostarti nel brano.

## Personalizzazioni (⚙︎)
- Orologio: Digitale / Impilato / Analogico; carattere Tondo / Sottile / Classico / Mono; formato 24 ore, secondi, data.
- Colore: automatico (preso dalla copertina del brano) oppure uno a scelta.
- Sfondo: nero, copertina sfocata, sfumato.
- Orologio a destra o a sinistra quando il telefono è in orizzontale.
- Modalità notte rossa (sempre attiva, oppure automatica in una fascia oraria), luminosità dell'app, protezione burn-in.

## Note
- Lo schermo resta acceso solo finché l'app è **aperta in primo piano**. Se il telefono non è in carica la batteria si scarica più in fretta.
- Su iPhone serve iOS 16.4 o successivo. Se "Modalità Risparmio energetico" è attiva, iOS può comunque spegnere lo schermo.
- Le impostazioni restano salvate sul dispositivo.
