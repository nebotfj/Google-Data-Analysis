#  DECISIONES BASADAS EN DATOS

En el análisis, los datos impulsan la toma de decisiones. En esta parte del curso, explorarás datos de todo tipo y sus repercusiones en las elecciones y estrategias de la vida real. También aprenderás a compartir tus datos a través de informes y paneles.
--------
Objetivos de aprendizaje
- Debatir el uso de datos en el proceso de toma de decisiones
- Comparar y contrastar la toma de decisiones basada en datos con la toma de decisiones inspirada en datos
- Explicar la diferencia entre los datos cuantitativos y los cualitativos, incluidas las referencias a su uso y los ejemplos específicos
- Analizar la importancia y los beneficios de los paneles e informes para el analista de datos con referencia a Tableau y las hojas de cálculo
- Diferenciar entre datos y métricas con ejemplos específicos
- Demostrar una comprensión de lo que implica el uso de un enfoque matemático para analizar un problema

## Comprender el poder de los datos 
Data-inspired-decision-making: Explores different data sources to find out what they have in common (similitudes).

[Cómo la estrategia de datos de un minorista impulsa experiencias perfectas para el cliente](https://www.thinkwithgoogle.com/future-of-marketing/digital-transformation/crate-and-barrel-digital-customer-experiences/)


Quantitative data: Specific aqnd objective measures of numerical facts (The what? How manuy? How often?)
Qualitative data: Subjective or explanatory measures of qualities and characteristics (charts, Graphs)

Por lo general, los analistas de datos usarán ambos tipos de datos en su trabajo. A menudo, los datos cualitativos pueden ayudar a los analistas a comprender mejor sus datos cuantitativos al proporcionar una razón o una explicación más completa. En otras palabras, los datos cuantitativos suelen mostrar el qué, y los datos cualitativos suelen mostrar el por qué. Mediante el uso de datos cuantitativos y cualitativos, podemos aprender cuándo a las personas les gusta ir al cine y por qué eligen el cine. Tal vez realmente les gusten las sillas reclinables, por lo que tu gerente puede comprar más sillas reclinables. Tal vez el cine es el único que sirve cerveza de raíz. Tal vez un espectáculo en un horario posterior les da más tiempo para conducir hasta el cine desde donde se encuentran los restaurantes populares. Tal vez van a las matinés porque tienen hijos y quieren ahorrar dinero. No habríamos descubierto esta información analizando solo los datos cuantitativos de asistencia, ganancias y horarios de exhibición.

## Sigue la evidencia
### La gran revelación: compartir tus hallazgos
Report: Un informe es una recopilación estática de datos que se entrega periódicamente a los interesados
- Pros: 
  - High-level historical data
  - Easy to design
  - Pre-cleaned sorted data
- Cons:
  - Continual maintenance
  - Less visually appealing
  - Static
 
Dashboard: Un panel, monitorea los datos entrantes en vivo.
- Pros
  - Dynamic, automatic and interactive
  - More stakeholder access
  - Low maintenance
- Cons
  - Labor-intensive design
  - Can be confusing
  - Potentially uncleaned data
  
  Pivot Table (Tabla dinámica)
Una tabla dinámica es una herramienta de resumen de datos utilizada en el procesamiento de datos. Las tablas dinámicas se usan para resumir, ordenar, reorganizar, agrupar, contabilizar, totalizar o promediar los datos almacenados en una base de datos. Permite que los usuarios transformen las columnas en filas y las filas en columnas.

A data summarization tool that is used in data processing. Pivot tables are used to summarize, sort, reorganize, group, count, total or average data stored in a database.

##DATOS VS METRICAS 

- Metricas (Metric) Una métrica es un tipo único y cuantificable de datos que pueden utilizarse para le medición
- Objetivo métrico (Metric Goal) Conjunto de objetivos medibles establecido por una empresa y evaluado mediante métricas.

## LA BELLEZA DE LOS PANELES
| Beneficios | Para los analistas de datos | Para los interesados | 
--- | --- | ---
| Centralización | Compartir una única fuente de datos con todos los interesados | Trabajar con una visión integral de datos, iniciativas, objetivos, proyectos, procesos y más |
| Visualización | Mostrar y actualizar datos entrantes en vivo en tiempo real* | Detectar patrones y tendencias cambiantes más rápidamente
| Percepción | Extraer información relevante de diferentes conjuntos de datos | Comprender la historia detrás de los números para realizar un seguimiento de los objetivos y tomar decisiones basadas en datos |
| Personalización | Crear vistas personalizadas dedicadas a una persona específica, un proyecto o una presentación de los datos |  Profundizar en áreas más específicas de preocupaciones o intereses especializados |

### Creación de un panel. Aquí hay un proceso que puedes seguir para crear un panel:
1. Identificar a los interesados que necesitan ver los datos y cómo los usarán
[Requirements+Gathering+Worksheet (1).pdf](https://github.com/sirjn/Google-Data-Analysis/files/9547376/Requirements%2BGathering%2BWorksheet.1.pdf)

2. Diseñar el panel (lo que se debe mostrar)
Sigue estos consejos para que el diseño de tu panel sea claro, fácil de seguir y simple:
- Usa un encabezado claro para etiquetar la información
- Agrega descripciones de texto cortas a cada visualización
- Muestra la información más importante en la parte superior

3. Crea prototipos si lo deseas (opcional)

4. Selecciona las visualizaciones que utilizarás en el panel
<img width="831" alt="LNd1iz7jT-aXdYs-40_m5w_b74f77a457b64a2fadf07d9b57496816_Screen-Shot-2020-12-11-at-11 51 45-AM" src="https://user-images.githubusercontent.com/72023291/189639275-60823a4d-97af-4bee-8cc4-002492543a8d.png">

- Para obtener más información sobre cómo elegir las visualizaciones correctas, consulta el breve curso de [Looker sobre cómo diseñar excelentes paneles](https://training.looker.com/designing-great-dashboards). Simplemente regístrate y podrás acceder al tutorial completo de forma gratuita. También puedes visitar las galerías de Tableau:
- Para obtener más muestras de gráficos de área, gráficos de columnas y otras visualizaciones, [visita la Galería de visualizaciones de Tableau](https://www.tableau.com/solutions/gallery). Esta galería está repleta de buenos ejemplos que fueron creados usando datos reales; explora este recurso por tu cuenta para obtener algo de inspiración.

Explora la [Visualización del día de Tableau](https://public.tableau.com/en-us/gallery/?tab=viz-of-the-day&type=viz-of-the-day) para ver las visualizaciones seleccionadas por la comunidad. Estas son visualizaciones creadas por usuarios de Tableau y son una excelente manera de obtener más información sobre cómo otros analistas de datos utilizan las herramientas de visualización de datos. 

5. Crea filtros según sea necesario

Los filtros muestran ciertos datos mientras ocultan el resto de los datos de un panel. Esto puede ser de gran ayuda para identificar patrones mientras se mantienen intactos los datos originales. Es común que los analistas de datos usen y compartan el mismo panel, pero administren su parte con un filtro. Para profundizar en los filtros y encontrar un ejemplo de filtros en acción, puedes visitar la página de Tableau en [Acciones con filtros](https://help.tableau.com/current/pro/desktop/en-us/actions_filter.htm). Este es un recurso útil para que guardes y vuelvas a verlo cuando empieces a practicar el uso de los filtros en Tableau por tu cuenta.

Los paneles forman parte de un viaje de negocios
**Si agregas marcadores claros y resaltas los puntos importantes en tu panel, los usuarios entenderán hacia dónde se dirige tu historia de datos. Luego, pueden trabajar juntos para asegurarse de que la empresa llegue a donde debe ir.**


# TIPOS DE PANELES
___
Las tres categorías más comunes son las siguientes:

- Estratégico: se centra en objetivos y estrategias a largo plazo al más alto nivel de métricas
- Operativo: presenta un seguimiento del desempeño a corto plazo y objetivos intermedios
- Analítico: consiste en los conjuntos de datos y las matemáticas que se usan en estos conjuntos

1. Paneles estratégicos

Una amplia gama de empresas usan paneles estratégicos para evaluar y alinear sus objetivos estratégicos. Estos paneles proporcionan información durante el período más largo, desde un único trimestre financiero hasta años.

Por lo general, contienen información útil para la toma de decisiones en toda la empresa. A continuación, se muestra un ejemplo de un panel estratégico que se centra en los indicadores clave de rendimiento (KPI) durante un año.
![b309be6b-1903-4111-b327-0bccf889876bimage4](https://user-images.githubusercontent.com/72023291/189640527-7b1388fe-8d94-44ef-bc1f-2a89e2060488.png)

2. Paneles operativos
Tipo de panel más común. Dado que estos paneles contienen información en una escala temporal de días, semanas o meses, pueden proporcionar información sobre el desempeño casi en tiempo real.

Esto les permite a las empresas realizar un seguimiento y mantener sus procesos operativos inmediatos a la luz de sus objetivos estratégicos. El panel operativo que aparece a continuación se centra en el servicio al cliente.

![b309be6b-1903-4111-b327-0bccf889876bimage5](https://user-images.githubusercontent.com/72023291/189641638-00ee5f14-91a6-41bc-8fe9-06f9e28711b2.png)

3. Paneles analíticos

Los paneles analíticos contienen una gran cantidad de datos utilizados por los analistas de datos. Estos paneles contienen los detalles relacionados con el uso, el análisis y las predicciones realizadas por los científicos de datos.

Es la categoría más técnica; los paneles analíticos suelen ser creados y mantenidos por equipos de ciencia de datos y rara vez se comparten con la alta dirección, ya que pueden ser muy difíciles de entender. El panel analítico que aparece a continuación se centra en las métricas del desempeño financiero de una empresa.

![b309be6b-1903-4111-b327-0bccf889876bimage6](https://user-images.githubusercontent.com/72023291/189641592-3fa84c8e-7dfd-4dda-a8ec-02045896112f.png)





