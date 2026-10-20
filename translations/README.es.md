# xrevive

### [**English**](../README.md) · [**Deutsch**](README.de.md) · [**Français**](README.fr.md) · **Español** · [**Italiano**](README.it.md) · [**Português (Brasil)**](README.pt-BR.md) · [**Русский**](README.ru.md) · [**العربية**](README.ar.md) · [**日本語**](README.ja.md) · [**简体中文**](README.zh-CN.md)

Un launcher de escritorio para juegos del Xbox original recompilados con [Xrecomp](https://github.com/Teraflopping/Xrecomp), con servicios en línea del revival de Xbox Live en [xb.live](https://xb.live).

## Descargar

[Descargar para Windows x64](https://github.com/Teraflopping/xrevive/releases/latest) · [Descargar para Linux (AppImage)](https://github.com/Teraflopping/xrevive/releases/latest) · [Todos los instaladores y notas de versión](https://github.com/Teraflopping/xrevive/releases/latest)

Los ejecutables de los juegos alojados actualmente son compatibles con **Windows x64**. En Linux pueden ejecutarse con Wine o Proton (experimental). Los paquetes para macOS todavía no pueden ejecutar juegos.

## Funciones

- Agrega tu propia ISO o carpeta del juego extraída y descarga el ejecutable correspondiente. xrevive usa la versión Release del juego cuando existe y pregunta antes de instalar una versión Beta o Alpha. También reconoce dumps region-free, con media patch, renombrados o refirmados de un juego compatible. Un juego instalado desde Beta o Alpha pasa a su versión Release con una actualización en cuanto haya una para tu copia.
- Explora cualquier juego Release, Beta o Alpha antes de instalarlo: actividad, actualizaciones, clasificaciones, logros, addons y el conteo en vivo de jugadores y lobbies, con el botón **INSTALL** en su propia página.
- Búsqueda automática de actualizaciones de juegos y del launcher. Las actualizaciones de juegos eliminan los ejecutables antiguos que reemplazan, y las descargas vienen de un servidor cercano a ti y se reanudan si se corta la conexión.
- Inicia sesión con xb.live (empezando por el modo en línea de Midnight Club 3), agrega amigos por gamertag y ve lobbies en vivo, eventos de la comunidad y anuncios de XB Online. Si xb.live no está disponible, los juegos igual inician sin conexión.
- Administra los juegos instalados: jugar, abrir los archivos locales, desinstalar y la pestaña DLC/Addons, donde cada mod tiene un interruptor On/Off y los créditos de su creador. **▶ PLAY** inicia el juego con los mods activados, y los addons siguen funcionando después de actualizar el juego.
- Pestaña Saves en la página de cada juego con respaldo, restauración, importación, **Mover…** a la carpeta que elijas, conversión de partidas de PS2 (sin necesidad de perfil de Xbox) y editores de partidas para Midnight Club 3 y NINJA GAIDEN Black.
- Las partidas importadas desde xemu funcionan aunque las haya firmado otra consola: las de NINJA GAIDEN Black y otras con formato conocido se vuelven a firmar para este PC y aparecen como no verificadas.
- Bandas sonoras personalizadas: una pantalla de Música para crear bandas sonoras y agregar canciones MP3, FLAC, Ogg, WAV, M4A o AAC que todos los juegos compatibles reproducen (Midnight Club 3 desde su actualización 1.0.7).
- Las actualizaciones de título de XB Online y los DLC se instalan automáticamente mientras el juego está cerrado, y la lista de Add-ons de cada juego muestra su actualización de título con un interruptor. El juego en línea necesita la actualización de título: si falta o está desactivada, Play pregunta si quieres descargarla (o volver a activarla) o jugar sin conexión esta vez.
- Un juego con DLC en la tienda de XB Online lo muestra en su pestaña DLC/Addons con Descargar y Quitar, y el juego lo encuentra la próxima vez que se inicia.
- Ajustes por juego desde el menú del juego: pantalla completa, resolución, VSync, relación de aspecto, brillo, contraste, saturación, antialiasing, límite de FPS, y DirectX 12, DirectX 11 o Vulkan. Midnight Club 3 también tiene su propia lista de idiomas, incluidos los addons de traducción al portugués, ruso y árabe.
- Tiempo de juego de cada juego, y EXE de juegos que mantienen el mismo nombre entre actualizaciones para que los perfiles del Panel de control de NVIDIA sigan aplicados.
- En Configuración eliges si cerrar la ventana deja xrevive en la bandeja o lo cierra. Los juegos que se reinician en su actualización de título siguen apareciendo en juego, con el tiempo de juego y la sesión online intactos.
- Configuración > Inspector de disco lee el título, el ID de título, la versión y la región de una imagen de disco y copia un informe listo para pegar en un reporte de errores.
- La caché de shaders se queda con el juego, así que solo el primer inicio compila los shaders.
- Mensajes de error claros que explican qué salió mal y cómo solucionarlo, incluido un botón **Allow xrevive in Windows Security** cuando el Acceso controlado a carpetas bloquea una instalación.
- Elige entre 10 idiomas en Configuración > Idioma: inglés, alemán, francés, español, italiano, portugués de Brasil, ruso, árabe, japonés y chino simplificado. En árabe toda la ventana se muestra de derecha a izquierda.
- Agrega juegos instalados a Steam (Configuración o biblioteca), con portadas y Steam Input en el Deck.
- Personaliza tus juegos: haz clic derecho en un juego y abre Administrar para elegir tu propio banner e icono (PNG o JPEG). Si no, la lista de juegos muestra el icono de partida de cada juego, tomado de su default.xbe, y Agregar a Steam usa el mismo arte.
- Verificación del sistema para Windows 8.1+ y Direct3D 11, con la opción de Jugar de todos modos.
- Las partidas de XB Online de la antigua carpeta `XBL-Hosted` se copian a la carpeta de partidas habitual de cada juego cuando presionas Play. Las partidas existentes nunca se reemplazan y no se borra nada; después de revisar tus partidas, puedes borrar `SaveData\XBL-Hosted` tú mismo.

## Tú pones los juegos

xrevive no incluye ISOs ni archivos de los juegos. Usa tus propios archivos. Esta versión descarga ejecutables publicados en lugar de compilar los juegos localmente; los juegos sin ejecutable disponible pueden extraerse para usarlos más adelante.

El launcher y el instalador para Windows tienen firma Authenticode. Las actualizaciones del launcher se firman con la clave de actualización de xrevive. Los paquetes para macOS no están notarizados, así que pueden aparecer avisos de seguridad en la primera instalación en macOS.

---

xrevive es un proyecto de fans, sin afiliación ni respaldo de Microsoft.
