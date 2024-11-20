# Proyecto: Optimización de Ingresos en una Tienda en Línea

## Contexto
Este proyecto se lleva a cabo en una gran tienda en línea, donde el departamento de marketing ha planteado diversas hipótesis que podrían contribuir al aumento de los ingresos. El objetivo es priorizar estas hipótesis, realizar un test A/B para probarlas y analizar los resultados obtenidos con el fin de optimizar la estrategia de ingresos de la tienda.

## Herramientas Utilizadas
- **Python (Pandas, NumPy):** Para la manipulación y análisis de datos.
- **Matplotlib / Seaborn:** Para la visualización de los datos.
- **Análisis A/B:** Aplicación del test A/B para evaluar el impacto de las hipótesis sobre el comportamiento de los usuarios y los ingresos.
- **Frameworks ICE y RICE:** Para la priorización de las hipótesis.

## Análisis de Resultados
### 1. **Priorizar Hipótesis**
- **Framework ICE:** Se utilizó para ordenar las hipótesis basándose en el impacto, la confianza y el esfuerzo. Las hipótesis con mayor puntuación en estos tres aspectos fueron priorizadas para las pruebas.
- **Framework RICE:** Se aplicó este segundo framework para evaluar las hipótesis en función de su alcance, impacto, confianza y esfuerzo. Se compararon los resultados de ICE y RICE, destacando diferencias clave en la priorización de ciertas hipótesis.

### 2. **Análisis de Test A/B**
- **Ingreso Acumulado y Tamaño Promedio de Pedido:** Se crearon gráficos que muestran el rendimiento de cada grupo (A y B) en términos de ingresos acumulados y tamaño promedio de pedido. El análisis reveló que el grupo B mostró un rendimiento superior en términos de conversión.
- **Tasa de Conversión:** Se calculó y representó la tasa de conversión para cada grupo. El grupo B mostró una tasa de conversión significativamente más alta que el grupo A, lo que sugiere que las modificaciones implementadas en el grupo B generaron un mayor interés y comportamiento de compra.
- **Análisis de Dispersión:** Se realizó un análisis de dispersión para evaluar la relación entre el número de pedidos y los precios. Se identificaron anomalías en los precios y en el volumen de pedidos, lo que ayudó a detectar áreas donde se podría mejorar la experiencia de compra.
- **Evaluación de Significancia Estadística:** Se analizó la significancia estadística de las diferencias en la tasa de conversión y el tamaño promedio de los pedidos entre ambos grupos. Los resultados mostraron que las diferencias en las conversiones fueron significativas, mientras que no hubo diferencias significativas en los tamaños promedio de los pedidos.

## Conclusiones
- **Grupo B como Líder:** A partir de los análisis realizados, se decidió considerar el grupo B como líder de la prueba. Este grupo presentó un mejor desempeño en la tasa de conversión, mientras que no hubo una diferencia estadísticamente significativa en los tamaños de los pedidos entre ambos grupos.
- **Optimización de Ingresos:** El grupo B muestra un mayor potencial de conversión, lo que sugiere que las estrategias implementadas en ese grupo tienen el impacto deseado en el comportamiento de compra de los usuarios. A partir de estos resultados, se recomienda ajustar las estrategias basadas en las características de este grupo para continuar optimizando los ingresos.

Este análisis ha permitido identificar cuál de las hipótesis puede generar mayores ingresos, lo que ayudará a la tienda en línea a enfocar sus esfuerzos de marketing de manera más efectiva.
