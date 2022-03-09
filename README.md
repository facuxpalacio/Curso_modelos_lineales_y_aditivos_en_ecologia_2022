# Curso de posgrado: Modelos lineales y aditivos en ecología

Docente a cargo: Dr. Facundo Xavier Palacio, Universidad Nacional de La Plata.

Colaborador docente:  Dr. Mariano Ordano, Instituto de Ecología Regional y Universidad Nacional de Tucumán.

Coordinadora académica: Dr. Romina D. Fernández, Instituto de Ecología Regional y Universidad Nacional de Tucumán.

Fecha: del 2-5-22 al 6-5-22

Facultad de Ciencias Naturales e Instituto Miguel Lillo, Universidad Nacional de Tucumán.


## Destinatarios
Graduados universitarios y profesionales de ciencias biológicas y carreras afines (ciencias ambientales, agronomía, veterinaria, biotecnología). Se requieren conocimientos básicos de estadística y manejo del software R.

## Objetivos
1. Favorecer la comprensión de la aplicación de modelos lineales vs. no lineales en ecología.
2. Brindar las herramientas teórico-prácticas que permitan abordar y resolver problemas de índole estadístico que involucren el uso de modelos lineales y aditivos.
3. Capacitar a los alumnos para realizar una rutina de análisis de los modelos estudiados con el software R.
4. Contribuir al conocimiento de los alumnos sobre el funcionamiento del software R para usarlo de forma autónoma y efectiva.

## Contenidos:

1. Introducción a los modelos lineales
Concepto de modelo lineal. Regresión lineal simple. Gráficos de dispersión. Correlación lineal simple: correlación producto-momento de Pearson, correlación de Spearman, matrices de correlación. Correlación y regresión lineal múltiple. Coeficientes de regresión parcial. Supuestos y transformaciones. Colinealidad, tolerancia y factores de inflación de la varianza. Variables dummy. Prueba de t, t pareado y análisis de la varianza.

2. Modelos lineales generalizados (GLMs)
¿Qué es un GLM y por qué usarlos? Componentes de un GLM. La familia exponencial. Inferencia: estimación de parámetros y pruebas de hipótesis. Selección de modelos: máxima verosimilitud, devianza, prueba de Wald, chi-cuadrado de Pearson, criterios de información. Inferencia multimodelo y modelos promedio. Bondad del ajuste: chi-cuadrado de Pearson, pseudo-R2. Supuestos, diagnósticos y validación. Conteos I: GLM Poisson. Sobredispersión. GLM quasi-Poisson. Variables offset. Datos binarios y proporciones: GLM binomial. Odds, logits, clasificación y matriz de confusión. Conteos II: GLM binomial negativo, parámetro de dispersión. Conteos III: modelos truncados e inflados en ceros. Datos continuos: modelo lineal general, GLM Gamma. Reporte de tabla de resultados y gráficos.

3. Modelos aditivos generalizados (GAMs)
Más allá de la linealidad: modelos no lineales. Regresión polinómica. Funciones a trozos, función escalonada. Funciones suaves univariadas: splines de regresión, de suavizado y con penalizaciones. Bases, ventanas y nodos. Parámetro de suavidad, validación cruzada generalizada. Regresión local y suavizado no paramétrico (LOESS). Modelos aditivos generalizados. Problemas de sobreajuste en un GAM. Ventajas y desventajas de un GAM. Interpretación de resultados y análisis de residuos para validar el ajuste de un GAM. Ejemplos prácticos en ecología. Modelos semiparamétricos y de suavizado bidimensional. Reporte de tabla de resultados y gráficos.

4. Modelos mixtos
Definición de efectos fijos y efectos aleatorios. Modelo mixto para datos anidados: método de los dos pasos. Modelo lineal general mixto. Modelo de intercepto aleatorio. Modelo de intercepto y pendientes aleatorios. Máxima verosimilitud restringida. Modelo lineal generalizado mixto (GLMM) y modelo aditivo generalizado mixto (GAMM). Bondad del ajuste y R2. Significancia de coeficientes y selección de modelos. Bootstrapping. Diseños experimentales en bloques aleatorizados, anidados, parcelas divididas (split-plot) y medidas repetidas. Estructuras de correlación espacial, temporal y filogenética. Interpretación de efectos fijos y aleatorios. Análisis de residuos y validación. Utilidad y limitaciones de los modelos mixtos. Reporte de tabla de resultados y gráficos.

## Modalidad del curso

El curso será de forma presencial y se trabajará de forma íntegra con la interfaz RStudio. Todos los scripts, bases de datos, actividades, diapositivas y bibliografía sugerida se encuentra en este repositorio. Los alumnos y alumnas deberán tener instalado tanto R como Rstudio, así como los paquetes que se listan a continuación, previo al comienzo del curso:

DHARMa

equatiomatic

lmtest

MASS

multcomp

performance

pscl

VGAM

visreg

pscl
