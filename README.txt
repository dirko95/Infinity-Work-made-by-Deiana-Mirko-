Rapportino Fibra – WebApp (HTML)
================================

Come usarla
1) Apri index.html da smartphone (consigliato: Chrome su Android / Safari su iPhone).
2) Compila i dati generali e aggiungi una o più attività.
3) Usa:
   - Salva PDF (genera un PDF professionale)
   - Salva immagine (genera un PNG del rapportino)
   - Condividi (prova a condividere direttamente come allegato su WhatsApp/Email)

Note importanti (smartphone)
- "Salvare come immagine nella galleria": i browser non possono scrivere direttamente nella galleria.
  La webapp scarica un file PNG; poi puoi scegliere “Salva immagine”/“Salva su Foto” dal sistema
  oppure usare il tasto Condividi.
- Condivisione con allegati: dipende dal supporto del browser (Web Share API con files).
  Se non supportato, verrà proposta una condivisione solo testuale (link/mailto/wa.me).

Dipendenze
Per export PDF/immagine la webapp usa:
- html2canvas
- jsPDF

In questa versione vengono caricate via CDN (serve connessione almeno al primo uso).
Se vuoi una versione 100% OFFLINE (librerie incluse nella cartella), dimmelo e la impacchetto.
