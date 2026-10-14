# Prompt: convertir datos en narrativa de financiamiento

Datimpacto · www.datimpacto.com · Pieza 05

**Propósito:** redactar un texto de evidencia para un reporte o una conversación con financistas, con cifras, una voz de las personas atendidas y el límite del dato a la vista.
**Cuándo usarla:** cuando ya analizaste y verificaste tus datos (Pieza 04) y necesitas comunicarlos.
**Tiempo:** 10 minutos para correr el prompt, 20 para revisar y ajustar.

## Qué necesitas

- Los hallazgos ya analizados y verificados: cifras con su base (cuántas personas, qué porcentaje respondió) y el momento en que se midieron.
- Una o dos citas textuales de personas atendidas, anonimizadas, de perfiles distintos.
- A quién va dirigido el texto y cuántas palabras tiene el espacio.
- Si lo conoces: qué evidencia suele pedir ese financista.

Nota sobre datos: usa cifras agregadas y citas anonimizadas. No pegues nombres ni datos de personas.

## El prompt

```
Eres un redactor de reportes de evidencia para organizaciones sociales.
Escribes texto a partir de datos que ya fueron analizados y verificados por
una persona. No agregas datos.

Datos ya analizados (cifra, base de la que sale y momento de la medición):
[CIFRA 1: QUÉ MIDE, SOBRE CUÁNTAS PERSONAS, CUÁNDO]
[CIFRA 2: ...]
[TASA DE RESPUESTA O COBERTURA DEL DATO]

Citas textuales anonimizadas (perfil entre paréntesis):
["CITA 1" (PERFIL)]
["CITA 2" (PERFIL)]

Destinatario del texto:
[FINANCISTA, TIPO DE REPORTE O CONVERSACIÓN]

Extensión máxima:
[NÚMERO] palabras

Qué suele pedir este destinatario (opcional):
[POR EJEMPLO: ALCANCE, DURACIÓN DEL CAMBIO, CAUSALIDAD]

Tarea:
1. Redacta un texto de evidencia que incluya: a quién llega el programa,
   cuánto cambió y por cuánto tiempo (si el dato existe), una cita y el
   límite del dato.
2. El límite del dato debe decir qué porcentaje respondió, qué grupo está
   subrepresentado o qué no se puede afirmar.
3. Usa verbos que no atribuyan causa salvo que los datos incluyan una
   comparación con el punto de partida o con un grupo de referencia. Si no
   la hay, escribe "después de", "durante" o "entre quienes".
4. Entrega una tabla que relacione cada cifra del texto con el dato de
   entrada del que sale.

Formato de respuesta:
A. Texto de evidencia (máximo [NÚMERO] palabras)
B. Tabla: Cifra o cita del texto | Dato de entrada del que sale
C. Qué quedó fuera del texto y por qué
D. Qué afirmación NO se puede sostener con estos datos

Reglas:
- No uses ninguna cifra, porcentaje ni comparación que no esté en los datos
  de entrada. Si falta un dato para completar una frase, escribe [DATO
  FALTANTE].
- Las citas van textuales, entre comillas y sin editar.
- No uses lenguaje de promoción ("impresionante", "transformador"). Texto
  llano.
- El límite del dato va dentro del texto, no en una nota al pie.
```

## Cómo leer el resultado

- Compara cada cifra del texto con tu base original, usando la tabla B. Una cifra que no se encuentra no se publica.
- Revisa la parte D antes de enviar: si el financista pregunta por algo que figura ahí, ya sabes qué responder.
- Si el texto suena más seguro que tus datos, baja el tono. Una conclusión con sus límites a la vista resiste mejor una conversación con un financista.
- Lee el texto en voz alta. Si no lo dirías a la persona que lo va a leer, reescríbelo.

## Qué sigue siendo tu decisión

Qué se comunica, qué se deja fuera y con qué tono. La IA redacta. El equipo responde por cada cifra frente al financista.

## Ejemplo de uso

La entrada completa y la salida de este prompt con Barrio Verde están en `caso-barrio-verde/05-narrativa-financiamiento.md`.

## Referencias

- Dimensiones de evidencia (quién, cuánto, contribución, riesgo): Impact Management Project.
- Verificación de veracidad y sesgo antes de comunicar: Datimpacto (2026).
