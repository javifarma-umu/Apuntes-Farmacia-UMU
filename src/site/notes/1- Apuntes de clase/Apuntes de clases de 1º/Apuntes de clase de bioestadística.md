---
{"dg-publish":true,"permalink":"/1- Apuntes de clase/Apuntes de clases de 1º/Apuntes de clase de bioestadística/","created":"2026-01-27T08:33:23.391+01:00","updated":"2026-04-14T09:24:11.479+02:00"}
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
Un boxplot (o diagrama de caja o diagrama de caja y bigote) es una caja que representa la mediana y los cuartiles 1 y 3. La caja contiene el 50% de los datos y los bigotes son los valores mínimos y máximos que no consideran outliers, es decir,  los valores por encima o debajo de los bigotes se consideran outliers. Nos dejan ver casi todos los valores (excepto la media).
___
### Ejercicio
Identifica muestra y población 
36 pacientes de hemodialisis; pacientes de hemodialisis con COVID

b. Identifica las variables y sus modalidades presentadas en las filas de la Tabla 1. 
Supervivientes (dicotómica)
c. Observa como se resumen los datos de las variables 

d. Comenta los resultados de alguna variable:

---
# Probabilidad
**FALTÉ A ESTO**
## Test de diagnóstico
Una prueba que se usa para detectar una enfermedad. Estas pruebas no son perfectas, existen falsos positivos y falsos negativos. Luego se confirma con un "gold standard" *ej cribado de cancer de mama, que luego se confirma con una biopsia*. Pueden servir para descubrir, confirmar o descartar una enfermedad. El truco está en combinar distintas pruebas. Tiene distintos parámetros:
- **Validez:** lo sensible y específico que es un test. Normalmente se compara con el gold standard. Se mide con probabilidades condicionadas
- **Capacidad predictiva:** capacidad de detectar un sano en negativo o un enfermo con positivo. Son probabilidades condicionadas.

**Sensibilidad:** la porbabilidad de que el test sea positivo si está enferma
**Especifidad:** probabilidad de que de negativo cuando es sano

También se obtienen tasas de falsos positivos y de falsos negativos

Una prueba muy sensible tiene pocos falsos negativos, por lo que identifican bien a enfermos. Sirve para hacer cribados. Pueden haber falsos positivos, pero se contrasta con el gold standard. Es util ante enfermedades graves que necesitan diagnostico.

Mientras la sensibilidad y especifidad miden la validez, los valores predictivos miden la capacidad predictiva.
- **Valor predictivo positivo**: De los positivos, cuales son verdaderos positivos.
- **Valor predictivo negativo**: De los negativos, cuales son verdaderos negativos.

La prevalencia es la probabilidad o frecuencia de una enfermedad. **Los valores predictivos cambian con la prevalencia** de la enfermedad. Por ejemplo, con un test de sensibilidad y especifidad alta, el v+ sube mucho (no hay FP) y el v- baja (más FN); y cuando hay muy poca prevalencia lo contrario. Esto se justifica con el teorema de Bayes. Como resultado, el valor predictivo es muy dependiente del **contexto**. La precisión es el porcentaje de aciertos ((VP+VN)/total).

**Test de diagnóstico comunes en farmacia en la diapositiva**

Para un test que funciona bien "para todo" hay que sumar la sensibilidad y especifidad. La suma de s y e restando 1 se llama índice de Younden

# Probabilidad tema2 (creo)
**Variable aleatoria:** una variable asignada a un experimento aleatorio que tiene un valor numerico para cada suceso. Puede ser ds¡iscreta si puede tomar un numero finito de valores o continua si puede tomar una cantidad infinita de valores. Para transformar una cualitativa en una cuantitativa (para hacerla aleatoria) en Rcommander se "codifica" una variable cualitativa, dandole valor numerico a cada estado.

Hay que diferenciar el **parámetro y estadístico**. El estadístico es la cantidad numérica obtenida a partir de los valores o datos de una muestra. Pretende resumir la información de todos esos valores. Es un valor empírico (se puede calcular). Cuando se trata de datos de la población se usa **parámetro**. Para la metra la media, varianza y proporción son 𝑥, 𝑠^2 y p. Mientras que en el parámetro es 𝜇, 𝜎 2 y π. En resumen, e estadístico es obtenida a partir de datos observados de la muestra, mientras que el estadístico son datos teóricos sobre la población. A medida que sube el tamaño de muestra, más se parece el estadístico al parámetro.

