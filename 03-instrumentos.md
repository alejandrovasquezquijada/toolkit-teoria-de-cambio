# Guía: diseñar instrumentos de recolección de datos

Datimpacto · www.datimpacto.com · Pieza 03

**Propósito:** pasar de un indicador a una pregunta, de la pregunta a un instrumento, y del instrumento a una base que se consolide sola, con los cuidados éticos antes de abrir un asistente de IA.
**Cuándo usarla:** cuando ya tienes indicadores validados (Pieza 02) y necesitas decidir cómo recoger el dato.
**Tiempo:** 30 a 45 minutos por instrumento.

## Paso 1: la cadena

Cada indicador necesita una pregunta, un instrumento y un destino para la respuesta.

| Indicador | Pregunta | Instrumento | Base consolidada |
|---|---|---|---|
| Cuantitativo | Cerrada, con opciones | Formulario de seguimiento | Las respuestas llegan solas, sin tabulación manual |
| Cualitativo | Abierta, sobre una experiencia concreta | Guía de entrevista | Transcripciones codificadas por tema |

Completa una fila por indicador antes de redactar ninguna pregunta:

| Indicador | Quién responde | Cuándo | Instrumento | Dónde se guarda |
|---|---|---|---|---|
| [INDICADOR] | [PERSONAS] | [MOMENTO] | [FORMULARIO / ENTREVISTA] | [HERRAMIENTA] |

## Paso 2: criterios de una buena pregunta

Revisa cada pregunta con esta lista.

- [ ] Mide un solo indicador. Una pregunta que mezcla dos cosas no se puede analizar.
- [ ] No sugiere la respuesta. "¿Qué tan útil fue el programa?" supone que fue útil. "¿Qué cambió en tu trabajo después del programa?" no lo supone.
- [ ] Usa las palabras de las personas que responden, no las del equipo técnico.
- [ ] Pide una experiencia concreta, no una opinión general. "Cuéntame cómo fue la última semana en tu casa con los residuos" da más que "¿te sientes más comprometido con el ambiente?".
- [ ] Cabe en el tiempo que las personas pueden dedicar.
- [ ] Cada dato que pide tiene una razón en un indicador. Si no, se elimina.

## Paso 3: redactar y revisar con IA

La IA redacta preguntas a partir del indicador y detecta las que inducen la respuesta. Tú decides qué preguntar, a quién y cuándo.

```
Eres un especialista en diseño de instrumentos de recolección de datos para
organizaciones sociales. Propones preguntas en borrador. No decides qué se
pregunta.

Indicador:
[INDICADOR REDACTADO: SUJETO + VARIABLE + CUÁNDO]

Tipo de instrumento:
[FORMULARIO DE SEGUIMIENTO / GUÍA DE ENTREVISTA]

Personas que responderán (perfil y contexto, sin nombres):
[PERFIL]

Tarea:
1. Propón entre tres y cinco preguntas que permitan calcular o describir
   el indicador. Si es cuantitativo, con opciones de respuesta. Si es
   cualitativo, abiertas y sobre una experiencia concreta.
2. Para cada pregunta, indica qué parte del indicador cubre.
3. Revisa tus propias preguntas con esta lista y marca las que fallen:
   a. Mezcla más de un tema.
   b. Sugiere o supone la respuesta (pregunta inductora).
   c. Usa términos técnicos que la persona no usaría.
   d. Pide un dato que el indicador no necesita.
4. Reescribe una vez las que fallen y muestra antes y después.

Formato de respuesta:
A. Tabla: Pregunta | Parte del indicador que cubre | Opciones de respuesta
B. Tabla: Pregunta que falló | Motivo (a, b, c o d) | Reescritura
C. Datos personales que las preguntas piden y que el indicador no necesita

Reglas:
- No pidas nombres, documentos, teléfonos ni direcciones salvo que el
  indicador lo exija, y en ese caso dilo en la parte C.
- No inventes escalas ni categorías sin indicar que son una propuesta.
```

Nota sobre datos: este prompt trabaja con el indicador y el perfil del grupo. No pegues respuestas de personas.

## Paso 4: tres cuidados antes de abrir un asistente de IA

| Cuidado | Qué significa | Cómo se ve en la práctica |
|---|---|---|
| Consentimiento | Las personas saben para qué usarás sus datos, incluido el uso de herramientas de IA, y lo aceptan | El formulario o la guía de entrevista lo dice al inicio, con una casilla o una frase de aceptación |
| Minimización | Recoges y compartes con la IA solo lo que el indicador necesita | Cada campo del instrumento responde a un indicador |
| Anonimización | Quitas nombres, contactos y otros identificadores antes de subir una base o una transcripción | Cada persona tiene un código (P001, P002), y la lista de equivalencias queda fuera de la herramienta |

Regla práctica: si un dato identifica a una persona y la pregunta no lo necesita, no entra a la herramienta. Revisa también la política de IA de tu organización.

## Ejemplo de uso

La cadena completada, las preguntas revisadas y el texto de consentimiento de Barrio Verde están en `caso-barrio-verde/03-instrumentos.md`.

## Qué sigue siendo tu decisión

Qué preguntar, a quién, cuándo y con qué consentimiento. La IA propone redacciones. El equipo decide el instrumento final y lo prueba con dos o tres personas antes de usarlo.

## Referencias

- Cadena indicador, pregunta, instrumento y base: Datimpacto (2026).
- Principio de minimización: Reglamento General de Protección de Datos de la Unión Europea, art. 5(1)(c).
