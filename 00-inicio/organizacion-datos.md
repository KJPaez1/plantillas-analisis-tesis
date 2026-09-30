# Organización de datos

Una tabla ordenada y documentada reduce errores y hace el análisis más fácil de revisar.

## Estructura recomendada

- Una fila por unidad de análisis (persona, muestra, parcela o medición, según el diseño).
- Una columna por variable; cada columna debe representar un concepto y tener un tipo claro.
- Una fila de encabezados, con nombres breves, únicos y sin saltos de línea.
- Identificador estable y no identificable directamente. No uses nombres, documentos o correos como ID.
- Fechas en formato ISO `AAAA-MM-DD`; unidades explícitas en el diccionario.
- Códigos consistentes para categorías. No mezcles, por ejemplo, `F`, `femenino` y `2`.

## Flujo de trabajo

1. Guarda el archivo recibido como original de solo lectura.
2. Registra fuente, fecha, versión, permisos y responsable del tratamiento.
3. Crea una copia de trabajo y conserva un registro de cada transformación.
4. Completa el [diccionario de datos](plantilla-diccionario-datos.xlsx).
5. Revisa duplicados, rangos, categorías, faltantes y consistencia con el protocolo.
6. Exporta una versión analítica limpia sin reemplazar el original.

## Datos faltantes y valores especiales

En la hoja de datos usa una celda vacía/NA según el formato y documenta el significado. Evita códigos numéricos como `99` para “no responde” en variables cuantitativas: podrían confundirse con observaciones válidas. Distingue ausencia estructural, no respuesta y dato no medido cuando sea posible.

## Confidencialidad y respaldo

Separa la llave que vincula identificadores de investigación de la base analítica; cifra y restringe el acceso según el protocolo institucional. Antes de compartir, evalúa riesgo de reidentificación incluso tras retirar nombres. No publiques bases sensibles en este repositorio.
