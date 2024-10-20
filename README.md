# Download Music from YouTube

Questo progetto consente di scaricare audio da video e playlist di YouTube e di convertirli in file MP3. Utilizza le librerie `yt-dlp` e `ffmpeg` per gestire il download e la conversione.

## Prerequisiti

Assicurati di avere accesso a Google Colab, poiché questo codice è progettato per funzionare in quell'ambiente. Non è necessario installare `yt-dlp` e `ffmpeg` manualmente, poiché il codice li installerà automaticamente.

## Come utilizzare

1. **Apri Google Colab** e crea un nuovo notebook.
2. **Copia e incolla** il codice fornito nel notebook.
3. Esegui il codice. Ti verrà chiesto di scegliere se vuoi scaricare un video (1) o una playlist (2) di YouTube.
4. **Inserisci l'URL** del video o della playlist che desideri scaricare.
5. Il programma scaricherà l'audio e lo convertirà in formato MP3, salvandolo in una cartella denominata `download_music_py`.
6. Una volta completato il download, il programma comprimerà i file in un archivio ZIP e ti permetterà di scaricarlo.

## Funzionalità

- **Download audio**: Scarica audio da un video di YouTube o da una playlist.
- **Conversione in MP3**: I file audio vengono convertiti in formato MP3 con qualità massima (320 kbps).
- **Archiviazione**: I file scaricati vengono archiviati in una cartella e compressi in un file ZIP per un facile download.

## Requisiti

Questo codice richiede:
- Accesso a Google Colab
- Connessione a Internet per il download dei file

## Esempi di utilizzo

- Per scaricare un video, inserisci l'URL diretto del video.
- Per scaricare una playlist, inserisci l'URL della playlist di YouTube.

## Licenza

Questo progetto è distribuito sotto la licenza MIT. Consulta il file `LICENSE` per ulteriori dettagli.

## Note

- Assicurati di avere i diritti necessari per scaricare e utilizzare i contenuti da YouTube.
- Questo strumento è destinato esclusivamente a scopi educativi e personali.
