# ds2-primera-entrega-turismo-emisivo
Análisis exploratorio y modelo econométrico del turismo emisivo argentino (2016–2025). Se estudian estacionalidad, destinos, transporte y relación con variables macroeconómicas (tipo de cambio, salarios y feriados). Proyecto realizado para Data Science II – Coderhouse.

🌍 Turismo Emisivo Argentino (2016–2025)

📊 Data Science II – Primera Entrega
🏫 Coderhouse
👤 Autor: Santiago Quagliotti
📅 Fecha: 16/02/2026

📌 Descripción del Proyecto

El turismo emisivo (viajes de residentes argentinos al exterior) es un indicador relevante para agencias de viaje y analistas económicos, ya que refleja decisiones de consumo, estacionalidad y sensibilidad a variables macroeconómicas.

Este proyecto analiza:

La evolución temporal del turismo emisivo argentino (2016–2025)

La estacionalidad del fenómeno

Los destinos más visitados

La distribución por medio de transporte

La relación con variables macroeconómicas:

Tipo de cambio

Índice de salarios

Cantidad de feriados

La sensibilidad cambiaria por destino

Un modelo econométrico exploratorio

🎯 Objetivos

Identificar patrones estacionales.

Analizar la concentración de destinos.

Evaluar la influencia del tipo de cambio.

Estudiar la relación con el poder adquisitivo.

Medir sensibilidad cambiaria por destino.

Estimar un modelo econométrico exploratorio.

🗂️ Estructura del Repositorio
├── data/
│   ├── turismo_emisivo.csv
│   ├── dolar_mensual_argentinadatos.csv
│   ├── feriados_argentinadatos_2021_2025.csv
│   └── indice_salarios_datosgobar.csv
│
├── notebook/
│   └── turismo_emisivo_eda_modelo.ipynb
│
├── slides/
│   └── presentacion_turismo_emisivo.pptx
│
└── README.md

🔎 Fuentes de Datos

Dataset base de turismo emisivo (CSV provisto)

API ArgentinaDatos – Tipo de Cambio

API ArgentinaDatos – Feriados

API datos.gob.ar – Índice de Salarios (INDEC)

📊 Principales Hallazgos
✅ Estacionalidad marcada

El turismo emisivo presenta picos claros en meses de verano y períodos vacacionales.

✅ Alta concentración regional

Los destinos más visitados son países limítrofes, lo que evidencia la importancia de la proximidad geográfica y costos relativos.

✅ Estructura modal dual

Existe una combinación entre:

Turismo regional (mayormente terrestre)

Turismo internacional de larga distancia (predominantemente aéreo)

✅ Sensibilidad cambiaria heterogénea

No todos los destinos reaccionan igual ante variaciones del tipo de cambio.

✅ Impacto macroeconómico limitado en el corto plazo

Las variaciones mensuales del dólar y salarios no explican de manera contundente los movimientos mensuales de viajes.

📈 Modelo Econométrico

Se estimó un modelo OLS utilizando:

Variación % mensual del tipo de cambio

Variación % mensual del índice de salarios

Cantidad de feriados mensuales

Resultados:

Bajo R² (modelo exploratorio)

Tipo de cambio con signo esperado pero significancia limitada

Salarios no significativos en el corto plazo

Feriados estadísticamente significativos con dinámica compleja

El modelo debe interpretarse como exploratorio y no predictivo.

⚠️ Limitaciones

Posible multicolinealidad entre tipo de cambio y salarios.

Posible autocorrelación en residuos (Durbin–Watson bajo).

Datos agregados mensuales.

No se incluyen variables como ingreso real, restricciones cambiarias o conectividad aérea.

🧠 Conclusión

El turismo emisivo argentino es un fenómeno:

Estacional

Regionalmente concentrado

Modalmente dual (terrestre + aéreo)

Multidimensional

Las variables macroeconómicas influyen, pero no determinan completamente el comportamiento mensual de los viajes.

🚀 Tecnologías Utilizadas

Python

Pandas

NumPy

Matplotlib

Seaborn

Statsmodels

📌 Nota

Proyecto desarrollado como Primera Entrega del curso Data Science II – Coderhouse.
