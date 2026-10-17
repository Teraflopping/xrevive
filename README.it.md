# xrevive

### [**English**](README.md) · [**Deutsch**](README.de.md) · [**Français**](README.fr.md) · [**Español**](README.es.md) · **Italiano** · [**Português (Brasil)**](README.pt-BR.md) · [**Русский**](README.ru.md) · [**العربية**](README.ar.md) · [**日本語**](README.ja.md) · [**简体中文**](README.zh-CN.md)

Un launcher desktop per i giochi della prima Xbox ricompilati con [Xrecomp](https://github.com/Teraflopping/Xrecomp), con i servizi online del revival di Xbox Live su [xb.live](https://xb.live).

## Scarica la v0.1.14

[Scarica per Windows x64](https://github.com/Teraflopping/xrevive/releases/download/v0.1.14/xrevive_0.1.14_x64-setup.exe) · [Scarica per Linux (AppImage)](https://github.com/Teraflopping/xrevive/releases/download/v0.1.14/xrevive_0.1.14_amd64.AppImage) · [Tutti gli installer e le note di rilascio](https://github.com/Teraflopping/xrevive/releases/latest)

Gli eseguibili dei giochi ospitati supportano attualmente **Windows x64**. Su Linux possono girare tramite Wine o Proton (sperimentale). I pacchetti per macOS non possono ancora avviare giochi.

## Funzionalità

- Aggiungi la tua ISO o la cartella del gioco estratta, poi scarica l'eseguibile corrispondente. xrevive usa la build Release di un gioco quando c'è, e chiede prima di installare una build Beta o Alpha. Vengono riconosciuti anche i dump region-free, con media patch, rinominati o rifirmati di un gioco supportato.
- Esplora qualsiasi gioco Release, Beta o Alpha prima di installarlo: attività, aggiornamenti, classifiche, obiettivi, addon e il conteggio in tempo reale di giocatori e lobby, con **INSTALL** direttamente nella sua pagina.
- Controllo automatico degli aggiornamenti di giochi e launcher. Gli aggiornamenti dei giochi rimuovono i vecchi eseguibili che sostituiscono, e i download dei giochi arrivano da un server vicino a te e riprendono se la connessione cade.
- Accedi con xb.live (a partire dall'online di Midnight Club 3) e vedi amici, lobby in tempo reale, eventi della community e classifiche. Se xb.live non è raggiungibile, i giochi si avviano comunque offline.
- Gestisci i giochi installati: gioca, sfoglia i file locali, disinstalla e usa la scheda DLC/Addons, dove ogni mod ha un interruttore On/Off e i crediti del suo autore. **▶ PLAY** avvia il gioco con le mod attive, e gli addon continuano a funzionare dopo gli aggiornamenti del gioco.
- Scheda Salvataggi con backup, ripristino, importazione, conversione dei salvataggi PS2 ed editor dei salvataggi per Midnight Club 3 e NINJA GAIDEN Black.
- La cache degli shader resta con il gioco, quindi solo il primo avvio compila gli shader.
- Messaggi di errore chiari che spiegano cosa è andato storto e come risolverlo, incluso un pulsante **Allow xrevive in Windows Security** quando l'Accesso controllato alle cartelle blocca un'installazione.
- Spagnolo, italiano e arabo sono disponibili in Impostazioni > Lingua; in arabo l'intera finestra viene mostrata da destra a sinistra.
- Aggiungi i giochi installati a Steam (dalle Impostazioni o dalla libreria), con copertine e Steam Input sul Deck.
- Controllo del sistema per Windows 8.1+ e Direct3D 11, con l'opzione Gioca comunque.
- I salvataggi XB Online della vecchia cartella `XBL-Hosted` vengono copiati nella normale cartella dei salvataggi di ogni gioco quando premi Play. I salvataggi esistenti non vengono mai sostituiti e non viene cancellato nulla; dopo aver controllato i tuoi salvataggi, puoi eliminare tu stesso `SaveData\XBL-Hosted`.

## I giochi li porti tu

xrevive non include ISO né file dei giochi. Usa i tuoi file di gioco. Questa versione scarica eseguibili pubblicati invece di compilare i giochi in locale; i giochi senza un eseguibile disponibile possono essere estratti per usarli in seguito.

Il launcher e l'installer per Windows sono firmati Authenticode. Gli aggiornamenti del launcher sono firmati con la chiave di aggiornamento di xrevive. I pacchetti per macOS non sono notarizzati, quindi alla prima installazione su macOS possono comparire avvisi di sicurezza.

---

xrevive è un progetto di fan. Non è affiliato né approvato da Microsoft.
