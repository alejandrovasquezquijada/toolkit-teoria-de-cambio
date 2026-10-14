# Caso Barrio Verde: pieza 04, análisis de datos

Datimpacto · www.datimpacto.com

## Entrada

- Base: `barrio-verde-encuesta-6m.csv` (175 filas, un código por hogar, sin nombres ni direcciones).
- Transcripciones: `barrio-verde-entrevistas.md` (6 entrevistas con códigos).
- Indicadores: % de hogares que separa orgánicos 5 días o más por semana (columna `dias_separa_por_semana`); kilos de basura a relleno por semana, antes y a los 6 meses.
- Hogares invitados: 250. Subgrupos: distancia al punto de acopio y asistencia a taller.

## Salida (revisada por el equipo, con cifras verificadas en la hoja)

**A. Identificadores:** ninguno encontrado.

**B. Descripción de la base:** 175 filas y 7 columnas. Faltan datos de pesaje en 135 hogares, porque solo se pesó una muestra de 40. Tasa de respuesta: 175 de 250 = 70%.

**C. Indicadores**

| Indicador | General | Por subgrupo | Columna y filas |
|---|---|---|---|
| % que separa 5 días o más por semana | 52% (91 de 175) | Punto a menos de 4 cuadras: 63% (62 de 98). A más de 4 cuadras: 38% (29 de 77). Con taller: 54% (53 de 98). Sin taller: 49% (38 de 77) | `dias_separa_por_semana`, 175 filas |
| Kilos de basura a relleno por semana | De 11,0 a 8,0 en promedio | Solo hay muestra general | `kg_relleno_semana_antes` y `kg_relleno_semana_6m`, 40 filas |

**D. Temas cualitativos**

| Tema | Entrevistas | Cita |
|---|---|---|
| La distancia al punto de acopio decide si continúan | E02, E03, E05 | "Si el punto estuviera más lejos no sé si seguiría, la verdad." (E02) |
| La visita en casa pesó más que el taller | E01, E02 | "…la chica que vino a casa me mostró cómo hacerlo y eso ayudó mucho." (E01) |
| El taller no cambió una decisión ya tomada | E02, E05 | "Fui al taller y estuvo bien, pero ya estaba convencida antes de ir." (E05) |

**E. Hallazgos en lenguaje simple**

1. Poco más de la mitad de los hogares que respondió separa orgánicos cinco días o más por semana a los seis meses (52%).
2. El hábito se sostiene más cerca de un punto de acopio: 63% a menos de cuatro cuadras frente a 38% a más de cuatro.
3. Entre quienes no sostienen el hábito, la razón más repetida es la distancia (31 de 84 hogares). En los hogares a más de cuatro cuadras es la mitad de los casos (25 de 48).
4. En la muestra de 40 hogares, la basura que va a relleno bajó de 11 a 8 kilos por semana en promedio.
5. Asistir a un taller se asocia con una diferencia pequeña (54% frente a 49%).

**F. Lecturas alternativas y sesgo**

- Hallazgo 2: los hogares cerca de un punto pueden ser también los de mayor motivación previa. No se puede afirmar que el punto cercano cause el hábito.
- Hallazgo 4: la muestra de 40 hogares no se eligió al azar entre todos los hogares con kit. Puede incluir más hogares motivados.
- Respondió el 70%. Quienes abandonaron el hábito pueden haber respondido menos. El 52% puede estar sobrestimado.

**G. Lo que no se puede concluir:** que el programa causó el cambio (no hay comparación con hogares sin kit), ni que el hábito dure más allá de los seis meses.

## Verificación hecha por el equipo

- Recalculó 91 de 175 y los dos subgrupos de distancia con una fórmula de la hoja.
- Buscó las tres citas en las transcripciones: las tres existen palabra por palabra.
- Pidió una segunda lectura con otra formulación del prompt y obtuvo los mismos porcentajes.
