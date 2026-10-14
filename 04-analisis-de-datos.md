# Prompt: automatizar el análisis de datos

Datimpacto · www.datimpacto.com · Pieza 04

**Propósito:** cruzar una base consolidada de encuestas y entrevistas, proponer hallazgos en lenguaje simple y dejar cada cifra con su origen, para que una persona la verifique.
**Cuándo usarla:** cuando ya recogiste datos con los instrumentos de la Pieza 03 y quieres pasar de una base a una lectura.
**Tiempo:** 15 minutos para correr el prompt, 45 a 60 para verificar.

## Qué necesitas

- Una base consolidada de encuestas, con una fila por persona y un código en lugar del nombre.
- Transcripciones de entrevistas, con los nombres reemplazados por códigos.
- Los indicadores que quieres calcular (Pieza 02).
- La cifra de personas invitadas a responder, para calcular la tasa de respuesta.

## Antes de pegar: verificación de anonimización

Esta pieza admite una base a nivel individual solo si no identifica a nadie. Revisa antes de subirla:

- [ ] No hay nombres, apellidos, documentos, correos, teléfonos ni direcciones.
- [ ] Los códigos de persona no se pueden revertir sin una lista que queda fuera de la herramienta.
- [ ] Las respuestas abiertas y las transcripciones no mencionan nombres de personas, empresas pequeñas o lugares que permitan identificarlas.
- [ ] Cada columna de la base responde a un indicador. Si no, se elimina antes de subirla.
- [ ] Tu organización aprobó el asistente que vas a usar para documentos internos.

El prompt vuelve a revisar esto en su paso 0 y se detiene si encuentra identificadores.

## El prompt

```
Eres un analista junior de datos para una organización social. Cruzas datos y
propones lecturas. Una persona verifica y decide. No tienes acceso a nada
fuera de lo que te pego.

Base de encuestas (tabla o CSV adjunto):
[ADJUNTA O PEGA LA BASE ANONIMIZADA]

Transcripciones de entrevistas (adjuntas o pegadas, con códigos):
[ADJUNTA O PEGA]

Indicadores a calcular:
[LISTA DE INDICADORES, CON SU DEFINICIÓN]

Personas invitadas a responder: [NÚMERO]
Subgrupos de interés (por ejemplo, objetivo o perfil): [LISTA]

Tarea, en este orden:
0. Revisa si la base o las transcripciones contienen nombres, correos,
   teléfonos, documentos u otros identificadores. Si los encuentras, detente
   y dime cuáles son, sin repetirlos completos. No sigas.
1. Describe la base: número de filas, columnas, datos faltantes y tasa de
   respuesta (respondieron / invitadas).
2. Calcula cada indicador. Para cada resultado, indica la columna y el
   número de filas que usaste.
3. Repite el cálculo por cada subgrupo de interés. Muestra el promedio
   general y el de cada subgrupo.
4. En las transcripciones, identifica entre tres y cinco temas que aparecen
   en más de una persona. Para cada tema, indica en cuántas transcripciones
   aparece y propón dos citas textuales de perfiles distintos, incluidas las
   críticas.
5. Escribe tres a cinco hallazgos en lenguaje simple, uno por párrafo
   corto, cada uno con su cifra y su límite.
6. Propón una lectura alternativa para cada hallazgo (qué otra cosa podría
   explicar el mismo resultado).
7. Compara quién respondió con quién fue invitado, si hay datos para
   hacerlo, y dime si el resultado podría estar inclinado hacia quienes
   respondieron.

Formato de respuesta:
A. Resultado de la revisión de identificadores (paso 0)
B. Descripción de la base
C. Tabla: Indicador | Resultado general | Resultado por subgrupo | Columna y filas usadas
D. Temas cualitativos: Tema | Transcripciones donde aparece | Citas
E. Hallazgos en lenguaje simple
F. Lecturas alternativas y posible sesgo de respuesta
G. Lo que no puedo concluir con estos datos

Reglas:
- No uses ninguna cifra que no puedas rastrear a una columna y un número de
  filas. Si no se puede calcular, dilo.
- Toda cita debe aparecer palabra por palabra en las transcripciones.
- No afirmes que el programa causó un cambio salvo que los datos incluyan
  una comparación con el punto de partida o con un grupo de referencia.
- Si algo es ambiguo (una columna, una categoría), pregunta antes de
  calcular.
```

## Cómo leer el resultado

- Empieza por la parte A y la parte G: dicen si el análisis es utilizable y hasta dónde llega.
- La tabla C es tu lista de verificación. Abre la base y comprueba al menos tres cifras con una fórmula propia.
- Cada cita de la parte D debe existir en la transcripción. Búscala antes de usarla.
- La parte F es tu segunda lectura: la IA puede inclinarse hacia la que sugiere tu prompt.

## Verificación antes de comunicar

| Veracidad | Sesgo |
|---|---|
| [ ] Contrasté cada cifra del texto con la base original | [ ] Revisé quién respondió y quién no antes de generalizar |
| [ ] Pedí a la IA la columna o la fila de donde sale cada dato | [ ] Pedí el análisis por subgrupo y el promedio |
| [ ] Confirmé que cada cita exista en la transcripción | [ ] Elegí citas de varios perfiles, incluidas las críticas |
| [ ] Descarté cualquier cifra que no aparece en mis datos | [ ] Probé una segunda lectura con otra formulación |

## Qué sigue siendo tu decisión

Qué hallazgos son ciertos, cuáles se comunican y qué se hace con ellos. El juicio sobre qué hacer con una lectura es de quien decide.

## Ejemplo de uso

La entrada completa y la salida de este prompt con Barrio Verde están en `caso-barrio-verde/04-analisis-datos.md`.

## Referencias

- Verificación de veracidad y sesgo, y el papel de la IA como analista junior: Datimpacto (2026).
- Principio de minimización: Reglamento General de Protección de Datos de la Unión Europea, art. 5(1)(c).
