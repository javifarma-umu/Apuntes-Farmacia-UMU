---
{"dg-publish":true,"permalink":"/2 - Wikifarma/regulación de la expresión génica/","tags":["bioquimica"],"created":"2026-02-08T20:17:39.414+01:00","updated":"2026-02-19T09:20:25.135+01:00"}
---

# Generalidades
La [[2 - Wikifarma/transcripción\|transcripción]] es un proceso muy regulado. Se tiene en cuenta la secuencia, etapa celular y frecuencia. Para comprender la necesidad de la regulación de la transcripción, hay que tener en cuenta varias cosas:
- Todos los seres pluricelulares empiezan como una única célula.
- Todas las células de un individuo tienen un **mismo [genoma](organización%20del%20material%20genético)** (y por ende la posibilidad de expresar las mismas proteínas), que en el caso del humano son ~25000 genes. 
- El organismo posee distintos tejidos y especializaciones, resultado de la expresión del **proteoma**. En el hombre hay ~200 tipos celulares.
- La expresión genética difiere según la **especialización** y **etapa de desarrollo**. Hay genes de **expresión ubicua** (o constitutiva) presentes en todas las células, como las proteínas de membrana o actina; y genes de **expresión regulada**, responsables de las especializaciones.
- La expresión regulada responde a cambios metabólicos, etapas del ciclo celular, respuestas a estímulos, estado de salud, nutrición…

Hay tres niveles de regulación: pre-transcripcional, transcripcional y post-transcripcional. Además, esta regulación puede ser genética; o **epigenética**, es decir, basada (o en consecuencia) en marcas moleculares que afectan a ADN e histonas.