Para una variable aleatoria discreta 𝑋, la asignación de cada posible valor 𝑥𝑖 (sucesos elementales de un espacio muestral) a la probabilidad de que suceda, es a lo que llamamos distribución de probabilidad de la variable X.

Las distribuciones no tienen por qué ser normales. La existencia o no de esta distribución normal normalmente dicta la inferencia. El fondo de densidad *f* es el área bajo la curva en el rango de datos que queremos. Muchas veces hay que tipificar para aproximar la distribución real a la distribución normal.

El objetivo final es contruir modelos de probabilidad que fueran capaces de representar el comportamiento teórico de diferentes fenómenos aleatorios observados en el mundo real. Vienen descritas por 1 o más parámetros que se pueden definir y describir libremente. Conociendo estos parámetros se puede definir y describir perfectamente esta distribución. Si usamos un método inferencial en el que asumimos que los datos de una muestra pertenecen a una población con una distribución teórica conocida, suele decirse que dicho método es **paramétrico**.

**BINOMIAL EN LAS DISPOSITIVAS**

La distribución normal es simétrica y coincide la media, mediana y moda **COMPLETA EN LOS APUNTES**

Hay más tipos de distribuciones en la inferencia aparte de la normal y binomial. 

La **t de student** depende de los grados de libertad y tiene muchas distintas. Es parecida a la normal y se va asemejando cada vez más mientras aumentan los grados de libertad (k). Se suele usar con muestras pequeñas. "Si conocemos la distribución conocemos de todo".

**Chi cuadrado** es una distribución asimétrica que se va haciendo más simétricas con más geados de libertad. También existe el F de Reynolds

# Muestreo y estimación
Se coge una porción de la población para inferir el resto. Hay distintos tipos de muestreo, cada uno con sus ventajas y dificultades.

- **Precisión:** Es la variación/dispersión de los datos. Algo válido pero no preciso tendrá un error **aleatorio**.
- **Validez:** Asegura que se está midiendo lo deseado. Algo preciso pero no válido tendrá un error **sistemático** (sesgo).

El error aleatorio puede ser causado por azar de no obtener una muestra representativa, un tamaño muestral inadecuado, mala técnica de muestreo (no probabilístico) o variabilidad en la medición (o por el instrumento o variedad natural de los elementos de estudio).

El error sistemático se puede tener varias formas:
- **Selección:** la selección es inadecuada y produce una muestra no representativa
- **Información:** la medición de variables se ha hecho de manera deficiente
- **Factores de confusión:** correlación no es igual a causa. *Ej: el café no produce cáncer pero los que consumen café tienen más cáncer porque los que toman café suelen fumar también*.
El error sistemático no se corrige con el tamaño muestral, sino e cambi de técnica de muestreo, análisis estadóstoco y diseño del estudio. Hay que determinar un objetivo claro y definir criterios de exclusión.

## Muestreo
Hay de distintos tipos:
- **Intencional:** Se trata de seleccionar casos característicos (que convengan al investigador) de una población limitando la muestra sólo a estos casos. Puede ser poco válido.
- **Por conveniencia:** Se seleccionan aquellos casos accesibles (proximidad de los sujetos para el investigador y que acepten ser incluidos). Puede ser poco válido
- **Aleatorio simple:** Es un muestreo probabilístico donde los elementos de la muestra se extraen al azar de la población, por tanto, se caracteriza porque cada elemento de la población tiene la misma probabilidad de ser elegido. Se escoge aleatoriamente un número determinado de sujetos de un listado de la población que compondrían la muestra.
- **Aleatorio estratificado:** Se divide la población en estratos atendiendo a los criterios importantes del estudio. Los estratos son homogéneos pero heterogéneos entre sí.
- **Por conglomerados:** Se divide la población en conglomerados heterogéneos pero homogéneos entre sí. Se hacen conglomerados que tengan un poco de todo pero son iguales entre ellos, y luego se pilla uno al azar.

