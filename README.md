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

#### 1. Introducción a los modelos lineales

Concepto de modelo lineal. Regresión lineal simple. Gráficos de dispersión. Correlación lineal simple: correlación producto-momento de Pearson, correlación de Spearman, matrices de correlación. Correlación y regresión lineal múltiple. Coeficientes de regresión parcial. Supuestos y transformaciones. Colinealidad, tolerancia y factores de inflación de la varianza. Variables dummy. Prueba de t, t pareado y análisis de la varianza.

#### 2. Modelos lineales generalizados (GLMs)

¿Qué es un GLM y por qué usarlos? Componentes de un GLM. La familia exponencial. Inferencia: estimación de parámetros y pruebas de hipótesis. Selección de modelos: máxima verosimilitud, devianza, prueba de Wald, chi-cuadrado de Pearson, criterios de información. Inferencia multimodelo y modelos promedio. Bondad del ajuste: chi-cuadrado de Pearson, pseudo-R2. Supuestos, diagnósticos y validación. Conteos I: GLM Poisson. Sobredispersión. GLM quasi-Poisson. Variables offset. Datos binarios y proporciones: GLM binomial. Odds, logits, clasificación y matriz de confusión. Conteos II: GLM binomial negativo, parámetro de dispersión. Conteos III: modelos truncados e inflados en ceros. Datos continuos: modelo lineal general, GLM Gamma. Reporte de tabla de resultados y gráficos.

#### 3. Modelos aditivos generalizados (GAMs)

Más allá de la linealidad: modelos no lineales. Regresión polinómica. Funciones a trozos, función escalonada. Funciones suaves univariadas: splines de regresión, de suavizado y con penalizaciones. Bases, ventanas y nodos. Parámetro de suavidad, validación cruzada generalizada. Regresión local y suavizado no paramétrico (LOESS). Modelos aditivos generalizados. Problemas de sobreajuste en un GAM. Ventajas y desventajas de un GAM. Interpretación de resultados y análisis de residuos para validar el ajuste de un GAM. Ejemplos prácticos en ecología. Modelos semiparamétricos y de suavizado bidimensional. Reporte de tabla de resultados y gráficos.

#### 4. Modelos mixtos

Definición de efectos fijos y efectos aleatorios. Modelo mixto para datos anidados: método de los dos pasos. Modelo lineal general mixto. Modelo de intercepto aleatorio. Modelo de intercepto y pendientes aleatorios. Máxima verosimilitud restringida. Modelo lineal generalizado mixto (GLMM) y modelo aditivo generalizado mixto (GAMM). Bondad del ajuste y R2. Significancia de coeficientes y selección de modelos. Bootstrapping. Diseños experimentales en bloques aleatorizados, anidados, parcelas divididas (split-plot) y medidas repetidas. Estructuras de correlación espacial, temporal y filogenética. Interpretación de efectos fijos y aleatorios. Análisis de residuos y validación. Utilidad y limitaciones de los modelos mixtos. Reporte de tabla de resultados y gráficos.

## Modalidad del curso

El curso será de forma presencial y se trabajará de forma íntegra con la interfaz RStudio. Todos los scripts, bases de datos, actividades, diapositivas y bibliografía sugerida (sólo artículos científicos) se encuentra en este repositorio. Los alumnos y alumnas deberán tener instalado tanto R como Rstudio (versión 4.0.2 o posterior), así como los paquetes que se listan a continuación, previo al comienzo del curso:

car

DHARMa

equatiomatic

fields

glmmTMB

gratia

ggplot2

gstat

Hmisc

itsadug

lattice

lme4

lmtest

MASS

mgcv

multcomp

MuMIn (se lee "mumin")

nlme

palmerpenguins

performance

plot3D

pscl

psych

sjPlot

sp

splines

VGAM

visreg


## Bibliografía

Burnham KP y DR Anderson. (2004). Model selection and multi-model inference. A practical information-theoretic approach. Springer-Verlag.

Burnham KP, DR Anderson y KP Huyvaert. (2011). AIC model selection and multimodel inference in behavioral ecology: some background, observations, and comparisons.     Behavioral Ecology and Sociobiology 65: 23-35.

Crawley MJ. (2012). The R book. Wiley-Blackwell.

Faraway JJ. (2006). Extending the linear model with R. Generalized linear, mixed effects and non-parametric regression models. Chapman & Hall/CRC

Grueber CE, S Nakagawa, RJ Laws e IG Jamieson. (2011). Multimodel inference in ecology and evolution: challenges and solutions. Journal of Evolutionary Biology 24: 
699-711.

James G, D Witten, T Hastie y R Tibshirani. (2013). An introduction to statistical learning. Springer.

Harrison XA, L Donaldson, ME Correa-Cano, J Evans, DN Fisher, CE Goodwin, BS Robinson, DJ Hodgson y R Inger. (2018). A brief introduction to mixed effects modelling 
and multi-model inference in ecology. PeerJ 6: e4794.

Logan M. (2010). Biostatistical design and analysis using R. A practical guide. Wiley-Blackwell.

Nakagawa S y H Schielzeth. (2013) A general and simple method for obtaining R2 from generalized linear mixed‐effects models. Methods in Ecology and Evolution 4: 133-
142.

Palacio FX. (2018). Advocating better habitat use and selection models in bird ecology. Revista Brasileira de Ornitologia 26: 90-104.

Pedersen EJ, DL Miller, GL Simpson y N Ross. (2019). Hierarchical generalized additive models in ecology: an introduction with mgcv. PeerJ 7: e6876.

Quinn G y M Keough. (2002). Experimental design and data analysis for biologists. Cambridge University Press.

Zuur AF. (2012). A beginner's guide to generalized additive models with R. Highland Statistics Limited.

Zuur AF y EN Ieno. (2016). A protocol for conducting and presenting results of regression‐type analyses. Methods in Ecology and Evolution 7: 636-645.

Zuur AF, EN Ieno y CS Elphick. (2010). A protocol for data exploration to avoid common statistical problems. Methods in Ecology and Evolution 1: 3-14.

Zuur A, EN Ieno y GM Smith. (2007). Analyzing ecological data. Springer.

Zuur A, EN Ieno, NJ Walker, AA Saveliev y GM Smith. (2009). Mixed effects models and extensions in ecology with R. Springer.


*Nota: si detecta algún error o problema, contactarse al siguiente correo: facundo_palacio@fcnym.unlp.edu.ar*
