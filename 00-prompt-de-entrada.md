# Prompt de entrada: pega lo que tengas y mira el recorrido completo

Datimpacto · www.datimpacto.com · Pieza 00

**Propósito:** a partir de un párrafo, un one pager o una propuesta, obtener un primer borrador del recorrido completo: teoría de cambio, indicadores, instrumentos, plan de análisis y estructura de una narrativa de financiamiento.
**Cuándo usarla:** al empezar, para ver el mapa completo antes de profundizar. Después pasas a las piezas 01 a 05 para cada paso.
**Tiempo:** 5 minutos para correrla, 20 para leer y corregir el resultado con tu equipo.

## Qué necesitas

- Cualquier texto que describa lo que hace tu organización: un párrafo, un one pager, el resumen de una propuesta, la descripción de un proyecto.
- Si lo tienes: una cifra o un testimonio sobre el problema que atienden.

Nota sobre datos: usa descripciones del programa y cifras agregadas. No pegues nombres ni datos de las personas que atiendes.

## El prompt

```
Eres un facilitador de teoría de cambio y de medición para organizaciones
sociales pequeñas. Propones borradores para que un equipo los revise. No
inventas información: si algo falta, lo señalas con [FALTA].

Lo que tengo sobre mi organización (pegado tal cual, sin ordenar):
[PEGA AQUÍ UN PÁRRAFO, UN ONE PAGER O UNA PROPUESTA]

Tarea, en este orden:

1. Teoría de cambio. Organiza lo que escribí en seis etapas: Problema,
   Recursos, Actividades, Outputs, Outcomes e Impacto. Un output es lo que
   producen directamente las actividades (se cuenta). Un outcome es lo que
   cambia en las personas o en el entorno por las actividades (se mide
   preguntando u observando). Escribe el supuesto entre cada etapa, con la
   forma "si hacemos X, esperamos Y porque Z". Si hay más de una línea de
   trabajo, muéstrala como ramificación.

2. Indicadores. Para cada outcome propón dos indicadores y para cada output
   uno. Redacta cada uno con sujeto (quién cambia) + variable (qué cambia) +
   cuándo se mide. Marca cumple o no cumple en SMART y reescribe los que no
   cumplan.

3. Instrumentos. Para los dos indicadores de outcome más importantes, indica
   qué pregunta exacta harías, a quién, cuándo y con qué instrumento
   (encuesta corta o guía de entrevista).

4. Análisis. Dime qué tendría que cruzar o comparar para saber si el cambio
   ocurrió y para quién (por ejemplo, por subgrupo o frente al punto de
   partida), y qué dato necesitaría tener desde el inicio.

5. Narrativa. Muestra la estructura de un texto de evidencia para un
   financista con huecos para llenar: a quién llega, cuánto cambió, por
   cuánto tiempo, una voz de las personas y el límite del dato.

6. Lo que falta. Lista qué información debería conseguir mi equipo antes de
   confiar en este borrador.

Formato de respuesta:
A. Tabla: Etapa | Contenido | Supuesto hacia la etapa siguiente
B. Tabla: Etapa | Indicador | Tipo (cuantitativo o cualitativo) | SMART
C. Tabla: Indicador | Pregunta | A quién | Cuándo | Instrumento
D. Plan de análisis en cinco líneas
E. Estructura de la narrativa, con huecos
F. Información que falta

Reglas:
- Usa solo lo que escribí. No inventes cifras, actividades ni resultados.
- No fijes metas. Las metas se definen después de tener una línea de base.
- Si un supuesto no tiene respaldo en lo que escribí, márcalo como
  "supuesto sin evidencia".
- No decidas por mi equipo. Propón y señala dudas.
```

## Cómo leer el resultado

- Empieza por F: lo que falta es tu lista de tareas.
- Revisa A con alguien que conozca el programa en terreno. Si la IA puso como outcome algo que en realidad se cuenta (personas atendidas, talleres, kilos recolectados), es un output.
- De B quédate con pocos indicadores. Uno por resultado que de verdad vayas a recoger.
- Con C puedes probar las preguntas con dos o tres personas antes de usarlas.

## Qué sigue siendo tu decisión

Qué entra en la teoría, qué indicadores se adoptan, qué se pregunta y qué se comunica. La IA ordena y propone. El equipo corrige y decide.

## Ejemplo de uso

La entrada y la salida de este prompt con Barrio Verde están en `caso-barrio-verde/00-prompt-de-entrada.md`.

## Referencias

- Weiss, C. H. (1995). Nothing as Practical as Good Theory.
- Rogers, P. (2014). Theory of Change. UNICEF, Methodological Brief No. 2.
- W. K. Kellogg Foundation (2004). Logic Model Development Guide.
- Doran, G. T. (1981). There's a S.M.A.R.T. way to write management's goals and objectives. Management Review, 70(11).
