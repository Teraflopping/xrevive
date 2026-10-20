# xrevive

### [**English**](../README.md) · [**Deutsch**](README.de.md) · [**Français**](README.fr.md) · [**Español**](README.es.md) · **Italiano** · [**Português (Brasil)**](README.pt-BR.md) · [**Русский**](README.ru.md) · [**العربية**](README.ar.md) · [**日本語**](README.ja.md) · [**简体中文**](README.zh-CN.md)

Un launcher desktop per i giochi della prima Xbox ricompilati con [Xrecomp](https://github.com/Teraflopping/Xrecomp), con i servizi online del revival di Xbox Live su [xb.live](https://xb.live).

## Scarica

[Scarica per Windows x64](https://github.com/Teraflopping/xrevive/releases/latest) · [Scarica per Linux (AppImage)](https://github.com/Teraflopping/xrevive/releases/latest) · [Tutti gli installer e le note di rilascio](https://github.com/Teraflopping/xrevive/releases/latest)

Gli eseguibili dei giochi ospitati supportano attualmente **Windows x64**. Su Linux possono girare tramite Wine o Proton (sperimentale). I pacchetti per macOS non possono ancora avviare giochi.

## Funzionalità

- Aggiungi la tua ISO o la cartella del gioco estratta, poi scarica l'eseguibile corrispondente. xrevive usa la build Release di un gioco quando c'è, e chiede prima di installare una build Beta o Alpha. Vengono riconosciuti anche i dump region-free, con media patch, rinominati o rifirmati di un gioco supportato. Un gioco installato da Beta o Alpha passa alla sua build Release con un aggiornamento appena ce n'è una per la tua copia.
- Esplora qualsiasi gioco Release, Beta o Alpha prima di installarlo: attività, aggiornamenti, classifiche, obiettivi, addon e il conteggio in tempo reale di giocatori e lobby, con **INSTALL** direttamente nella sua pagina.
- Controllo automatico degli aggiornamenti di giochi e launcher. Gli aggiornamenti dei giochi rimuovono i vecchi eseguibili che sostituiscono, e i download dei giochi arrivano da un server vicino a te e riprendono se la connessione cade.
- Accedi con xb.live (a partire dall'online di Midnight Club 3), aggiungi amici tramite gamertag e vedi lobby in tempo reale, eventi della community e annunci di XB Online. Se xb.live non è raggiungibile, i giochi si avviano comunque offline.
- Gestisci i giochi installati: gioca, sfoglia i file locali, disinstalla e usa la scheda DLC/Addons, dove ogni mod ha un interruttore On/Off e i crediti del suo autore. **▶ PLAY** avvia il gioco con le mod attive, e gli addon continuano a funzionare dopo gli aggiornamenti del gioco.
- Scheda Salvataggi nella pagina di ogni gioco con backup, ripristino, importazione, **Sposta…** in una cartella a tua scelta, conversione dei salvataggi PS2 (senza profilo Xbox) ed editor dei salvataggi per Midnight Club 3 e NINJA GAIDEN Black.
- I salvataggi importati da xemu funzionano anche se li ha firmati un'altra console: quelli di NINJA GAIDEN Black e altri con un formato noto vengono rifirmati per questo PC ed elencati come non verificati.
- Colonne sonore personalizzate: una schermata Musica per creare colonne sonore e aggiungere brani MP3, FLAC, Ogg, WAV, M4A o AAC che ogni gioco supportato riproduce (Midnight Club 3 dall'aggiornamento 1.0.7).
- Gli aggiornamenti del titolo da XB Online e i DLC si installano automaticamente mentre il gioco è chiuso, e l'elenco Add-on di ogni gioco mostra il suo aggiornamento del titolo con un interruttore. Il gioco online richiede l'aggiornamento del titolo: se manca o è disattivato, Play chiede se scaricarlo (o riattivarlo) o giocare offline questa volta.
- Un gioco con DLC nello store di XB Online li elenca nella scheda DLC/Addons con Scarica e Rimuovi, e il gioco li trova al prossimo avvio.
- Impostazioni per gioco dal menu del gioco: schermo intero, risoluzione, VSync, proporzioni, luminosità, contrasto, saturazione, anti-aliasing, limite FPS e DirectX 12, DirectX 11 o Vulkan. Midnight Club 3 ha anche un proprio elenco di lingue, inclusi gli addon di traduzione in portoghese, russo e arabo.
- Tempo di gioco per ogni gioco, ed EXE dei giochi che mantengono lo stesso nome tra un aggiornamento e l'altro, così i profili del Pannello di controllo NVIDIA restano applicati.
- Nelle Impostazioni scegli se chiudere la finestra lascia xrevive nell'area di notifica o lo chiude. I giochi che si riavviano nel loro aggiornamento del titolo restano mostrati come in gioco, con tempo di gioco e sessione online mantenuti.
- Impostazioni > Ispettore disco legge titolo, ID titolo, versione e regione di un'immagine disco e copia un report pronto da incollare in una segnalazione di bug.
- La cache degli shader resta con il gioco, quindi solo il primo avvio compila gli shader.
- Messaggi di errore chiari che spiegano cosa è andato storto e come risolverlo, incluso un pulsante **Allow xrevive in Windows Security** quando l'Accesso controllato alle cartelle blocca un'installazione.
- 10 lingue a scelta in Impostazioni > Lingua: inglese, tedesco, francese, spagnolo, italiano, portoghese brasiliano, russo, arabo, giapponese e cinese semplificato. In arabo l'intera finestra viene mostrata da destra a sinistra.
- Aggiungi i giochi installati a Steam (dalle Impostazioni o dalla libreria), con copertine e Steam Input sul Deck.
- Personalizza i tuoi giochi: fai clic destro su un gioco e apri Gestisci per scegliere banner e icona tuoi (PNG o JPEG). Altrimenti l'elenco dei giochi mostra l'icona di salvataggio di ogni gioco presa dal suo default.xbe, e Aggiungi a Steam usa le stesse immagini.
- Controllo del sistema per Windows 8.1+ e Direct3D 11, con l'opzione Gioca comunque.
- I salvataggi XB Online della vecchia cartella `XBL-Hosted` vengono copiati nella normale cartella dei salvataggi di ogni gioco quando premi Play. I salvataggi esistenti non vengono mai sostituiti e non viene cancellato nulla; dopo aver controllato i tuoi salvataggi, puoi eliminare tu stesso `SaveData\XBL-Hosted`.

## I giochi li porti tu

xrevive non include ISO né file dei giochi. Usa i tuoi file di gioco. Questa versione scarica eseguibili pubblicati invece di compilare i giochi in locale; i giochi senza un eseguibile disponibile possono essere estratti per usarli in seguito.

Il launcher e l'installer per Windows sono firmati Authenticode. Gli aggiornamenti del launcher sono firmati con la chiave di aggiornamento di xrevive. I pacchetti per macOS non sono notarizzati, quindi alla prima installazione su macOS possono comparire avvisi di sicurezza.

---

xrevive è un progetto di fan. Non è affiliato né approvato da Microsoft.
