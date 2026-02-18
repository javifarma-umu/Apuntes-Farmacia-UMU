---
{"dg-publish":true,"permalink":"/2 - Wikifarma/traducción/","tags":["bioquimica"],"created":"2026-02-08T16:57:50.225+01:00","updated":"2026-02-18T18:12:50.785+01:00"}
---

# Código genético
El [aminoácido](aminoácidos) es la subunidad de la [[2 - Wikifarma/proteína\|proteína]] y corresponde a un **triplete** (o codón) de nucleótidos de un ARNm. Esta correspondencia se llama código genético y ocurre gracias al aminoacil-tRNA. El **código genético** es el lenguaje vinculante de los ácidos nucleicos y polipéptidos. Se trata de un código universal, con 61 tripletes con sentido y 3 sin sentido (o de stop), esta abundancia supone que varios tripletes pueden sintetizar el mismo aminoácidos (degenerado o sinónimo). Solo hay 2 aa sin sinónimo (Met y Trp). El código genético no presenta ambigüedades, es decir, un triplete no puede codificar para dos aa distintos.

En el mensajero maduro hay 2 regiones que no se traducen (UTR5’ y UTR3’). Al principio había varias hipótesis de lectura: solapada y no solapada; pero al final se concluyó que la lectura no era solapada. La secuencia AUG indica el inicio del **marco abierto de lectura** (ORF) y supone el final de la secuencia UTR5’. 

En programas como Ensembl, la secuencia de los intrones o secuencias intergénicas se representan en minúscula y en la base de datos se representan incompletas; mientras que la de los exones están en mayúscula, con las regiones UTR de color naranja y las codificantes en azul. En programas informáticos el orden de lectura se ve indicado por una flecha, los intrones son líneas rectas y los exones son rectángulos (que son huecos en las UTR). Como el ADN humano es **monocistriónico**, solo sintetiza 1 proteína.

# Lectura del ORF
## Eucariotas
El marco de lectura comienza con un AUG embebido en una secuencia llamada **secuencia de Kozak**, que tiene, entre otros, un AUG inicial, un A en -3, y un G en +4. Se modula el número de proteínas a sintetizar dependiendo de lo “fuerte” que sea su contexto de Kozak.

