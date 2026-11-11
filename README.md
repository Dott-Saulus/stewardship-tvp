# Anticoagulation stewardship in ambulatorio: dal sospetto alla prescrizione

Strumento web a scopo **formativo e organizzativo** per facilitare la gestione del sospetto di trombosi (TVP ed EP) e della trombosi venosa superficiale nel setting della Medicina Generale della Regione Veneto.

Realizzato da **Dott. Paolo Simonato** – Medico di Medicina Generale.
Versione 1.0 – 11 novembre 2026.

## Cosa fa

- Guida alla scelta dell'indicazione: sospetto TVP/EP, TVP confermata, trombosi venosa superficiale.
- Score di Wells per TVP ed EP, con categoria di rischio (probabile/improbabile) e piano diagnostico.
- Controindicazioni all'anticoagulante da escludere prima della prescrizione.
- Calcolo della dose in base al peso: enoxaparina in UI/kg (ogni 12 o 24 ore) e fondaparinux per fascia di peso, con la siringa più vicina, il numero di siringhe per la durata scelta e i limiti per funzione renale.
- Modalità di prescrizione ed erogazione (convenzionata, Distribuzione per Conto, distribuzione diretta) secondo la Regione Veneto.
- Testo pronto da copiare in ricetta e cartella clinica.

## Avvertenze

Questo strumento **non è un dispositivo medico** e non sostituisce il giudizio clinico. Dosi, indicazioni e modalità di prescrizione vanno sempre verificate sulla scheda tecnica dei farmaci e sulle disposizioni della propria azienda sanitaria. La responsabilità delle decisioni cliniche resta del medico.

I dati inseriti restano nel browser e non vengono salvati né inviati ad alcun server.

## Come si usa

- **Online:** apri l'indirizzo della pagina dal computer o dal telefono.
- **Come app sul telefono:** apri la pagina nel browser e scegli «Aggiungi alla schermata Home» (Android: «Installa app»). Dopo la prima apertura funziona anche senza connessione.
- **Senza internet:** scarica il pacchetto dalla sezione *Releases*, decomprimilo e apri `index.html`.

## Fonti

- Score di Wells per la TVP e per l'EP.
- Allegato «Aree di risparmio identificate dalla Regione Veneto per la farmaceutica convenzionata», con la Tabella 2 sulle indicazioni, la durata e le modalità di erogazione degli anticoagulanti iniettivi (ULSS 6 Euganea).
- Schede tecniche dei medicinali (enoxaparina, fondaparinux).

Le modalità di erogazione e le indicazioni regionali possono cambiare: controlla sempre la versione in vigore.

## Aggiornamenti

La versione e la data compaiono nell'intestazione della pagina. Per ogni modifica: aggiorna il testo in `index.html` e cambia il numero di versione in `sw.js` (riga `CACHE`), così chi ha installato l'app riceve la versione nuova.

## Segnalazioni

Per errori o suggerimenti apri una segnalazione nella sezione *Issues* di questo repository.

## Licenza

Contenuti e codice: Creative Commons Attribuzione – Non commerciale – Non opere derivate 4.0 (CC BY-NC-ND 4.0). Il logo è utilizzato con autorizzazione ed è escluso dalla licenza. I caratteri IBM Plex e Newsreader sono distribuiti con licenza SIL OFL 1.1 (cartella `fonts`). Dettagli in `LICENSE.md`.
