# Versión 2.1

## Cambios

En esta versión arreglamos la estabilidad del addon de `Deportes`.

## 2.1

- Actualización para que funcione la aplicación de Deportes con la instalación de un acestream(Streaming de los canales de Deportes) no oficial.

## 2.1.1

- Añadida notificación al pulsar sobre `Pelis y Series` y `Canal+`.

## 2.1.2

- Actualización de Acestream al pulsar en `Actualizar Canales` mediante un script que descarga y ejecuta un archivo alojado en Dropbox. Esto en principio reemplaza el funcionamiento anterior que usaba Plexus para streaming con Acestream.

## 2.1.3

- Arreglado acceso a Google Drive para que al entrar por `Imágenes` sólo se visualicen imágenes, al entrar por `Música` sólo aparezcan archivos de audio y al entrar por `Vídeos` sólo aparezcan archivos de video (antes, se entrara por donde se entrase, se accedía a archivos de video únicamente).
 
## 2.1.4

- Arreglado acceso a `Catoal` que daba error.
- Eliminado `Cairo Dock` de Raspbian ya que hacía que no se vieran bien los iconos del escritorio.
- Añadido en el nombre del dispositivo en `Kodi` la versión de `medTV` (en `WiFi/Bluetooth`).
- Añadido soporte para archivos con extensión `.mkv` en el addon `gdrive` (Google Drive).
- Asignada la tecla `v` del teclado para ir a la pantalla de reproducción de video.
- Arreglado el script de `Actualizar canales` de `Acestream` ya que no descomprimía bien el archivo descargado de Dropbox y el tiempo de espera para descargar era demasiado corto y se ha prolongado a 1 minuto.

- Montado desde cero con nueva distribución de memoria (6GB asignados a `Retropie`, a `Raspbian` lo mismo de antes y el resto a `OpenElec`).
- Eliminado acceso a `Retropie` tanto en `Kodi` como en `Raspbian`.
- Añadido acceso a la agenda de Arenavision de `Catoal` en el submenú de `Deportes`.
- Arreglado acceso directo a `YouTube` en el menú principal.
- Eliminado acceso a la agenda de Arenavision de `Catoal` en el submenú de `Deportes` ya que dejó de funcionar.

## 2.1.5

- Últimos cambios de la versión 2.1.4, para tener todo controlado en una única versión.
- Eliminada opción `Perfiles` del submenú de `Configuración` que por alguna razón seguía ahí.
- Asignada tecla `V` para ir a la pantalla de reproducción de video, que por alguna razón no lo estaba.
- Añadido de nuevo acceso a Retropie *(sólo en versión no comercial)*.
