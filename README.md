# Tipología y ciclo de vida de los datos
Asignatura Tipología y ciclo de vida de los datos del máster en Ciencia de Datos de la UOC

## Motivación del proyecto:

En Europa, el paro cardiaco es una de las primeras causas de mortalidad y en España fallecen en torno a 100 personas al día por este suceso [https://fundaciondelcorazon.com/prensa/notas-de-prensa/2900-solo-el-30-de-espanoles-sabe-realizar-la-reanimacion-cardio-pulmonar-rcp-.html], esto representa aproximadamente el 31% de las muertes a nivel mundial.

## Descripción del dataset:

El conjunto de datos ha sido extraído de Kaggle: https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset, está compuesto de 12 variables y 918 registros. Que correlacionan una serie de características recogidas de varios pacientes con la posibilidad de sufrir un ataque al corazón.
Explicación de cada variable:

- **Age:** Edad del paciente
- **Sex:** Sexo del paciente
- **ChestPainType:** Tipo de dolor torácico: Angina Típica Angina Atípica Dolor no debido a una angina Asintomático
- **RestingBP:** Presión arterial en reposo (en mm Hg)
- **Cholesterol:** Colesterol en sangre (mg/dL)
- **FastingBS:** Tiene Glucemia en ayunas > 120 mg/dl -> (1: True, 0: False)
- **RestingECG:** Resultados electrocardiográficos en reposo Value 0: normal Value 1: Tiene anormalidad de la onda ST-T (inversiones de la onda T y/o elevación o depresión del ST > 0.05 mV) Value 2 Muestra hipertrofia ventricular izquierda probable o definitiva según los criterios de Estes
- **MaxHR:** Frecuencia cardíaca máxima alcanzada
- **ExerciseAngina: Angina inducida por el ejercicio (1 = sí, 0 = no)
- **Oldpeak:** Descenso del segmento ST inducido por el ejercicio en relación con el reposo (‘Segmento ST’ se relaciona con las posiciones en el gráfico de Electrocardiograma).
- **ST_Slope:** La pendiente del segmento ST de ejercicio máximo: 0: pendiente descendente 1: plano 2: pendiente ascendente
- **HeartDisease:** Variable Objetivo: 0= menos posibilidades de infarto 1= más posibilidades de infarto.

## Descripción de los ficheros y su ubicación dentro del proyecto