# Niveles de regulación
El **control pretranscripcional** se ejerce sobre el ADN y se basa en:
- El control de la [condensación del ADN](organización%20del%20material%20genético#Condensación%20y%20descondensación), lo que condiciona si se puede leer un gen o no. Este control está condicionado por señales epigenéticas.

El **control transcripcional** se ejerce sobre el proceso de pasar del ADN al transcrito primario de ARN. Este control incluye:
- Frecuencia y velocidad de **iniciación** de la transcripción. En este proceso es importante la accesibilidad de los puntos de inicio, los factores de transcripción y la eficiencia de los promotores.
- Velocidad de elongación, aunque está poco regulada.
- Eficiencia en la terminación de transcripción.

El control **postranscripcional** se ejerce sobre una variedad de procesos que ocurren tras la transcripción del ADN a ARN:
- El **procesamiento del ADN**
	- **Velocidad de maduración**, que incluye el ayuste y las modificaciones postranscripcionales.
	- **Maduración alternativa**.
- El **transporte** del transcrito al citosol desde le núcleo
	- Selección del ARN que será transportado.
	- El paso por el complejo poro.
- La **degradación** del ARN
	- **Estabilidad** del ARNm maduro.
	- **Ribointerferencia**.

# Regulación pretranscripcional (señales epigenéticas)
Las señales epigenéticas son señales químicas heredables propias de cada tejido que señalan el ADN e histonas.

## Sobre el ADN (metilación CG)
La metilación del ADN ocurre sobre las islas CG (CpG) presentes en los promotores (~4% de las C en humanos). Esta metilación interfiere con la transcripción de los genes. La **hipermetilación** disminuye la transcripción de genes aguas abajo, lo que supone un silenciamiento génico; mientras que la **hipometilación** favorece a transcripción.

### Proceso de metilación
En la metilación, un sustrato donador, que suele ser S-adenosilmetionina (**SAM**) le da un metilo a la posición 5 de la citosina en un proceso mediado por la metilasa que libera un H+ y transforma el SAM en S-adenosilhomocisteína.

La desmetilación ocurre secuencias mCpG, donde la desmetilasa usa un agua para eliminar el grupo metilo, obteniendo como subproducto un CH3OH

### Influencia en la transcripción
Los promotores hipermetilados interfieren con la unión de la ARN pol II y factores de transcripción. 

Esto ocurre porque los mCpG atraen a las proteínas MeCP1 y MeCP2, que reclutan a las enzimas HDAC (histona desacetilasa), HMT (histona metil transferas) y HDMT (histona demetilasa). Las MeCP **impiden el reconocimiento**. Las HDAC eliminan los acetilos del extremo N de las histonas, provocando una carga positiva que causa la **condensación** de la cromatina. Como resultado **no hay transcripción**.

Cuando los islotes CG no están metilados, hay unión de ARNpol II y los FT, por lo que se da la transcripción.

## Sobre las histonas (metilación y acetilación)
La acetilación está mediada por la enzima HAT, que hace que el extremo N de la histona pase de un lisina (carga positiva) una ε-N-acetil-lisina (carga neutra). Este cambio abre la cromatina (conformación laxa) lo que permite la replicación, transcripción y reparación. La acetilación requiere como donador a un acetil-CoA, que se transforma en CoA.

El proceso opuesto (desacetilación) está mediada por la enzima HDAC, y transforma a la ε-N-acetil-lisina (carga neutra) de nuevo a lisina. Las cargas positivas de las lisinas causan la condensación de las histonas, silenciando el gen; como ocurre en los centrómeros y telómeros. El proceso de desacetilación libera un acetato.

# Regulación transcripcional
Involucra sobre todo en la región promotora y a los factores de transcripción. En el gen la región reguladora es la que engloba al promotor basal (muy cerca de +1), promotor proximal (más o menos en -200) y al promotor distal.

En los eucariotas, el ARN polimerasa no puede unirse solo al promotor, por lo que necesita una "pareja de baile", que son unas proteínas llamadas factores de transcripción. Además, también hay proteínas que flexionan el ADN para acercar al promotor basal y distal.

Los factores de transcripción dependen del tipo de gen

| Producto                     | Gen       | Polimerasa  | Promotor     | Factores de transcripción |
| ---------------------------- | --------- | ----------- | ------------ | ------------------------- |
| ARNr 28S, 18S y 5,8S         | clase I   | ARN pol I   | de clase I   | TFI                       |
| proteínas y ARNhn            | clase II  | ARN pol II  | de clase II  | TFII                      |
| ARNt, ARN pequeños y ARNr 5S | clase III | ARN pol III | de clase III | TFIII                     |

## Genes tipo II

### Complejo de iniciación (basal y proximal)
En los promotores basales de genes tipo II hay: 
- Motivos BRE (BREu y BREd). Unen TFIIB
- Caja TATA, a la que se une la TBP. Une a TFIID
- Inr, que es el elemento iniciador Une también a TFIID
- DPE, o elemento promotor corriente abajo. En algunos genes se combina con DCE. Une a TFIID
- DCE, o elemento central corriente abajo. 
- MTE, o elemento motivo diez, que está ubicado justo corriente arriba del DPE. Une a TFIID

La unión de los FT es secuencial, siguiendo el siguiente orden: TFIID, TFIIA, TFIIB, la polimerasa con TFIIF, TFIIE y finalmente TFIIH.
![Pasted image 20260214134952.png](/img/user/6%20-%20Fotos/Pasted%20image%2020260214134952.png)
Otros motivos comunes en el promotor proximal son la secuencia CCAAT, que une CTF (NF1) y la repetición de CG (islas CpF), que une SP1.

El promotor proximal y basal pueden colaborar porque hay proteínas que arquean el ADN, acercando en el espacio tridimensional a los promotores, permitiendo que interaccionen. Se forma un **complejo de transcripción**, que aparece en todos los genes constitutivos. En este complejo, TFIID (TAFs y TBP), TFIIA, TFIIB, ARNpol II, TFIIF (helicasa), TFIIE (SSBP) y TFIIH (helicasa y quinasa) se unen al promotor basal. Además, CTF y SP1 se unen al promotor proximal. Los promotores pueden ser débiles o fuertes. Los fuertes aumentan la fuerza y afinidad del proceso de transcripción.

Sobre los promotores basales y proximales actúan factores de transcripción **generales**, que están en todos los tipos celulares; y son independientes del ciclo celular y momento metabólico, Regulan la transcripción de genes constitutivos

### Promotor distal
El **promotor distal** es el sitio de actuación de los TF inducibles, que son específicos al tejido  y dependientes del ciclo celular y momento metabólico. Regulan la transcripción de genes inducibles. 

Está muy alejado del origen y sobre él hacen efecto las hormonas, que hacen de factor de transcripción (activador o represor). Los factores de transcripción inducibles se unen a mediadores, que están enlazados al complejo de iniciación de (promotor basal y proximal).

Los **activadores** se unen a secuencias potenciadoras del promotor distal, mientras que los **represores** se unen a zonas llamadas silenciadores, que reducen la tasa de transcripción. Esto afecta el comportamiento de los TF basales. Los factores de transcripción inducibles conectan con los coactivadores, que se encuentran unidos a las proteínas del complejo de iniciación. Los coactivadores integran estas señales.