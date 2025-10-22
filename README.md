═══════════════════════════════════════════════════════════════
🌶️  LP NDUJA - AUTOPLAY AUTOMATICO  🌶️
═══════════════════════════════════════════════════════════════

VERSIONE: 1.0.2
AUTORE: LP Nduja
DATA: Ottobre 2025

═══════════════════════════════════════════════════════════════
📖  DESCRIZIONE
═══════════════════════════════════════════════════════════════

LP Nduja è un'estensione Chrome che automatizza la visualizzazione
dei video.

FUNZIONALITÀ:
✅ Riproduzione automatica di tutti i video del corso
✅ Gestione automatica delle categorie e sottocategorie
✅ Pop-up simpatici con proverbi calabresi
✅ Notifiche di stato in tempo reale
✅ Recupero automatico dopo errori di connessione
✅ Auto-click su popup di errore
✅ Shadow DOM per zero interferenze

═══════════════════════════════════════════════════════════════
🚀  INSTALLAZIONE
═══════════════════════════════════════════════════════════════

1. Estrai la cartella "nduja" dallo ZIP

2. Apri Google Chrome e vai su:
   chrome://extensions/

3. Attiva "Modalità sviluppatore" (interruttore in alto a destra)

4. Clicca su "Carica estensione non pacchettizzata"

5. Seleziona la cartella "nduja" estratta

6. L'estensione "LP Nduja" apparirà nella lista!

7. Vai su dettagli e Automatically allow access on the following sites "OFF"

═══════════════════════════════════════════════════════════════
📚  UTILIZZO
═══════════════════════════════════════════════════════════════

MODALITÀ CORSO COMPLETO:
1. Accedi al corso
2. Assicurati che nessuna lezione sia in corso, se così fosse aspetta che termini
3. In alto a destra fai partire l'estensione
3. Vedrai pop-up con lo stato di avanzamento
4. Rilassati e lascia che faccia tutto da solo! 🏖️

COSA SUCCEDE:
- Apre automaticamente tutte le categorie
- Riproduce ogni video in sequenza
- Salta le lezioni già completate (100%)
- Mostra pop-up simpatici ogni 20-30 secondi
- Gestisce errori di connessione automaticamente


═══════════════════════════════════════════════════════════════
⚙️  CONFIGURAZIONE AVANZATA (OPZIONALE)
═══════════════════════════════════════════════════════════════

Se vuoi modificare i parametri, apri "autoplay_unified.js"
e cerca la sezione "CONFIG BASE":

PLAYBACK_SPEED = 1.0         → Velocità video (1.0 = normale)
DELAY_TENDINA = 8000-10000   → Attesa apertura categorie (ms)
EXTRA_BUFFER = 35000-45000   → Buffer extra per completamento (ms)
STEP_WAIT = 28000-32000      → Attesa tra controlli (ms)

Pop-up ticker = 25000 ±5000  → Frequenza pop-up simpatici (ms)

═══════════════════════════════════════════════════════════════
🔧  RISOLUZIONE PROBLEMI
═══════════════════════════════════════════════════════════════

PROBLEMA: L'estensione non si carica
SOLUZIONE: Verifica che la cartella contenga:
  - manifest.json
  - autoplay_unified.js
  - favicon-16x16.png (opzionale)
  - android-icon-48x48.png (opzionale)
  - android-icon-144x144.png (opzionale)

PROBLEMA: I video non partono
SOLUZIONE: Assicurati di essere sulla pagina principale del corso
           con tutte le categorie visibili.

PROBLEMA: Pop-up troppo frequenti
SOLUZIONE: Modifica il valore "startTicker(25000, 5000)" 
           nel file autoplay_unified.js aumentando i numeri.

PROBLEMA: Lo script si ferma dopo un errore
SOLUZIONE: L'estensione dovrebbe ripartire automaticamente.
           Se non succede, ricarica la pagina manualmente.

═══════════════════════════════════════════════════════════════
📝  LOG E DEBUG
═══════════════════════════════════════════════════════════════

Per vedere cosa sta facendo l'estensione:

1. Premi F12 per aprire DevTools
2. Vai su "Console"
3. Vedrai messaggi con tag [SEQ]:
   - "Trovate X macrocategorie"
   - "[1/5] Nome lezione - 0%"
   - "Video avviato a velocità normale"
   - "COMPLETATA 100%"

═══════════════════════════════════════════════════════════════
⚠️  AVVERTENZE
═══════════════════════════════════════════════════════════════

- Usa l'estensione responsabilmente
- Assicurati di avere una connessione stabile
- Non chiudere il browser durante l'esecuzione
- I video devono essere disponibili sulla piattaforma
- L'estensione NON bypassa restrizioni della piattaforma

═══════════════════════════════════════════════════════════════
📂  CONTENUTO CARTELLA "nduja"
═══════════════════════════════════════════════════════════════

nduja/
├── manifest.json              → Configurazione estensione
├── autoplay_unified.js        → Script principale
├── favicon-16x16.png          → Icona 16x16 (opzionale)
├── android-icon-48x48.png     → Icona 48x48 (opzionale)
└── android-icon-144x144.png   → Icona 128x128 (opzionale)

═══════════════════════════════════════════════════════════════
🌶️  CREDITI
═══════════════════════════════════════════════════════════════

Sviluppato con ❤️ e 🌶️ in Calabria

"Cu' prima non pensa, all'urtimu suspira"
(Chi prima non pensa, alla fine sospira)

NDUJA SUPREMACY! 🔥

═══════════════════════════════════════════════════════════════
📧  SUPPORTO
═══════════════════════════════════════════════════════════════

Per problemi o domande, controlla il file autoplay_unified.js
oppure consulta la documentazione inline nel codice.

═══════════════════════════════════════════════════════════════
📜  LICENZA
═══════════════════════════════════════════════════════════════

Uso personale. Non distribuire o modificare senza permesso.

═══════════════════════════════════════════════════════════════
🎉  BUONA FORTUNA CON LA LAUREA!
═══════════════════════════════════════════════════════════════

Ricorda: LP Nduja studia per te, ma tu devi superare gli esami! 😄

Vai a curcati! 😴
