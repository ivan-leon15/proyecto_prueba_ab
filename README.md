# Proyecto: Optimización de Ingresos en una Tienda en Línea

## Contexto
El proyecto se lleva a cabo en una gran tienda en línea, donde se han recopilado hipótesis con el departamento de marketing que podrían ayudar a aumentar los ingresos. El objetivo es priorizar estas hipótesis, realizar un test A/B y analizar los resultados.

## Descripción de los Datos

### Datos utilizados en la primera parte del proyecto
- **Hipótesis**: `/datasets/hypotheses_us.csv`
  - Hypotheses: Descripciones breves de las hipótesis.
  - Reach: Alcance del usuario (escala del 1 al 10).
  - Impact: Impacto en los usuarios (escala del 1 al 10).
  - Confidence: Confianza en la hipótesis (escala del 1 al 10).
  - Effort: Recursos necesarios para probar una hipótesis (escala del 1 al 10).

### Datos utilizados en la segunda parte del proyecto
- **Órdenes**: `/datasets/orders_us.csv`
  - transactionId: Identificador de pedido.
  - visitorId: Identificador del usuario que realizó el pedido.
  - date: Fecha del pedido.
  - revenue: Ingresos del pedido.
  - group: Grupo del test A/B al que pertenece el usuario.

- **Visitas**: `/datasets/visits_us.csv`
  - date: Fecha.
  - group: Grupo del test A/B.
  - visits: Número de visitas en la fecha especificada para el grupo de test A/B.

## Pasos Realizados
1. **Priorizar Hipótesis**:
   - Aplicar el framework ICE para ordenar las hipótesis por prioridad.
   - Aplicar el framework RICE para ordenar las hipótesis por prioridad y comparar cambios en la priorización.

2. **Análisis de Test A/B**:
   - Gráficos del ingreso acumulado y tamaño de pedido promedio por grupo, con conclusiones.
   - Cálculo y representación de la tasa de conversión de cada grupo con conclusiones.
   - Análisis de dispersión del número de pedidos y precios de los pedidos, con identificación de anomalías.
   - Evaluación de la significancia estadística en conversiones y tamaños promedio de pedidos entre grupos.
   - Toma de decisiones basada en los resultados del test.

## Conclusión
De acuerdo al análisis realizado, se decidió considerar el grupo B como líder de la prueba debido a su rendimiento en la conversión y a la falta de diferencia significativa en el tamaño promedio de pedidos entre ambos grupos.
