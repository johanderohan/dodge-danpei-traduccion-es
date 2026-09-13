# Dodge Danpei — Traducción al castellano

Traducción al **español de España** de *Honoo no Toukyuuji — Dodge Danpei* para **Mega Drive**, realizada a partir del japonés de la ROM.

**Descarga: [v0.1-dev — Parche y documentación](https://github.com/johanderohan/dodge-danpei-traduccion-es/releases/tag/v0.1-dev).**

Se distribuye como parche IPS. Necesitas tu propia copia del juego; la descarga no incluye una ROM.

## Estado

**Versión de desarrollo.** Se han traducido los 122 segmentos de diálogo identificados, compuestos en 137 páginas, y se han adaptado menús, tutoriales, nombres de jugadores, narración, títulos de ronda, créditos y numerosos rótulos gráficos.

| Parte | Trabajo incluido |
|---|---|
| Diálogos | 68 registros, 122 segmentos; 137 páginas comprobadas carácter a carácter en la memoria de vídeo del emulador. |
| Narración y nombres | 19 rótulos narrativos, 23 etiquetas de hablante y 175 registros de jugador. |
| Interfaz | Opciones, selección, posiciones, fichas, versus y liga; avisos del entrenamiento y del partido. |
| Gráficos | 15 títulos de ronda, créditos y FIN, inicio y celebración de liga, rótulos de título y demostración. |
| Castellano | Minúsculas, tildes, diéresis, ñ, ¡ y ¿; biblia de términos y abreviaturas. |

Se han probado el arranque, el acceso al primer partido, el acceso al entrenamiento y una liga de dos equipos de la CPU resuelta mediante el resultado automático. Los diálogos, capítulos y créditos también se han comprobado mediante selección de escenas.

**Falta una partida completa**, la comprobación de guardado y continuación, las variantes restantes de modos y una segunda revisión lingüística de los nombres provisionales. No se ha probado en Steam Deck ni en consola física. Las pruebas parciales no acreditan el cien por cien del juego.

Se conservan el logotipo japonés, las marcas y atribuciones originales, las banderas y las siglas gráficas de equipos y jugadores.

## Descarga e instalación

En **[Releases](https://github.com/johanderohan/dodge-danpei-traduccion-es/releases)** encontrarás:

- `dodge_danpei_es_0.1-dev.ips`: parche independiente.
- `dodge_danpei_es_0.1-dev.zip`: el mismo parche, aplicador con verificación, biblia de traducción, informe de calidad y notas técnicas.

La base debe ser la ROM **japonesa original de 524.288 bytes**, sin parches previos ni cabecera adicional.

| Archivo | SHA-256 |
|---|---|
| Original japonés | `0d476b9f1c7245d408a2c1a6d22bc0f37e7fe3be9850b7d9c9fac5b18f616511` |
| ROM resultante, 1.048.576 bytes | `c174d9d2f30a7c5888e7173a07f0d0a2d202e6100fd2e3886c81508ab2c6fe74` |
| Parche IPS | `5adf99e159ab9288303629acd4d0b1261d52ada8c1e96e765acbda619acb9606` |

Descomprime el ZIP y aplica el parche con Python 3:

```sh
python3 aplicar_parche.py "original.md" "dodge_danpei_es_0.1-dev.ips" "Dodge Danpei (Castellano).md"
```

El aplicador comprueba las huellas y crea un archivo nuevo. También puedes usar un aplicador IPS compatible con ampliación de ROM, comprobando después la huella de salida. Inicia las pruebas con una partida nueva: un estado instantáneo de otra versión no acredita el funcionamiento de esta.

## Documentación y errores

La biblia incluida en el ZIP fija las voces, los términos deportivos, los nombres, las abreviaturas y los criterios de composición. El informe de calidad detalla qué se ha comprobado y qué sigue pendiente.

Para comunicar un error, abre una incidencia con la versión del parche, el emulador, el modo y la pantalla o frase afectada. No adjuntes la ROM.

Traducción no oficial, sin vinculación con los titulares del juego. Se conservan sus créditos. Este repositorio contiene únicamente el README; los archivos descargables están en Releases.