## Procariotas
En los procariotas el [ARN](ácidos%20nucleicos#ARN) es policistriónico (un ARNm lleva varios genes), sin secuencias intergénicas, no tienen caperuza y muchos ribosomas se unen al sitio de inicio y secuencian proteínas a la vez (normalmente estas cooperan en una misma ruta metabólica). 

En el caso de los genes policistriónicos, no hay secuencia de Kozak, sino varios **RBS** (ribosome binding site), que es complementaria a la secuencia 3’ de la subunidad pequeña del ARNr y hay una por cada proteína que tiene el gen. Cuando el ARNr se une al **RBS** (o secuencia de Shine-Dalgarno) comienza a leer la cadena y empieza a sintetizar en el primer AUG.

# ARN transferente
Aparte del ARNm, en la biosíntesis también participan el ARNr y ARNt. La unidad funcional es aminoacil tRNA.

Los ARNt son secuencias cortas monocatenarias que adoptan una forma de hoja de trébol con 3 o 4 lazos con extremos cortados con una secuencia CCA en el extremo 3’ (brazo aceptor).  Estructuralmente, tiene 4 asas llamadas asa D, asa anticodón asa variable y asa ψ.

Tridimensionalmente, forman una hélice invertida, con el asa ψ y D adoptando una forma helicoidal enrollada entre sí porque existen muchos grupos de contacto en ambas asas y acabando formando (en visión bidimensional) una L invertida donde el triplete anticodón tiene movilidad en la bases en el extremo 5’ (base móvil) y bases apiladas y rígidas en el extremo 3’. 

Que la base 5' sea fluctuante permite que el aminoacil ARNt se una no solamente al codón (base canónica) pero también a otras bases no canónicas (**teoría de balanceo**). Esto hace que no tengan que haber 61 ARNt distintos, sino 31, dándole redundancia al ADN, ya que se une a los aa dependiendo del anticodón. Para determinados aminoácidos hay ARNt isoaceptores (que aceptan el mismo aa) debido a la degeneración del código genético. 

## Formación del aminoacil ARNt
La unión entre tRNA y aa la llevan a cabo aminoacil-tRNa sintetasa, de las que hay 20 (1 por cada aa). La enzima distingue entre el aa y se reconoce el anticodón tRNA; luego une el aa al brazo aceptor (3') del ARNt. 

Son muy específicas (1 error por cada 10000 cargas) gracias a que tienen una actividad correctora, donde si la carga del aminoácido al ARNt no es buena se libera el aa. Esta carga lleva un gasto energético importante (2ATP/carga) con dos etapas importante: 
- En la 1ª el carboxilo se une al fosfato, liberando un pirofosfato y creando un aminoácido adenilado.
- En la 2ª fase se forma un enlace éster entre el carboxilo y el brazo aceptor del ARNt, liberando un AMP.

# Ribosoma
Estructuralmente, el [[2 - Wikifarma/ribosoma\|ribosoma]] es una partícula ribonucleoproteíca con una subunidad pequeña y otra grande. En el citosol de las eucariotas (y protoplasma procariota) hay ribosomas, que se encargan de sintetizar proteínas. Este proceso (al igual que todos los procesos biosintéticos) requieren aporte energético, que es de ~80% del total de la célula. En este proceso intervienen ~100 proteínas. 

Cuando el triplete mensajero es complementario al anticodón, se acopla el aminoacil-ARNt. Cuando se unen las 2 subunidades ribosomales (primero el pequeño luego el grande) se forman 3 cámaras: E (exit), P (peptidina) y A (aminoacilo); que ocupa un triplete cada uno. En el E está el ARNt vacío listo para liberarse, en el P está el aa uniéndose a la cadena y en el A está el aa siguiente. La subunidad grande es el centro de transferencia y el pequeño el centro decodificador. 

Cada vez que se da una unión se provoca un movimiento de un triplete, a una velocidad de 20aa/s en procariotas y 2aa/s en eucariotas. El ARNm está enroscado con la caperuza cerca de la cola poliA. Para cada mensajero hay varios ribosomas traduciendo a la vez, formando polisomas para optimizar los recursos de la célula. 

También se aprovechan recursos con el “ciclo del ribosoma”, donde cada ribosoma se reutiliza, aprovechándose de que tridimensionalmente el extremo 3’ está muy cerca del 5’ para que el ribosoma liberado vuelva a empezar el ensamblaje.

# Proceso de transcripción
La subunidad grande es la responsable de la actividad catalítica de **transpeptidación**, es decir, es la que posibilita el enlace peptídico de dos aa. La incorporación de un aminoacilo nuevo se da por la rotura del enlace del peptidilo con el 3’ del tRNA, que es atacado por la amina del aminoacil-tRNA siguiente, formando el enlace peptídico. Así se queda un tRNA vacío en P y el aminoacil unido en N en A, por lo que el ribosoma tiene que moverse (**translocación**). En cada ciclo de elongación se produce un gasto de 2 GTP.

*EJEMPLO:* una proteína de 500 aa requiere un gasto de 1000 ATP para formar los aminoacil-ARNt y otros 1000 para los enlaces peptídicos (sin contar con otros gastos energéticos). Este gasto se da porque el gasto energético le merece la pena a la célula para disminuir la entropía.

El proceso de reclutamiento de los IF (factores de iniciación) y ensamblaje del ribosoma es muy complejo. Se requiere una estructura circular en el ARNm, que es reconocida por las IF:
- **eIF-1**: bloquea el sitio A de la subunidad menor
- **eIF-2**: une GTP y tiene actividad GTPasa
- **eIF-3**: bloquea el sitio E en la subunidad menor
- **eIF-4**: une el ARNm con interacciones entre caperuza y cola poliA

Los IF marcan el mensajero para la traducción. La subunidad pequeña forma un complejo con las IF, que son responsables de iniciar la síntesis en AUG. Cabe destacar el IF-2, que lleva un GTP tRNA-Met . Cuando el aminoacil de metionina hace “click”, se liberan las IF y comienza la síntesis y es el único aa que entra por el sitio P. 

La liberación se da cuando hay un codón de STOP, para la no hay ARNt aa, sino un RF (factor de liberación), que es la eRF en eucariotas o en procariotas las RF1, RF2 y RF3. En la liberación, la transpeptidasa promueve la hidrólisis del GTP y disloca la maquinaria.

# Antibióticos inhibidores de la traducción
- **Estreptomicina:** Aminoglicósido bacteriano que se une a la subunidad menor del ribosoma para impedir el inicio y elongación.
- **Tetraciclina:** De origen bacteriano o sintético, es derivado del nícleo tetracícilico que se une al sitio A de la subunidad menor para impedir la elongación.
- **Cloranfenicol:** Puede ser de origen bacteriano o sintético. Impide la elongación al unirse a la subunidad mayor e inhibir la transpeptidasa bacteriana.
- **Ciclohexamida:** De origen bacteriano, se une a la subunidad mayor para inhibir la transpeptidasa eucariota, inhibiendo la traducción.
- **Puromicina:** Es un aminonucleósido bacteriano que hace de análogo estructural al ARNt, enlazándose con el péptido y causando una terminación prematura (inhibe la elongación).