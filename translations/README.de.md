# xrevive

### [**English**](../README.md) · **Deutsch** · [**Français**](README.fr.md) · [**Español**](README.es.md) · [**Italiano**](README.it.md) · [**Português (Brasil)**](README.pt-BR.md) · [**Русский**](README.ru.md) · [**العربية**](README.ar.md) · [**日本語**](README.ja.md) · [**简体中文**](README.zh-CN.md)

Ein Desktop-Launcher für Spiele der ersten Xbox, die mit [Xrecomp](https://github.com/Teraflopping/Xrecomp) neu kompiliert wurden, mit Onlinediensten vom Xbox-Live-Revival auf [xb.live](https://xb.live).

## Download v0.1.14

[Download für Windows x64](https://github.com/Teraflopping/xrevive/releases/download/v0.1.14/xrevive_0.1.14_x64-setup.exe) · [Download für Linux (AppImage)](https://github.com/Teraflopping/xrevive/releases/download/v0.1.14/xrevive_0.1.14_amd64.AppImage) · [Alle Installer und Versionshinweise](https://github.com/Teraflopping/xrevive/releases/latest)

Die bereitgestellten Spiel-Executables unterstützen derzeit **Windows x64**. Unter Linux laufen sie über Wine oder Proton (experimentell). macOS-Pakete können noch keine Spiele starten.

## Funktionen

- Füge deine eigene ISO oder deinen entpackten Spielordner hinzu und lade dann die passende Executable herunter. xrevive nutzt den Release-Build eines Spiels, wenn es einen gibt, und fragt nach, bevor ein Beta- oder Alpha-Build installiert wird. Region-free-, Media-Patch-, umbenannte oder neu signierte Dumps eines unterstützten Spiels werden ebenfalls erkannt.
- Sieh dir jedes Release-, Beta- oder Alpha-Spiel vor der Installation an: Aktivität, Updates, Bestenlisten, Erfolge, Addons und die Live-Zahl der Spieler und Lobbys, mit **INSTALL** direkt auf der Seite.
- Automatische Update-Prüfung für Spiele und Launcher. Spiel-Updates entfernen die alten Executables, die sie ersetzen, und Spiel-Downloads kommen von einem Server in deiner Nähe und laufen nach einem Verbindungsabbruch weiter.
- Melde dich mit xb.live an (zuerst online in Midnight Club 3) und sieh Freunde, Live-Lobbys, Community-Events und Bestenlisten. Ist xb.live nicht erreichbar, starten die Spiele trotzdem offline.
- Verwalte installierte Spiele: spielen, lokale Dateien durchsuchen, deinstallieren und ein DLC/Addons-Tab, in dem jeder Mod einen An/Aus-Schalter und die Credits seines Erstellers hat. **▶ PLAY** startet das Spiel mit den aktivierten Mods, und Addons funktionieren auch nach Spiel-Updates weiter.
- Spielstände-Tab mit Sicherung, Wiederherstellung, Import, PS2-Spielstandkonvertierung und Spielstand-Editoren für Midnight Club 3 und NINJA GAIDEN Black.
- Der Shader-Cache bleibt beim Spiel, sodass nur der erste Start Shader kompiliert.
- Klare Fehlermeldungen, die erklären, was schiefging und wie man es behebt, einschließlich einer Schaltfläche **Allow xrevive in Windows Security**, wenn der überwachte Ordnerzugriff eine Installation blockiert.
- Spanisch, Italienisch und Arabisch sind unter Einstellungen > Sprache verfügbar; auf Arabisch wird das ganze Fenster von rechts nach links angezeigt.
- Füge installierte Spiele zu Steam hinzu (in den Einstellungen oder der Bibliothek), mit Coverbildern und Steam Input auf dem Deck.
- Systemprüfung für Windows 8.1+ und Direct3D 11, mit der Option „Trotzdem spielen“.
- XB-Online-Spielstände aus dem alten Ordner `XBL-Hosted` werden beim Drücken von Play in den üblichen Spielstandordner jedes Spiels kopiert. Vorhandene Spielstände werden nie ersetzt und nichts wird gelöscht; sobald du deine Spielstände geprüft hast, kannst du `SaveData\XBL-Hosted` selbst löschen.

## Du bringst die Spiele mit

xrevive enthält keine Spiel-ISOs oder Spieldateien. Verwende deine eigenen Spieldateien. Diese Version lädt veröffentlichte Executables herunter, statt Spiele lokal zu kompilieren; Spiele ohne verfügbare Executable können für später entpackt werden.

Der Windows-Launcher und der Installer sind mit Authenticode signiert. Launcher-Updates sind mit dem xrevive-Update-Schlüssel signiert. macOS-Pakete sind nicht notarisiert, daher können unter macOS bei der ersten Installation Sicherheitshinweise erscheinen.

---

xrevive ist ein Fanprojekt. Es steht in keiner Verbindung zu Microsoft und wird nicht von Microsoft unterstützt.
