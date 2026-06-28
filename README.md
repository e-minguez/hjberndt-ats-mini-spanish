# Guía del firmware Mini-Radio (V4) para ATS-Mini

Guía de usuario en español del firmware personalizado para el receptor de bolsillo
**ATS-Mini** (ESP32-S3 + SI4735/SI4732): escucha de **FM · AM · SSB** y decodificación de
**RTTY · CW · SSTV · WeFax** directamente desde la antena telescópica.

> **Nota:** esta es una versión traducida y reorganizada de la guía original de H.J. Berndt:
> <http://www.hjberndt.de/dvb/pocketSI4735DualCoreDecoder.html>

## 🌐 Web

Publicada con GitHub Pages: <http://eduardominguez.es/hjberndt-ats-mini-spanish/>

## Contenido

- `index.html` — la guía completa (web estática).
- `styles.css` — estilos de la página.
- `img/` — imágenes y capturas.

## Temas que cubre

Instalación del firmware, primeros pasos, escucha de FM/AM/onda corta/SSB, sintonización
(Fast Tune, NumPad), decodificación de RTTY y CW, recepción de imágenes SSTV y mapas WeFax,
identificación de balizas IBP, gestión de archivos, personalización de la pantalla, referencia
del menú y solución de problemas.

## Uso local

Abre `index.html` en el navegador, o sirve la carpeta:

```bash
python3 -m http.server 8000
# luego abre http://localhost:8000
```

## Licencia

Guía de usuario no oficial de la comunidad, traducida y reorganizada a partir del
[original de H.J. Berndt](http://www.hjberndt.de/dvb/pocketSI4735DualCoreDecoder.html).
ATS-Mini y los chips SI4735/SI4732 pertenecen a sus respectivos fabricantes.
