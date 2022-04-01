# Actividades

## Lunes - Ejercicios varios de repaso (resumen, graficos)

## Martes

#### Ejercicio 2.1

Identifique qué tipo de distribuciones de probabilidad utilizaría para las siguientes variables de respuesta. Justifique en cada caso.

a. Densidad de especies de plantas en parcelas de un bosque.

b. Probabilidad de detección de una especie de anfibio en charcas temporarias.

c. La tasa de crecimiento en pichones de una especie de ave.

d. El sexo en una especie de lagarto.

#### Ejercicio 2.2

Se estimó la prevalencia del parásito *Elaphostrongylus cervi* en ciervos colorados de granjas de España (**Tbdeer**). En cada granja (**Farm**) se muestreó un grupo  de animales (**DeerSampledCervi**) y se registró si eran positivos para la enfermedad (**DeerPosCervi**). Además, se registraron variables de hábitat, como porcentaje de áreas abiertas (**OpenLand**), arbustos (**ScrubLand**) y plantaciones de pino (**PinePlantation**), densidad de plantas y árboles de *Quercus* sp. (**QuercusPlants**, **QuercusTrees**). También se estimaron abundancias relativas de jabalí (**WildBoarIndex**) y ciervo colorado (**RedDeerIndex**), área del campo (**EstateSize**) y si el campo estaba cercado (1 = cercado, 0 = no cercado). 

- Determinar, de estas variables, aquellas involucradas en la prevalencia de la enfermedad. 

- Validar y graficar el modelo resultante.

#### Ejercicio 2.3

Simule un modelo lineal general (utilice la función *rnorm*) con dos variables (una con un efecto positivo y otra con un efecto negativo sobre la respuesta) y ajuste un modelo con las funciones *lm* y *glm*. Compare ambos modelos ¿Qué conclusión obtiene?

#### Ejercicio 2.4

Desarrolle un script para calcular el R<sup>2</sup> de Tjur utilizando el GLM binomial de Solea.txt. Corrobore el resultado con la función *r2_tjur* (paquete performance). ¿En qué situación hipotética el R<sup>2</sup> vale 0?

## Miércoles

#### Ejercicio 3.1 - Selección de modelos

#### Ejercicio 3.2

Tomando como base el set de datos **parasitos.txt** y el modelo ZAP (de dos partes o "valla") ajustado, ajuste un modelo ZAP con los mismos predictores pero de forma manual. Para esto, considere ajustar dos GLMs por separado: uno para la probabilidad de obtener un 0, y otro para la distribución de los conteos. Compare los resultados con el modelo obtenido con la función *hurdle* (paquete pscl).

#### Ejercicio 3.3

## Jueves

#### Ejercicio 4.1 - GLM conteos

#### Ejercicio 4.2 

Wingfield et al. (2017) estudiaron la dinámica espaciotemporal de *Phocoena phocoena* (Pinnipedia, Mammalia) en Maryland, Estados Unidos. Se quiere establecer en que época del año es más frecuente detectarla y los determinantes de su distribución. Para esto se realizaron muestreos durante 18 meses y se recolectó información sobre la temperatura de la superficie del agua (**SST**) y la concentración de clorofila, expresada como logaritmo (**lnCHL**). 

- Utilice un modelo que describa la dinámica temporal de la proporción de detecciones de la especie.

- Identifique qué variables se relacionan con la proporción de detecciones.

- Construya una tabla que represente los resultados principales.

- Grafique el modelo como considere más conveniente para mostrar los resultados.

- ¿Qué conclusiones obtiene en términos biológicos?


## Viernes

#### Ejercicio 5.1

Palacio et al. (2014) realizaron conteos de 44 especies de aves a lo largo de un año en 10 puntos de muestreos (**id**) localizados en un bosque de ligustro y arbustales circundantes (**habitat.type**). El set de datos corresponde a **abundancia_aves.txt**.

- Analice los factores que se relacionan con la abundancia total de individuos y con las siguientes dos especies: Tordo músico (**agebad**) y Benteveo (**pitsul**).

- Identifique claramente los efectos fijos y aleatorios incluidos en cada modelo.

- Según el problema de estudio y el modelo especificado ¿A qué tipo de diseño corresponde?

- En base a los resultados obtenidos ¿Tiene sentido incluir efectos aleatorios? Justifique.

- ¿Puede hipotetizar algo sobre la distribuciones de probabilidad utilizada para cada especie y para la abundancia total?


#### Ejercicio 5.2 - GAMM
