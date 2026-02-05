---
{"dg-publish":true,"permalink":"/1- Apuntes de clase/Apuntes de clase de bioestadística/","created":"2026-01-27T08:33:23.391+01:00","updated":"2026-02-04T09:24:46.929+01:00"}
---

Antes de hacer cualquier estudio es fundamental hacer una pregunta de investigación con objetivos e hipótesis. Si no tenemos pregunta no tiene sentido hacer un estudio estadístico.

- Los individuos o elementos son las personas u objetos que tienen información a analizar. *Ej: la cerveza en un control de calidad*.
- La población es un conjunto de elementos con propiedades comunes. *Ej: hipertensos*.
- La muestra es un grupo o subgrupo al que se le va a medir algo. Con esta muestra hay que conseguir poder generalizar a la población mediante la inferencia. *Ej: 50 hipertensos*.
- Las variables son los rasgos que se miden. *Ej: si fuman cada uno de estos hipertensos*.
- Modalidades: posibles valores para una característica, que es exhaustiva y excluyente. *Ej: n.º de cigarrillos al día*.
- Las clases son un conjunto de modalidades
____
### Ejercicio 1
**Población:** mujeres con síndrome metabólico
**Muestra:** 150 mujeres con síndrome metabólico
**Variables:** colesterol, peso, imc, presión arterial, etc.

____ 
Las variables pueden ser cualitativas nominales cuando no se puede poner orden (ej tipo sanguíneo), cualitativas ordinales si se pueden ordenar (bueno, muy bueno) o dicotómicas si son valores si/no (ej macho/hembra). También pueden ser cuantitativas cuando son numéricos, que pueden ser discretas (ej numero de hermanos) o continuas (ej edad).

Las variables se describen de manera distinta. Las cauntitavas con cosas como media y las cualitativas con cosas como porcentajes.

En las cuantitativas se pueden poner unos puntos de corte (ej más de 65 años para decir q es mayor)

Las transformaciones consisten en transformar variables originales en otras para facilitar su uso. *Ej: n.º paquetes -> fumador o no*.
___
### Ejercicio 2
**Pregunta:** determinar los factores de riesgos de enfermedad cardiovascular
**Población:** pacientes de diabetes II e hipercolesterolemia
**Muestra:** 838 personas con diabetes II e hipercolesterolemia
**Variable:** Sexo, edad, tabaquismo, actividad física, etc.
____
### descriptiva
Se busca obtener información de una manera global y resumida sobre la distribución de una variable, permitiéndonos una percepción, comprensión y presentación más clara de los resultados de nuestra investigación. 

En el caso de la estadística descriptiva se pone una tabla con modalidad, frecuencia absoluta (n.º), el peso (o frecuencia relativa) y porcentaje. Este método es válido para todo tipo de datos, pero en las cualitativas hay que agrupar en intervalos (o hacer x o menos/ y o más).

Todas las cualitativas se resumen en las modalidades y se dan en porcentaje. 

En estas investigaciones es MUY importante el contexto, por lo que es vital tenerlo en cuenta ("la estadística sin contexto no vale"). También es importante plantear bien la pregunta para que el encuestado no se confunda.

Una de las formas más comunes de representar variables cualitativas es el diagrama de barras. Sirve tanto para cualitativas como cuantitativas discretas. Para las cuantitativas continuas se usa el histograma.

También pueden ser útiles los gráficos de barras agrupadas para agrupar variables cualitativas.

Para representar dos variables cuantitativas se usa un gráfico de puntos.

Es muy importante poner las frecuencias absolutas en las gráficas. Muchas veces si no se pone es por engaño.

# Resumen de datos
Necesitamos medidas que nos resuman los datos de forma numérica. 

## Medidas de tendencia central
La **media** es la suma de todas las variables dividido por el número de ellas. Se aplica en variables cuantitativas para resumir los datos de las variables, aunque tiene sus restricciones. Mide la tendencia central (en las mismas unidades), representando muy bien las distribuciones simétricas, pero es muy sensible a valores extremos, por lo que no es recomendable en distribuciones asimétricas o con muchos valores atípicos (outliers). *Lo mejor es siempre usar la media.*