Algunos problemas pueden ser la dificultad en la obtencion de datos, que lleva a un muestreo no probabilístico; no tener claro el objetivo inicial que lleva a una definición ambigua de la población; o desconocer las variables de interés, factores de precisión y desconocer las limitaciones del instrumento de medida.

---
Un **estimador puntual** es un estadístico que toma valores próximos al parámetro. Es construido con el fin de dar una idea acerca del valor que toma ese parámetro dentro de una población.

Un estimador puntual se obtiene a partir de los valores de una muestra (es un estadístico). Sin embargo, si tomamos varias muestras (supongamos 𝑚 muestras), tendremos un valor para nuestro estimador (posiblemente distinto) en cada una de las 𝑚 muestras. Esta variación muestral sugiere que nuestra estimación puntual puede aproximarse, pero no será exactamente igual al parámetro.


## Obtención de un intervalo
La **estimación por intervalos de confianza** nos da un rango de valores posibles para el parámetro.

Para dar un intervalo se sacan una gran cantidad de muestras y se hace una media de las medias de las muestras llamada **media muestral** (μ) y se da un rango de medias posibles. Las medias forman una distribución normal.

El objetivo es encontrar un intervalo (rango de valores) donde aseguremos, con una probabilidad prefijada que supondremos suficientemente alta, que en su interior se encontrará el parámetro que pretendemos estimar.

Dado 𝜶 (nivel de confianza), llamaremos intervalo de confianza con nivel de confianza del (𝟏 − 𝜶)% para un parámetro 𝜽, a un intervalo 𝐼 tal que la probabilidad de que el verdadero valor del parámetro esté contenido en dicho intervalo sea (1 − α). Cuanto mayor es la confianza, menor es la precisión de los datos dados, por lo que el estándar es α = 0,05 (confianza del 95%).

![Pasted image 20260304091003.png|300](/img/user/6%20-%20Fotos/Pasted%20image%2020260304091003.png)

![Pasted image 20260304091236.png](/img/user/6%20-%20Fotos/Pasted%20image%2020260304091236.png)

**EN INFERENCIA, SIEMPRE HAY UN RIESGO DE ERROR** para paliar esto, se busca que el estudio se repita por varios equipos.

### Factores e interpretación de los IC
Si hay mucha variabilidad hay menos seguridad de los valores (precisión).

El error máximo se da cuando p=0,5

![Pasted image 20260305090754.png](/img/user/6%20-%20Fotos/Pasted%20image%2020260305090754.png)

Antes de hacer un estudio hay que decidir el tamaño de muestra, que se marca por la pregunta y objetivo

**INCOMPLETO HASTA LA DIAPOSITIVA 58**

# Tema 5 - Contraste de hipótesis
![Pasted image 20260312085311.png](/img/user/6%20-%20Fotos/Pasted%20image%2020260312085311.png)
![Pasted image 20260312090024.png](/img/user/6%20-%20Fotos/Pasted%20image%2020260312090024.png)

Si se obtiene una media de una muestra (estadístico de contraste), el p valor es la posibilidad de que el parámetro de media hipotetizado se cumpla. Cuando p-valor es mayor al nivel de significación (alfa), se cumple H0, y cuando no, H1.

---
### Ejercicio plantear contrastes
- Los estudiantes de ciencias sociales y artes usan menos psicoestimulantes
--- 
Hay diferencias entre clinicamente relevante y estadisticamente significativo.
## Contraste de hipótesis: 2 distribuciones proporción
Se coge un caso de 2 muestras dependientes *ej: un grupo de oesos ates y después de tratamiento con GLP-1*. Buscamos que la πpre=πpost es H0 y si no, H1. Se hace un chi cuadrado. **En Rcommander se estudia el intervalo de confianza de las diferencias**. 

# Bloque 6: Regresión y ANOVA
Se busca la relación de 2 variables cuantitativas

El coeficiente de correlacion coincide con el signo de la pendiente de la recta. El coeficiente de determinación nos da la magnitud de asociación. El coeficiente de correlación es R y el coeficiente de determinación es R^2, por lo que con R podemos sacar R^2, pero de R^2 no se puede obtener R, ya que no sabriamos el signo. Ambos se sacan con la pendiente de la recta

El error tipo 1 se da por el alfa y el error tipo 2 normalmente se da por el tamaño de la muestra