# xrevive

[English](README.md) · [Português](README.pt-BR.md) · **Español** · [中文](README.zh-CN.md)

Un launcher de escritorio para juegos del Xbox original recompilados con [Xrecomp](https://github.com/Teraflopping/Xrecomp), con servicios en línea del revival de Xbox Live en [xb.live](https://xb.live).

## Descargar v0.1.14

[Descargar para Windows x64](https://github.com/Teraflopping/xrevive/releases/download/v0.1.14/xrevive_0.1.14_x64-setup.exe) · [Descargar para Linux (AppImage)](https://github.com/Teraflopping/xrevive/releases/download/v0.1.14/xrevive_0.1.14_amd64.AppImage) · [Todos los instaladores y notas de versión](https://github.com/Teraflopping/xrevive/releases/latest)

Los ejecutables de los juegos alojados actualmente son compatibles con **Windows x64**. En Linux pueden ejecutarse con Wine o Proton (experimental). Los paquetes para macOS todavía no pueden ejecutar juegos.

## Funciones

- Agrega tu propia ISO o carpeta del juego extraída y descarga el ejecutable correspondiente. xrevive usa la versión Release del juego cuando existe y pregunta antes de instalar una versión Beta o Alpha. También reconoce dumps region-free, con media patch, renombrados o refirmados de un juego compatible.
- Explora cualquier juego Release, Beta o Alpha antes de instalarlo: actividad, actualizaciones, clasificaciones, logros, addons y el conteo en vivo de jugadores y lobbies, con el botón **INSTALL** en su propia página.
- Búsqueda automática de actualizaciones de juegos y del launcher. Las actualizaciones de juegos eliminan los ejecutables antiguos que reemplazan, y las descargas vienen de un servidor cercano a ti y se reanudan si se corta la conexión.
- Inicia sesión con xb.live (empezando por el modo en línea de Midnight Club 3) y ve amigos, lobbies en vivo, eventos de la comunidad y clasificaciones. Si xb.live no está disponible, los juegos igual inician sin conexión.
- Administra los juegos instalados: jugar, abrir los archivos locales, desinstalar y la pestaña DLC/Addons, donde cada mod tiene un interruptor On/Off y los créditos de su creador. **▶ PLAY** inicia el juego con los mods activados, y los addons siguen funcionando después de actualizar el juego.
- Pestaña Saves con respaldo, restauración, importación, conversión de partidas de PS2 y editores de partidas para Midnight Club 3 y NINJA GAIDEN Black.
- La caché de shaders se queda con el juego, así que solo el primer inicio compila los shaders.
- Mensajes de error claros que explican qué salió mal y cómo solucionarlo, incluido un botón **Allow xrevive in Windows Security** cuando el Acceso controlado a carpetas bloquea una instalación.
- Español, italiano y árabe disponibles en Configuración > Idioma; en árabe toda la ventana se muestra de derecha a izquierda.
- Agrega juegos instalados a Steam (Configuración o biblioteca), con portadas y Steam Input en el Deck.
- Verificación del sistema para Windows 8.1+ y Direct3D 11, con la opción de Jugar de todos modos.
- Las partidas de XB Online de la antigua carpeta `XBL-Hosted` se copian a la carpeta de partidas habitual de cada juego cuando presionas Play. Las partidas existentes nunca se reemplazan y no se borra nada; después de revisar tus partidas, puedes borrar `SaveData\XBL-Hosted` tú mismo.

## Tú pones los juegos

xrevive no incluye ISOs ni archivos de los juegos. Usa tus propios archivos. Esta versión descarga ejecutables publicados en lugar de compilar los juegos localmente; los juegos sin ejecutable disponible pueden extraerse para usarlos más adelante.

El launcher y el instalador para Windows tienen firma Authenticode. Las actualizaciones del launcher se firman con la clave de actualización de xrevive. Los paquetes para macOS no están notarizados, así que pueden aparecer avisos de seguridad en la primera instalación en macOS.

---

xrevive es un proyecto de fans, sin afiliación ni respaldo de Microsoft.
