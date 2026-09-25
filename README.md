<p align="center">
  <img src="assets/banner/noah-castellano.png" alt="CHAOS;HEAD NOAH — Traducción al español" width="760">
</p>

# CHAOS;HEAD NOAH — Traducción al español

<p align="center">
  <img alt="Versión: v1.1.0" src="https://img.shields.io/badge/versión-v1.1.0-blue?style=flat-square">
  <img alt="Plataforma: Windows" src="https://img.shields.io/badge/plataforma-Windows-0078D6?style=flat-square">
  <img alt="Edición: Steam" src="https://img.shields.io/badge/edición-Steam-1b2838?style=flat-square">
  <img alt="Committee of Zero: 1.1.3" src="https://img.shields.io/badge/CoZ-1.1.3-6f42c1?style=flat-square">
</p>

<p align="center">
  <a href="https://github.com/rubocopter/chaos-head-noah-es/releases/tag/v1.1.0"><strong>Descargar v1.1.0</strong></a>
  ·
  <a href="https://github.com/rubocopter/chaos-head-noah-es/issues/new/choose">Informar de un problema</a>
  ·
  <a href="CHANGELOG.md">Historial de cambios</a>
</p>

<p align="center">
  <a href="https://ko-fi.com/onitaku"><img alt="Support me on Ko-fi" src="https://ko-fi.com/img/githubbutton_sm.svg"></a>
</p>

Traducción completa al castellano de **CHAOS;HEAD NOAH** para Steam, revisada editorialmente y preparada para jugar sobre **CHAOS;HEAD NOAH Overhaul Patch 1.1.3** de Committee of Zero.

La versión `v1.1.0` incluye la traducción narrativa completa y añade también **nueve recursos gráficos de interfaz en español**: configuración, biblioteca, música, accesos rápidos, TIPS, álbum, miniaturas del álbum y backlog.

## Instalación rápida

Necesitas:

- una copia legítima de **CHAOS;HEAD NOAH para Steam**;
- **Windows de 64 bits**;
- **CHAOS;HEAD NOAH Overhaul Patch 1.1.3** de Committee of Zero instalado previamente.

Puedes descargar CoZ desde su [página oficial](https://sonome.dareno.me/projects/chn-patch.html) o desde sus [releases en GitHub](https://github.com/CommitteeOfZero/chn-patch/releases).

Después:

1. Descarga `CHAOS-HEAD-NOAH-ES-Setup.exe` desde la [release v1.1.0](https://github.com/rubocopter/chaos-head-noah-es/releases/tag/v1.1.0).
2. Ejecuta el instalador.
3. Comprueba que detecta correctamente el juego y Committee of Zero.
4. Pulsa **Instalar** y espera a que finalice la verificación.

El instalador detecta automáticamente la carpeta de Steam. También permite actualizar directamente desde la traducción española `v1.0.0`.

> La instalación de `v1.1.0` puede tardar algo más porque debe reconstruir, respaldar y verificar uno de los archivos de recursos de CoZ, de aproximadamente 2,26 GB. Espera a que el instalador termine antes de abrir el juego.

El instalador **no inicia el juego ni el launcher de CoZ al finalizar**. Puedes configurar CoZ como prefieras antes o después de instalar la traducción.

## Qué incluye

El texto completo se revisó teniendo en cuenta el contexto de cada escena, las voces de los personajes, la terminología y el registro. También se validaron la estructura de los guiones, las cursivas, los hablantes y los caracteres necesarios para mostrar correctamente el español.

`v1.1.0` conserva íntegra la traducción narrativa publicada en `v1.0.0` y amplía la localización a elementos gráficos visibles de la interfaz.

## Capturas de la interfaz

<p align="center"><img src="assets/screenshots/tips-v1.1.0.jpg" alt="Lista de TIPS con rótulos de interfaz en español" width="700"></p>

<p align="center"><img src="assets/screenshots/biblioteca-v1.1.0.jpg" alt="Biblioteca de CG, sonido, vídeo y lista de TIPS en español" width="700"></p>

<p align="center"><img src="assets/screenshots/configuracion-v1.1.0.jpg" alt="Configuración de teclas con rótulos en español" width="700"></p>

## Capturas de la traducción

<p align="center"><img src="assets/screenshots/instalador.png" alt="Instalador de la traducción, con juego y parche compatibles detectados" width="700"></p>

<p align="center"><img src="assets/screenshots/grimm-neidhardt.jpg" alt="Conversación de Grimm y Neidhardt en español" width="700"></p>

<p align="center"><img src="assets/screenshots/a-duras-penas.jpg" alt="Escena narrativa: A duras penas logré encontrar algo a lo que agarrarme" width="700"></p>

<p align="center"><img src="assets/screenshots/mystery-girl.jpg" alt="Escena de la fotografía de mystery girl" width="700"></p>

## Restaurar los archivos originales

Abre de nuevo el instalador y pulsa **Restaurar original**. El instalador recuperará los archivos compatibles guardados antes de aplicar la traducción y verificará el resultado.

## Compatibilidad y problemas

Esta versión está preparada exclusivamente para **CHAOS;HEAD NOAH de Steam + Committee of Zero Overhaul Patch 1.1.3**. Si el instalador detecta otra versión o una base modificada, se detendrá sin sobrescribirla.

Si encuentras un problema, abre un [Issue](https://github.com/rubocopter/chaos-head-noah-es/issues/new/choose):

- **Instalación:** indica el mensaje mostrado por el instalador y adjunta una captura.
- **Traducción:** adjunta una captura e indica la escena o el contexto.
- **Compatibilidad:** especifica tu edición del juego y la versión de Committee of Zero.

No compartas archivos del juego ni del parche y evita publicar rutas que contengan datos personales.

<details>
<summary><strong>Detalles técnicos y compatibilidad exacta</strong></summary>

El instalador valida una instalación compatible de Committee of Zero 1.1.3 (`intVersion: 8`) mediante los archivos y hashes esperados antes de modificar nada.

La traducción narrativa se aplica sobre `c0mes01.cpk`. Los nueve recursos gráficos de `v1.1.0` se sirven mediante `languagebarrier/c0data.cpk`. Los CPK originales `system_eng.cpk` y `manual_eng.cpk` no se modifican.

La distribución utiliza deltas reconstruidos únicamente sobre una base compatible verificada. No incluye ni redistribuye CPK originales completos del juego o de Committee of Zero.

Al actualizar desde `v1.0.0`, el instalador conserva su copia de seguridad histórica y añade el estado necesario para poder restaurar también los recursos incorporados en `v1.1.0`.

</details>

## Créditos y aviso

- **CHAOS;HEAD NOAH:** MAGES. / Spike Chunsoft y sus titulares correspondientes.
- **CHAOS;HEAD NOAH Overhaul Patch:** Committee of Zero.
- **Traducción al español:** onitaku — proyecto `chaos-head-noah-es`.

Proyecto fan no oficial. No está afiliado ni respaldado por MAGES., Spike Chunsoft ni Committee of Zero. Se requiere una copia legítima del juego. Los nombres, marcas, imágenes y contenidos de CHAOS;HEAD NOAH y del parche pertenecen a sus respectivos titulares; su inclusión aquí sirve únicamente para identificar y mostrar el proyecto. Este repositorio no concede derechos sobre esos materiales.

## Descargas

El instalador, `SHA256SUMS.txt` y el aviso de licencias de terceros están disponibles en [GitHub Releases](https://github.com/rubocopter/chaos-head-noah-es/releases). Los ejecutables y demás binarios se publican en Releases, no en el historial del repositorio.
