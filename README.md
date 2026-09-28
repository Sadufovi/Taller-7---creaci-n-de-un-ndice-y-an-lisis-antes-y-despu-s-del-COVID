# Taller 7: Construcción de un índice para entender cambios en la economía global antes y después del COVID

Repositorio del equipo consultor para el encargo del fondo de inversión interesado en analizar la evolución y desempeño de tres sectores de la economía global entre 2015 y 2025. El objetivo es construir índices sectoriales transparentes a partir de datos de mercado, evaluar el impacto de distintas reglas de ponderación (precio vs. volumen), comparar retornos y volatilidad entre el periodo previo y posterior al COVID-19, y estructurar una recomendación de inversión clara y fundamentada.

## Equipo consultor

| Integrante | Rol |
| :--- | :--- |
| *Samuel Dussán Fonseca* | *Líder del proyecto y enlace con el fondo* |
| *Chari Valeria Reyes Arias* | *Especialista en datos y reproducibilidad* |
| *Mariana Forigua Tamayo* | *Analista cuantitativo* |
| *Santiago Gómez Ibague* | *Especialista en visualización y comunicación* |
| *María Paula Monroy Molina* | *Analista cuantitativo / Apoyo en investigación* |

> Los roles definen una responsabilidad principal, no dividen el taller en partes aisladas. Todos los productos son responsabilidad conjunta y cualquier integrante puede ser seleccionado como portavoz en la Sesión 3.

## Descripción del encargo

El fondo de inversión requiere entender la evolución sectorial comparada entre 2015 y 2025, analizando el comportamiento antes y después del impacto del COVID-19 para orientar la asignación de sus recursos. Puntualmente, se busca responder a las siguientes preguntas clave:

1. **Construcción y ponderación de índices:** ¿Cómo se comportan los índices sectoriales según las distintas reglas de ponderación (volumen inicial vs. precio inicial) y qué implicaciones tiene la regla de ponderación para la lectura del fondo?
2. **Resumen y comportamiento:** ¿Qué revelan los retornos diarios ponderados, su dispersión, *outliers* y la evolución acumulada normalizada (base 100 en 2015) sobre la dinámica de cada sector?
3. **Comparación pre y post COVID (2015 vs. 2025):** ¿Existen diferencias estadísticamente significativas en términos de retorno promedio, desviación estándar e intervalos de confianza (95%) entre 2015 y 2025?
4. **Recomendación estratégica:** ¿Qué sector(es) debería el fondo priorizar, mantener bajo observación o evitar, considerando el desempeño acumulado, la dispersión, los eventos extremos y las limitaciones metodológicas del análisis?

El análisis se basa en datos de precios de cierre diario y volúmenes de transacción (2015–2025) obtenidos mediante Bloomberg, estructurados y procesados rigurosamente en Excel (y opcionalmente respaldados en Power BI), siguiendo la metodología de *Doing Economics* (CORE Econ, Cap. 10.2).

## Estructura del repositorio

```text
TALLER_7_INDICES_COVID/
├── Datos_y_Analisis/
│   └── taller7_indices_fondo.xlsx    # Libro de Excel dinámico, verificado y reproducible
├── Presentacion/
│   └── taller7_briefing.pptx         # Presentación ejecutiva para el cliente (Sesión 3)
├── Dashboard/                        # (Opcional) Dashboard interactivo de apoyo
│   └── taller7_visualizacion.pbix
└── README.md                         # Documentación principal del proyecto
