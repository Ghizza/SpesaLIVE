# Spesa LIVE

Webapp minimale per calcolare al volo la spesa mentre si fa la spesa. Nessun backend, nessun account: tutto resta sul dispositivo.

## Cosa fa

- Tabella **Prezzo × Quantità = Subtotale** con ricalcolo immediato del totale
- Aggiunta/eliminazione righe, gestione automatica di quantità vuota (= 1)
- Salvataggio automatico su `localStorage` (i dati sopravvivono alla chiusura del browser)
- Formato numerico e monetario italiano (`1.234,56 €`)
- Interfaccia ottimizzata per mobile, installabile come PWA (icona su home screen, avvio a schermo intero)
- Funziona offline dopo il primo caricamento

## Come usarla online

Apri dal browser del telefono:

**https://ghizza.github.io/SpesaLIVE/**

Non serve installare nulla: la webapp gira direttamente nel browser. I dati vengono salvati automaticamente sul dispositivo e restano lì alla chiusura della pagina.

## Installazione sul telefono (consigliata)

Installandola come app, si apre a schermo intero senza barra del browser, con un'icona sulla home screen, e funziona anche **senza connessione** dopo il primo avvio.

**iOS (Safari)** — Apri il link → tocca l'icona **Condividi** → **Aggiungi a Home**.  
**Android (Chrome)** — Apri il link → menu ⋮ → **Installa app** (o **Aggiungi a schermata Home**).

Una volta installata, l'app si apre a schermo intero senza barra del browser, come un'app nativa.

## Uso offline

Dopo la prima apertura (online), la webapp resta disponibile anche senza connessione:

- **Se installata** — apri l'icona dalla home screen: funziona normalmente offline
- **Se non installata** — il browser può mostrare una versione in cache, ma il comportamento varia; l'installazione è il modo affidabile per usarla offline

I dati restano sul dispositivo e non richiedono rete per essere letti o modificati.

## Privacy

Tutti i dati (prezzi, quantità, totale) sono salvati **solo nel `localStorage` del browser**, sul tuo dispositivo. Niente viene inviato a server esterni. Per cancellare i dati: pulsante **Svuota foglio** nell'app, oppure cancella i dati del sito dalle impostazioni del browser.

## Licenza

Fai quello che vuoi. Se ti è utile, bene così.
