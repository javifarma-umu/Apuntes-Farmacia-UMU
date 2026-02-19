---
{"dg-publish":true,"permalink":"/2 - Wikifarma/replicación/","tags":["bioquimica"],"created":"2026-02-07T19:01:26.581+01:00","updated":"2026-02-19T17:16:13.328+01:00"}
---

# Generalidades
La replicación es la biosíntesis de una nueva copia de [ADN](ácidos%20nucleicos#ADN) a partir de una copia anterior. Este proceso solo ocurre en la fase S del [[2 - Wikifarma/ciclo celular\|ciclo celular]] (la cadena molde debe estar en fibra de 10nm y deslizado) gracias a la actividad de varias [enzimas](enzima), sobre todo al ADN polimerasa.  La replicación va en sentido 5'->3’ y es semiconservativa, por la que una es molde y otra es nueva. 

Hay una nueva cadena que se sintetiza de manera continua (conductora) y otra que se sintetiza de manera semidiscontinua en **fragmentos de Okazaki** (retardada). Al estar el ADN desnaturalizado, se abren las dos hebras formando una **horquilla de replicación** (parte sujeta), que es bidireccional a partir de el origen de replicación. Un **replisoma** está compuesto por la horquilla (con su helicasa y topoisomerasa), ADN polimerasa, el molde, el primer (sintentizado por la primasa) y el ADN ligasa. 

# Maquinaria de replicación
Para la elongación de la cadena nueva, hace falta:
- ADNpol  
- Una monocadena molde
- Nucleótidos trifosfatados (dNTPs)
- Un primer. 

## ADN polimerasa
Cuando se establece el enlace para polimerizar el ADN, se liberan 2 fosfatos con ayuda de la pirofosfatasa para liberar energía e impulsar la reacción; y solo permanece el fosfato α. Existen muchos tipos de polimerasas dependiendo de lo que usen de molde (ADN o ARN) y de la molécula que sinteticen (ADN o ARN):

| **Molde** | **Molécula sintetizada** | **Nombre común**                    |
| --------- | ------------------------ | ----------------------------------- |
| ADN       | ADN                      | ADN polimerasa                      |
| ADN       | ARN                      | Primasa<br>ARN polimerasa           |
| ARN       | ADN                      | Transcriptasa inversa<br>Telomerasa |
| ARN       | ARN                      | ARN replicasa                       |


Cuando nos referimos al ADN nuclear, las polimerasas responsables de la replicación son las alfa (α), delta (δ) y épsilon (ε), pero también existe la gamma (γ) en la mitocondria y otras como la beta (β) que se encargan de la reparación.  

La gran mayoría de ADN polimerasa tienen una estructura rica en hélices alfa que recuerda a una mano semiabierta. Muchas ADN polimerasas son proteínas multifuncionales que tienen también actividad nucleasa, rompiendo el enlace fosfodiéster entre dos nucleótidos mediante la hidrólisis. Gracias a esta capacidad hidrolítica la polimerasa corrige los errores en la replicación, reduciendo su ya baja tasa de error. Se tratan de exonucleasas que cortan en dirección 3’->5’ y son las responsables de cortar el cebador. 

Los distintos tipos de ADNpol pueden tener funciones distintas:

|                                      | **I**      | **II**     | **III**    | **α**             | **δ**              | **ε**  | **β**  | **γ**       |
| ------------------------------------ | ---------- | ---------- | ---------- | ----------------- | ------------------ | ------ | ------ | ----------- |
| **Localización**                     | procariota | procariota | procariota | núcleo            | núcleo             | núcleo | núcleo | mitocondria |
| **Primasa**                          | no         | no         | no         | si                | no                 | no     | no     | no          |
| **Polimerasa**                       | si         | si         | si         | si                | si                 | si     | si     | si          |
| **3' exonucleasa** (correctora)      | si         | si         | si         | no                | si                 | si     | no     | si          |
| **5' exonucleasa** (eliminar primer) | si         | no         | no         | no                | no                 | no     | no     | no          |
| **Síntesis de hebra**                | no         | no         | si         | solo inicialmente | si                 | si     | no     | si          |
| **Empalme de fragmentos de okazaki** | si         | no         | no         | no                | si (con nucleasas) |        | no     | si          |

La ADN polimerasa α se encarga de sintetizar el primer (ARN primasa) y además es ADN polimerasa, formando ADN ini de unos 100 nucleótidos. Las más importantes en el proceso de duplicación son las δ ε, que alargan las cadenas (ε la forward y δ la reversa); y la gamma puede empalmar los fragmentos de Okazaki.

Las polimerasas tienen una velocidad muy alta (hasta 1000 nucleótidos/s en ADN polimerasa III y 90000 nucleótidos/s en gamma y épsilon). Además, este proceso es bidireccional y multifocal (excepto procariotas), es decir, hay muchos focos replicativos del que salen 2 horquillas que avanzan en direcciones opuestas, haciendo que la fase S dure de 6 a 8 horas. Otro factor importante es la procesividad (nº de ciclos catalíticos antes de separarse por su molde). 

## Abrazadera deslizante
Una cosa que **ayuda a aumentar la procesividad** es la abrazadera deslizante (PCNA), una proteína de 3 subunidades idénticas en forma de anillo que impide que la polimerasa se separe, abrazando el ADN, dejando espacio para unas pocas moléculas de agua para poder deslizarse.

La ADN polimerasa III tiene una doble dotación de la enzima núcleo que tiene dos subunidades α, ԑ, δ, θ y τ; que se unen por la subunidad α a una abrazadera, que está compuesta por subunidades β, que se une a una subunidad llamada **complejo cargador de la abrazadera**. 

## Proteínas adicionales
Un replisoma está formado por las proteínas que sintetizan las dos hebras. Consta de las ADN polimerasa, que están sujetas a la plantilla por su abrazadera deslizante y un complejo cargador de la abrazadera que une a las dos; las helicasas; y la topoisomerasa. 

Las **proteínas de unión a monocadena** (RPA) son unas proteínas que hacen un papel de escudo frente a las nucleasas; participan uniéndose en la bifurcación de la horquilla de replicación y se van desplazando. 

Para desenrollarse, se necesita la **helicasa**, que avanza en dirección a la horquilla, desenrollando la doble hélice. El problema es que este desenrollamiento produce un superenrollamiento, que genera tensión por torsión, por lo que se requiere la **topoisomerasa**, que se encarga de eliminar las tensiones. La helicasa desenrolla en sentido 5’->3', produce superenrollamiento y necesita ATP. La topoisomerasa tiene función endonucleasa y polimerasa: cortan, desenrollan (un poco de más para compensar la torsión) y vuelven a empalmar.

# Proceso de replicación
La replicación comienza en los orígenes de replicación, que suelen ser ricas en pares AT frente CG (secuencias replicador), ya que tienen menos puentes de hidrógeno. Constan de un par de docenas de nucleótidos, que son reconocidos por proteínas **ORC** (complejo de reconocimiento del origen), uniéndose y reclutando las proteínas Cdc8 y Cdt1 a ambos lados de la proteína, “cargándose” y reclutando una helicasa a cada lado para formar dos horquillas de replicación. 

Los plásmidos de procariotas son parecidos al cromosoma eucariota, pero con un solo origen de replicación (monofocal y bidireccional). Cuando se “chocan” dos burbujas queda un hueco que debe ser rellenado por una polimerasa. En los cromosomas hay varios focos.

## En procariotas
La ADN pol III tiene función correctora y sintetizan las hebras adelantadas, corresponde a las ԑ y δ de las eucariotas. Para eliminar el primer y sustituirla por ADN se usa el ADN pol I, de actividad exonucleasa 5’->3’, capacidad correctora y polimerizante 5’->3’. Para unir los fragmentos de ADN (Okazaki) se requiere al ADN ligasa I, que realiza los enlaces éster fosfato.

## En núcleos (eucariotas)
En las eucariotas hay muchos orígenes de replicación a lo largo del cromosoma, donde la primasa (ADN pol α) y las ADN pol ԑ y δ van alargando las cadenas. Hay una cadena líder continúa y una retrasada de fragmentos de Okazaki. 

Para eliminar los primer hace falta RNAsa H, que tiene capacidad nucleasa, generando una mella (o gap) que se completa con ayuda de ADN pol ԑ o ADN pol δ; y ADN ligasa. 

El proceso clave es el reconocimiento de los orígenes de replicación. La terminación también es decisiva, ya que es imposible completar el extremo 5’ del telómero porque no hay donde anclar un primer; por lo que los telómeros se irían degradando. Culpa de este acortamiento, en fases como el desarrollo embrionario hay que buscar mantener los telómeros vía la **telomerasa**, que es una ribonucleoproteína que usa como molde el ARN y sintetiza ADN que es complementario a la secuencia repetitiva de los telómeros, uniéndose al saliente en 3’ y elonga un poco más ese saliente para que el ADN pol pueda meter un fragmento de Okazaki.

## En mitocondrias
En la [[2 - Wikifarma/mitocondria\|mitocondria]] el ADN es casi 100% codificante, sin asociación proteica y circular que codifica unos 40 genes que son muy importantes (su mutación puede provocar envejecimiento prematuro). Sus cadenas se llaman H (interior) y L (exterior)

Las dos cadenas son codificantes salvo la región NCR (non coding region) o locus de control, que donde hay reguladores de transcripción y traducción que contiene el origen de replicación de la cadena H. Los plásmidos mitocondriales no son iguales a las procariotas, tienen dos orígenes de replicación (OH y OL), una para cada cadena. 

La replicación no va junto al ciclo celular (pueden haber varias centenas de plásmidos). La ADN polimerasa γ lo sintetiza y tiene una helicasa especial llamada TWINKLE. La polimerasa sintetiza un primer que se rodea de proteínas de asociación a monocadena y comienza la síntesis que, 11000 nucleótidos más abajo se encuentra con una horquilla que impide la asociación de proteínas de unión a monocadena, lo que permite que se sintetice un primer en la otra cadena y se comience a sintetizar la cadena L.
