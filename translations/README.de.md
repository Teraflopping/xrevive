# xrevive

### [**English**](../README.md) · **Deutsch** · [**Français**](README.fr.md) · [**Español**](README.es.md) · [**Italiano**](README.it.md) · [**Português (Brasil)**](README.pt-BR.md) · [**Русский**](README.ru.md) · [**العربية**](README.ar.md) · [**日本語**](README.ja.md) · [**简体中文**](README.zh-CN.md)

Ein Desktop-Launcher für Spiele der ersten Xbox, die mit [Xrecomp](https://github.com/Teraflopping/Xrecomp) neu kompiliert wurden, mit Onlinediensten vom Xbox-Live-Revival auf [xb.live](https://xb.live).

## Download

[Download für Windows x64](https://github.com/Teraflopping/xrevive/releases/latest) · [Download für Linux (AppImage)](https://github.com/Teraflopping/xrevive/releases/latest) · [Alle Installer und Versionshinweise](https://github.com/Teraflopping/xrevive/releases/latest)

Die bereitgestellten Spiel-Executables unterstützen derzeit **Windows x64**. Unter Linux laufen sie über Wine oder Proton (experimentell). macOS-Pakete können noch keine Spiele starten.

## Funktionen

- Füge deine eigene ISO oder deinen entpackten Spielordner hinzu und lade dann die passende Executable herunter. xrevive nutzt den Release-Build eines Spiels, wenn es einen gibt, und fragt nach, bevor ein Beta- oder Alpha-Build installiert wird. Region-free-, Media-Patch-, umbenannte oder neu signierte Dumps eines unterstützten Spiels werden ebenfalls erkannt. Ein aus Beta oder Alpha installiertes Spiel wechselt per Update auf seinen Release-Build, sobald es einen für deine Kopie gibt.
- Sieh dir jedes Release-, Beta- oder Alpha-Spiel vor der Installation an: Aktivität, Updates, Bestenlisten, Erfolge, Addons und die Live-Zahl der Spieler und Lobbys, mit **INSTALL** direkt auf der Seite.
- Automatische Update-Prüfung für Spiele und Launcher. Spiel-Updates entfernen die alten Executables, die sie ersetzen, und Spiel-Downloads kommen von einem Server in deiner Nähe und laufen nach einem Verbindungsabbruch weiter.
- Melde dich mit xb.live an (zuerst online in Midnight Club 3), füge Freunde per Gamertag hinzu und sieh Live-Lobbys, Community-Events und XB-Online-Ankündigungen. Ist xb.live nicht erreichbar, starten die Spiele trotzdem offline.
- Verwalte installierte Spiele: spielen, lokale Dateien durchsuchen, deinstallieren und ein DLC/Addons-Tab, in dem jeder Mod einen An/Aus-Schalter und die Credits seines Erstellers hat. **▶ PLAY** startet das Spiel mit den aktivierten Mods, und Addons funktionieren auch nach Spiel-Updates weiter.
- Spielstände-Tab auf der Seite jedes Spiels mit Sicherung, Wiederherstellung, Import, **Verschieben…** in einen Ordner deiner Wahl, PS2-Spielstandkonvertierung (kein Xbox-Profil nötig) und Spielstand-Editoren für Midnight Club 3 und NINJA GAIDEN Black.
- Spielstände aus xemu lassen sich importieren, auch wenn eine andere Konsole sie signiert hat: NINJA GAIDEN Black-Spielstände und andere mit bekanntem Aufbau werden für diesen PC neu signiert und als unbestätigt aufgeführt.
- Eigene Soundtracks: Im Musik-Bereich erstellst du Soundtracks und fügst MP3-, FLAC-, Ogg-, WAV-, M4A- oder AAC-Songs hinzu, die jedes unterstützte Spiel abspielt (Midnight Club 3 ab dem Update 1.0.7).
- Title Updates von XB Online und DLCs werden automatisch installiert, während das Spiel geschlossen ist, und die Add-ons-Liste jedes Spiels zeigt sein Title Update mit einem Schalter. Online-Spiele brauchen das Title Update: Fehlt es oder ist es ausgeschaltet, fragt Play, ob du es herunterladen (oder wieder einschalten) oder diesmal offline spielen willst.
- Ein Spiel mit DLC im Store von XB Online listet ihn im DLC/Addons-Tab mit Herunterladen und Entfernen auf, und das Spiel findet ihn beim nächsten Start.
- Spieleinstellungen im Spielmenü: Vollbild, Auflösung, VSync, Seitenverhältnis, Helligkeit, Kontrast, Sättigung, Kantenglättung, FPS-Limit sowie DirectX 12, DirectX 11 oder Vulkan. Midnight Club 3 hat außerdem eine eigene Sprachliste, einschließlich der portugiesischen, russischen und arabischen Übersetzungs-Addons.
- Spielzeit für jedes Spiel, und Spiel-EXEs behalten über Updates hinweg denselben Namen, damit Profile in der NVIDIA-Systemsteuerung erhalten bleiben.
- In den Einstellungen wählst du, ob xrevive beim Schließen des Fensters im Infobereich weiterläuft oder beendet wird. Spiele, die in ihr Title Update neu starten, werden weiter als laufend angezeigt, und Spielzeit sowie Online-Sitzung bleiben erhalten.
- Einstellungen > Disc-Inspektor liest Titel, Title-ID, Version und Region eines Disc-Images aus und kopiert einen Bericht, den du direkt in einen Fehlerbericht einfügen kannst.
- Der Shader-Cache bleibt beim Spiel, sodass nur der erste Start Shader kompiliert.
- Klare Fehlermeldungen, die erklären, was schiefging und wie man es behebt, einschließlich einer Schaltfläche **Allow xrevive in Windows Security**, wenn der überwachte Ordnerzugriff eine Installation blockiert.
- Unter Einstellungen > Sprache stehen 10 Sprachen zur Wahl: Englisch, Deutsch, Französisch, Spanisch, Italienisch, brasilianisches Portugiesisch, Russisch, Arabisch, Japanisch und vereinfachtes Chinesisch. Auf Arabisch wird das ganze Fenster von rechts nach links angezeigt.
- Füge installierte Spiele zu Steam hinzu (in den Einstellungen oder der Bibliothek), mit Coverbildern und Steam Input auf dem Deck.
- Gestalte deine Spiele selbst: Klicke mit der rechten Maustaste auf ein Spiel und öffne Verwalten, um ein eigenes Banner und Symbol (PNG oder JPEG) zu wählen. Ansonsten zeigt die Spieleliste das Spielstand-Symbol jedes Spiels aus seiner default.xbe, und Zu Steam hinzufügen verwendet dieselben Bilder.
- Systemprüfung für Windows 8.1+ und Direct3D 11, mit der Option „Trotzdem spielen“.
- XB-Online-Spielstände aus dem alten Ordner `XBL-Hosted` werden beim Drücken von Play in den üblichen Spielstandordner jedes Spiels kopiert. Vorhandene Spielstände werden nie ersetzt und nichts wird gelöscht; sobald du deine Spielstände geprüft hast, kannst du `SaveData\XBL-Hosted` selbst löschen.

## Du bringst die Spiele mit

xrevive enthält keine Spiel-ISOs oder Spieldateien. Verwende deine eigenen Spieldateien. Diese Version lädt veröffentlichte Executables herunter, statt Spiele lokal zu kompilieren; Spiele ohne verfügbare Executable können für später entpackt werden.

Der Windows-Launcher und der Installer sind mit Authenticode signiert. Launcher-Updates sind mit dem xrevive-Update-Schlüssel signiert. macOS-Pakete sind nicht notarisiert, daher können unter macOS bei der ersten Installation Sicherheitshinweise erscheinen.

---

xrevive ist ein Fanprojekt. Es steht in keiner Verbindung zu Microsoft und wird nicht von Microsoft unterstützt.
