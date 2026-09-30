# Explicación metodológica

## Diseño y estimando

La comparación de grupos independientes pregunta cómo difiere un resultado entre dos conjuntos de unidades. Antes de calcular, determina si interesa la diferencia de medias, una diferencia de localización u otro resumen. Esa decisión define lo que significa el resultado.

## Diferencia de medias

La diferencia de medias es interpretable en las unidades originales. Un intervalo de confianza muestra la precisión de la estimación. El contraste t de Welch permite varianzas distintas entre grupos y suele ser una opción razonable para comparar medias, siempre que el diseño y la distribución permitan una inferencia útil. Con muestras pequeñas, la forma de la distribución y observaciones influyentes importan especialmente.

## Supuestos y diagnósticos

- **Independencia:** se deriva del diseño y del muestreo; no se demuestra con una prueba de normalidad.
- **Medición y selección:** deben corresponder a la pregunta y protocolo.
- **Distribución y observaciones influyentes:** explora gráficos y analiza la sensibilidad de la media a valores extremos justificados.
- **Varianzas:** Welch no exige igualdad de varianzas.

No conviertas una prueba preliminar de normalidad en una regla automática para seleccionar el análisis. Los diagnósticos tienen poca potencia en muestras pequeñas y pueden señalar desviaciones triviales en muestras grandes.

## Alternativas

La prueba de Mann–Whitney compara distribuciones/rangos y su interpretación como diferencia de medianas requiere supuestos adicionales sobre la forma de las distribuciones. Métodos robustos o de permutación pueden responder preguntas distintas y necesitan especificar el estimando y el esquema de aleatorización/intercambiabilidad. Consulta a un especialista si el diseño es complejo.

## Tamaño de efecto e incertidumbre

Reporta la diferencia en unidades originales con intervalo de confianza y tamaños de cada grupo. Una medida estandarizada puede complementar, pero no sustituir, la diferencia interpretable. No uses etiquetas de efecto “pequeño/mediano/grande” sin justificar umbrales contextualizados.
