# Modelo de ASISAGRO

Este repositorio existe para una sola cosa: alojar, como publicación
(*release*), el archivo de pesos del modelo de lenguaje que la aplicación
ASISAGRO descarga en su primer inicio. El código de la aplicación vive en
otro repositorio.

ASISAGRO es el trabajo de grado de Bernardo Elías Ramírez Avendaño y Juan
David Alzate Zapata, Ingeniería en Software, Tecnológico de Antioquia, 2026:
un asistente técnico para caficultores que responde sin conexión con un
modelo de lenguaje ejecutado en el teléfono.

## Qué hay publicado

| Publicación | Archivo | Modelo | Tamaño | SHA-256 |
|---|---|---|---|---|
| `gemma3-1b-q4-ekv1280` | `modelo.task` | Gemma 3 1B IT, int4 por bloques de 32, ventana de 1280, prellenado múltiple, formato MediaPipe `.task` | 722 004 982 bytes | `ec839570e236d56eae042b56b06f7114ebab4899f539d93fd668b1a16432adab` |

La aplicación comprueba el tamaño y el resumen antes de dar el archivo por
instalado. Si este archivo cambia, la aplicación lo descarta.

## Licencia

El archivo es una compilación de Gemma publicada por Google en
`litert-community/Gemma3-1B-IT`. Gemma se entrega bajo los **Términos de
uso de Gemma** y está sujeta a la **Política de usos prohibidos de Gemma**.
Al descargarlo o usarlo se aceptan esos términos. Ver [NOTICE.md](NOTICE.md).
