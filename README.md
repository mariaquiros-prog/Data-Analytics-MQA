# Data-Analytics-MQA
Este proyecto realiza un análisis exploratorio (EDA) y estratégico de los datos de formación (L&D) de la organización, que comprende más de 2000 cursos impartidos.
El objetivo principal es identificar patrones de inversión, distribución de la formación y efectividad de los programas (medida por el Estado del curso) para optimizar la estrategia futura de capacitación.
Se utilizaron técnicas de análisis de datos tabulares y agregación de métricas (como tasas de finalización, coste promedio) para generar insights accionables sobre, por ejemplo, efectividad: ¿qué proveedores de formación tienen mayor tasa de éxito?
Este proyecto está basado en el análisis de datos estructurados creado por la IA

Resultados y Conclusiones

El análisis del estado de los cursos es la métrica principal de eficiencia del programa, destacando un alto grado de compromiso profesional:
Alto Éxito de Finalización: A nivel global, la inmensa mayoría de los cursos terminan en estado "Realizado" o "Aprobado"
Eficiencia Operativa: De los 2042 cursos totales, solo el 1.6% fueron "Cancelados", lo que subraya una excelente planificación y seguimiento de las inscripciones.

El análisis por tiempo y por título permite dirigir los esfuerzos de inversión y recursos:
Picos de Actividad Anual (2025): Se observa una marcada estacionalidad. La actividad se concentra en la segunda mitad del año, siendo Septiembre y Octubre los meses con la mayor cantidad de cursos realizados (401 cada uno), mientras que Agosto representa el punto más bajo (11 cursos).
Top Cursos Estratégicos: El dashboard identifica inmediatamente los cursos de mayor demanda, como la formación en "CHAT GPT y Microsoft Copilot" y "Resolución de problemas en entornos VUCA", siendo los más realizados (38 y 36 veces, respectivamente).

Las métricas del dashboard son esenciales para la gestión financiera y de partners:
Costo Promedio de la Formación: Al visualizar el costo promedio por curso, se puede ver la inversión por área. Por ejemplo, la formación en "Smart Start: Resolución de problemas en entornos VUCA" se destaca por tener uno de los costos promedio más altos, lo cual debe contrastarse con su alta demanda.
Concentración de Proveedores: El volumen de cursos está altamente concentrado en pocos partners. Cas Training se posiciona como el proveedor líder, con 204 cursos realizados. Esta información es crucial para evaluar la dependencia y negociar futuras tarifas y contratos.

Próximos Pasos
Integración de Dimensiones: Refinar el análisis de los resultados del dashboard mediante la integración de variables clave de la base de datos que aún no están en la vista principal, como la segmentación por Unidad de Gestión, Puesto y Edad de los profesionales.
Análisis de Series Temporales: Extender el análisis de la estacionalidad (Mes de inicio) a varios años para identificar tendencias a largo plazo en la demanda de formación.

Contribuciones
Este proyecto está abierto a la colaboración para mejorar el análisis y la calidad del código.