La **mediana** es la posición central de todos los datos ordenados de menor a mayor, es decir, que la mitad de los valores son mayores y la otra mitad son menores. Se expresa en la misma unidad que la variable, pero no está afectada por los valores que toma, dándole la ventaja de no ser afectada por valores extremos y/o atípico; por lo que es útil para datos sesgados (poblaciones asimétricas). Conviene usarlo con muestras pequeñas. 
	*Recomendación de Julián:* Todas las medidas se deben aplicar con todas las estadísticas, porque siempre se puede extraer un mínimo de utilidad. También hay que reflexionar sobre los valores durante las prácticas para que ayude en la teoría.

La **moda** es el máximo relativo de la distribución, es decir, aquella modalidad (categoría) o intervalo (clase) de mayor frecuencia absoluta.

La **simetría** busca identificar si los datos se distribuyen de forma uniforme alrededor del punto central (media aritmética), o si por el contrario, sufren algún tipo de desplazamiento o deformidad horizontal alrededor de la misma. La asimetría positiva es la acumulación de valores bajps, y la negativa la de valores altos. La asimetría afecta más a las medidas como media que la mediana. La media se mueve para la cola, separándose de la mediana.

## Medidas de dispersión
Las medidas de tendencia central normalmente deberían de ir acompañadas de medidas de dispersión. Estas medidas nos dicen lo representativas que son estas medidas de tendencia central y dan una idea de la variabilidad de los datos (uno de los conceptos más importantes de la estadística). Igual que para las cualitativas hay que poner frecuencia y porcentaje, para las cuantitativas hay que poner una medida de tendencia y otra de dispersión.

El **rango** es la resta del valor más grande y pequeño. Es fácil de calcular pero no da mucha información porque puede ser muy afectado por casos extremos y siempre aumentará (o seguirá igual) con el n.º de observaciones. Tiene valor orientativo, pero no es muy útil para la inferencia.

La **varianza** es el promedio del cuadrado de las diferencias entre cada valor y la media elevado. La **desviación típica** es su raíz cuadrada. Se suele usar la desviación típica porque usa las mismas unidades y junto a la media. La varianza siempre es positiva. No es recomendable usarla cuando la media no sea la medida de tendencia central, ya que puede ser sensible a la variación de observaciones por lo que se distorsiona si hay muchos valores atípicos. 

La desviación típica cumple que el intervalo (x̄-2s; x̄+2s) se encuentran al menos un 75% de las observaciones. Si la distribución no es muy asimétrica, este intervalo puede incluir un ~95% de los datos.

El **rango intercuartílico** (RI) es la diferencia entre el primer y tercer cuartil. Se recomienda usarlo cuando la medida de tendencia central es la mediana. Se representa mediante la diferencia de los cuartiles o mediante el intervalo definido por los cuartiles. En este intervalo se encuentra el 50% de los datos (centrales) de la variable. Análogamente, el 50% de los datos (centrales) de la variable se encuentra en un margen de 𝑅𝐼 unidades

El **coeficiente de variación** es s/x̄. El Cv no tiene unidades y no varía en los cambios de escala o unidad; y es muy útil para comparar dispersiones con distintas unidades: si el 𝑪𝒗 es mayor en una población, diremos que la variable presenta más dispersión en esa población.

Nos será de utilidad para comparar dispersiones: 
- De la misma variable medida en dos poblaciones o muestras distintas 
- De distintas variables expresadas en distintas unidades de medida 
- Cuando la dispersión pueda depender de la media
----
### Ejercicio 4
1. Observa como está representada o resumida cada variable media ± desviación típica, o frecuencia absoluta (porcentaje) según su tipo (cuantitativa, cualitativa).

2. Además de la media (y su correspondiente desviación típica), ¿de qué otra manera podríamos usar para representar variables cuantitativas?

---
## Percentiles
El percentil k (Pk) a aquel valor de la variable que deja por debajo de él al k% de los datos, y por encima al (100-k)%. Es decir el valor que queda un k por ciento por debajo de él. Un percentil especial es la mediana es el percentil P50. Cualquier valor de la variable es un percentil. 

Hay percentiles especiales llamados cuartiles (Q), donde Q1=P25; Q2=P50... y deciles (D), donde D1=P10 o D7=P70.

Los percentiles son muy útiles para ver la distribución de los valores y se usan como medidas de dispersión cuando las variables son asimétricas

## Boxplot **Importante para examen**
Un boxplot (o diagrama de caja o diagrama de caja y bigote) es una caja que represeta la mediana de los cuartiles 1 y 3. La caja contiene el 50% de los datos y los bigotes son los valores mínimos y máximos que no consideran outliers, es decir,  los valores por encima o debajo de los bigotes se consideran outliers. Nos dejan ver casi todos los valores (excepto la media).

