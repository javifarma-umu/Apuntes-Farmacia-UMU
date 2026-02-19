---
{"dg-publish":true,"permalink":"/2 - Wikifarma/procesos post transcripcionales/","tags":["bioquimica"],"created":"2026-02-08T20:18:18.688+01:00","updated":"2026-02-19T17:50:58.459+01:00"}
---

# Regulación de la expresión genética
La regulación de la expresión génica es un proceso complejo, sobre todo en eucariotas y seres pluricelulares, que permite a las células cumplir funciones completamente distintas (especialización) a pesar de tener el mismo genoma. Esta especialización se da gracias a que cada célula tiene un perfil de expresión proteica propio. Esta regulación puede ser pretranscripcional, transcripcional o postranscripcional.

La **regulación pretranscripcional** modifica la accesibilidad del ADN a la maquina de transcripción e incluye:
- El estado de **condensación** de la cromatina.
- Disposición de señales **epigenéticas** en el ADN e histonas.

La **regulación transcripcional** controla el inicio y eficacia de la transcripción e incluye:
- Eficacia de los **promotores**.
- Los **factores de transcripción**.
- **Velocidad de elongación**.
- **Eficiencia de terminación**.

La regulación **postranscripcional** se refiere a los fenómenos que se dan tras la transcripción como:
- El **ayuste** de transcritos.
- La **maduración**, que puede ser convencional o alternativa.
- **Translocación** de los ARN en el [[2 - Wikifarma/citosol\|citosol]].
- **Estabilidad** de los ARN y procesos de **ribointerferencia**.

# Maduración 
En las células eucariotas, los transcritos primarios de ARN son moléculas grandes sin función biológica que deben sufrir un proceso de maduración para eliminar las secuencias prescindibles. Así se pasa de ARNhn a un ARNm maduro. Este proceso es exclusivo a los seres eucariotas, ya que el ARNm procariota no sufre maduración postranscripcional. La maduración del transcrito primario ocurre en el núcleo y conlleva:
- Modificación de nucleósidos y adición de nucleótidos en ambos extremos
- División de la molécula precursora (corte)
- Eliminación de largos fragmentos de secuencias internas llamadas **intrones**.
- Unión (empalme) de secuencias que estaban separadas en el transcrito primario
- Exportación del ARN al citosol

Esta maduración la sufre los transcritos primarios principales (ARNhn, preARNt y preARNr). Se trata de un proceso muy delicado (errores llevan a una mala expresión genética) mediada por un amplio complejo enzimático. 

Los intrones suelen ser mucho más largos que los exones *si un exon tiene ~200 nucleótidos, un intrón tiene ~1000*. El número de intrones parece ser proporcional a la complejidad de la especie, siendo el nº de intrones por gen humano alrededor de 6 o 7 intrones por gen.

La maduración de los transcritos primarios hace que:
- Los transcritos primarios obtengan actividad biológica 
- El ARN se vuelvan más estable, aumentando su vida media en el citosol
- El transcrito se acorte, facilitando el transporte al citosol
- El ARN sea mejor molde para la traducción

## Formación del capuchón 
Una proceso de maduración al ARNm es la formación del capuchón. Es un proceso que sufre el transcrito primario (ARNhn) en el extremo 5' por guanosilación. La caperuza es una estructura particular al ARNm eucariota que otorga estabilidad química al transcrito, ya que sirve de protección contra exonucleasas que actúan sobre el extremo 5', ya que imposibilita el reconocimiento de este extremo. Además, la caperuza puede servir de anclaje para el ribosoma y tanto la capucha como los dos nucleótidos siguientes pueden sufrir reacciones químicas.

### Guanosilación
Primero se añade la guanosina en una reacción acoplada llamada guanosilación, un proceso cotranscripcional en la que se parte de un transcrito primario y hay 2 fases:
-  **Defosforilación:** La fosfatasa acoplada a la cola C-terminal del ARNpol II hidroliza el enlace fosfato del nucleótido del extremo 5', liberando el fosfato γ. 
- **Guanililación:** La mRNA guanililtransferasa usa de sustrato un GTP para transferir un grupo guanililo (radical del GMP), uniéndose al extremo 5' y liberando dos fosfatos. El producto final es una guanosina unida al transcrito primario por una unión 5'-5' trifosfato

### Metilación
Es una reacción catalizada por la metiltransferasa (asociada a la cola del ARNpol II) en la que S-adenosilmetionina dona un metilo, convirtiéndose en S-adenosilcisteína. Esta metilación puede sufrir en la guanosina del capuchón o alguno de los dos nucleótidos siguientes. Puede formar varias estructuras:
- **Caperuza 0:** 1 metilación en el N7 de la guanosina.
- **Caperuza 1:** 2 metilaciones, una en el N7 de la G y otra en el hidroxilio C2' de la siguiente ribosa.
- **Caperuza 2:** 3 metilaciones, una en el N7 de G y las otras dos en el hidroxilo C2' de las dos ribosas siguientes.

## Adición de la cola poliA
Otra modificación necesaria que sufre el ARNhn es la poliadenilación, donde se añaden muchas adeninas al extremo 3' del ARN. Esta cola protege de la degradación por ribonucleasas en el extremo 3', ayudando a que el ARNm dure más en el citosol. Además, la cola poliA es reconocida para el proceso de transporte del ARN del núcleo al citosol.

La poliadenilación ocurre porque el transcrito primario tiene una señal de poliA, que atrae a CsTF (cleavage stimulation factor) y CPSF (cleavage and polyadenylation specificity factor), que saltan de la cola del ARNpol II. La CPSF hace de señal para que CsTF (endonucleasa) corte el ARN por 3', liberándolo de la maquinaria de transcripción ~30 nucleótidos aguas abajo de donde se unió, dejando un extremo 3' expuesto.

La CPSF luego atrae a PAP (poliA polimerasa), que añade adeninas al extremo 3' libre hasta formar una cadena de 40-250 adeninas. Este proceso de poliadenilación es postranscripcional.

## Eliminación de intrones
En el ARNhn hay secuencias que se eliminan durante la maduración y no están presentes en el transcrito maduro. Estas secuencias se llaman **intrones**, que no se deben confundir con las UTR (que si que se conservan pero no codifican genes), y suponen que la secuencia de ADN o transcrito primario sea distinta al transcrito maduro, es decir, el ARNhn es colineal a la cadena codificante, pero el ARNm maduro es muchísimo más corto (por tanto no colineal).

Para cortar los intrones, es necesario romper los enlaces fosfodiéster, para lo que ayuda la maquinaria de splicing (también llamado **spliceosoma** o ayustosoma), que cataliza el corte y empalme. 

### Proceso de corte y empalme
Los spliceosomas reconocen varias señales del intrón para hacer el proceso de corte y empalme:
- **Centro de ayuste 5':** los dos primeros nucleótidos son GU.
- **Centro de ramificación (motivo CURAY):** la adenina de esta secuencia es esencial.
- **Centro de ayuste 3':** los dos últimos nucleótidos son AG.
Estos motivos tienen cierta flexibilidad en la secuencia de nucleótidos para el proceso de splicing.

Durante el proceso de corte (que ocurre gracias al espliceosoma). Sigue los siguientes pasos:
1. Se corta el intrón en 5'. 
2. El extremo libre 5' es atacado por el hidroxilo de 2' de la adenina del motivo CURAY, formando una estructura de lazo (la A se llama punto triple porque se enlaza con 3 nucleótidos) con un enlace éster-fosfato 2',5' (muy poco común) que une la G del centro 5' con la A del motivo CURAY. 
3. Cuando se forma este enlace se rompe el intrón en 3', liberándose. 
4. Luego el hidroxilo libre del exón se une al otro exón en un enlace éster-fosfato (empalme).

Estas reacciones consecutivas de transesterificación ocurren gracias a la participación del espliceosoma, permitiendo la participación de muchos nucleótidos, acortándose mucho la secuencia. El ARN se va cortando y empalmando a medida que se sintetiza.

### El spliceosoma
El spliceosoma es una maquinaria formada por ribonucleoproteínas nucleares pequeñas (snRNP), es decir, asociaciones de proteínas con ARN. Forman unas partículas (U1, U2, U4, U6), que no llegan a ser orgánulos, pero tienen cierto parecido a la subunidad grande del ribosoma. Están formados por un ARN nuclear pequeño (ARNpn) de 100-200 nucleótidos y ~10 proteínas. 

Se tratan de partículas altamente específicas para:
- El reconocimiento de subunidades de ARNpn y proteínas para formar la snRNP.
- El reconocimiento de la secuencia del intrón.
- El reconocimiento de proteínas propias y ajenas.

Dependiendo de la combinación de proteínas se obtienen los distintos tipos de ribonucleoproteínas (U):
- **U1:** Contiene un RNApn que reconoce que reconoce específicamente al sitio de ayuste 5’ al ser completamente complementario y antiparalelo.
- **U6:** También es complementario al sitio de ayuste 5', pero no tanto como U1. La U6 y U1 forman un sistema de doble chequeo.
- **U2:** Tiene alta afinidad por el sitio de ramificación y también es capaz de desplazar las branch binding proteins (BBP) del sitio CURAY e identificarlo como sitio de ramificación y además tiene nucleótidos complementarios con U6, dándole la capacidad de acercar los nucleótidos del sitio de ayuste 5' y el motivo CURAY.

Hay proteínas con dominio SR (serina arginina) que ayudan a reclutar a los componentes de ayustosomas a los sitios pertinentes. Viajan en la cola carboxilo terminal de a subunidad beta de la ARNpol II y saltan al motivo ESE (motivos intraexónicos que fomentan el splicing), donde atraen a las snRNP. 

### Splicing alternativo
Un "fallo" en el proceso de corte y empalme implicaría que un motivo de ayuste reconozca a un motivo del intrón siguiente, saltándose un exón interno, provocando un splicing alternativo.

El **splicing alternativo** se consideraba un proceso anómalo, pero en realidad es un proceso que permite a la célula poseer varios ARNm a partir de un solo transcrito primario (ocurre en el 85% de genes multiexónicos). En este proceso el spliceosoma se salta secuencias exónicas. 

Un ejemplo es el gen de la troponina, que tiene tiene varias isoformas (troponina α y β). Esto depende de proteínas silenciadoras (ESS), que no tienen motivo SR y se unen al ESE, bloqueando a las SR de manera competitiva. 

Aparte de los motivos ESE y ESS, existen los motivos ISS (silenciador intraintrónico) y ISE (estimulador de splicing intraintrónico)

Las mutaciones sobre los sitios de ayuste están asociadas con patologías como el cáncer.

## En ARN no mensajero
En el genoma humano también hay transcritos primarios de ARNr y ARNt que son modificados. 

En el **ARNr** hay 2 genes: uno del precursor grande (45S) que lleva la info de 3 ARNr (18S, 5,8S y 28S), que son cortados para generar los ARNr maduros; y un preARN pequeño (5S), que también es cortado por endonucleasas. 

En procariotas, las secuencias secuencias de ARNr están mezcladas con secuencias de ARNt. El pre-ARNr es 30S y tiene información para fragmentos de ARNr 16S, 23S y 5S  

En los precursores del **ARNt** eucariotas hay un splicing parecido al de los ARNm, donde además de cortar los intrones, las endonucleasas cortan una secuencia guía 5’, una trailer 3’ y se añade al extremo 3’ (brazo aceptor del aminoácido) una secuencia CCA. Además, se modifican covalentemente algunas bases

### Tabla resumen de la maduración
**PROCARIOTAS**

|          | precursor                   | corte por <br>endonucleasa          | ayuste                               | corte por<br>exonucleasa | adición 3' | modificación 5' | modificación nucleósidos |
| -------- | --------------------------- | ----------------------------------- | ------------------------------------ | ------------------------ | ---------- | --------------- | ------------------------ |
| **ARNm** | ---                         | ---                                 | ---                                  | ---                      | ---        | ---             | ---                      |
| **ARNr** | precuursor 30S              | a ambos lados (RNasa III)           | en algunos organismos hay autoayuste | en ambos extremos        |            |                 | algunas metilaciones     |
| **ARNt** | pre ARNt y algunos pre ARNR | a ambos lados (RNasa P u RNasa III) |                                      | extremo 3' (RNasa D)     |            |                 | muchas bases modificadas |

**EUCARIOTAS**

|          | precursor          | corte por <br>endonucleasa | ayuste                                 | corte por<br>exonucleasa | adición 3'                                   | modificación 5' | modificación nucleósidos                   |
| -------- | ------------------ | -------------------------- | -------------------------------------- | ------------------------ | -------------------------------------------- | --------------- | ------------------------------------------ |
| **ARNm** | preARNm            | solo extremo 3'            | sí (en la mitocondria autoayuste)      |                          | cola poliA                                   | capuchón        | en casos puntuales desaminación (de C a U) |
| **ARNr** | preARNr (45S y 5S) | similar a procariotas      | en algunos unicelulares (autoayuste)   | similar a procariotas    |                                              |                 | metilación de ribosas                      |
| **ARNt** | preARNt            |                            | en algunos seres (mecanismos variados) | en ambos extremos        | secuencia CCA (tRNA-nucleotidil-transferasa) |                 | muchas bases modificadas                   |
.

# Transporte al citosol
Una vez ocurren estas modificaciones, los transcritos deben migrar del núcleo al citosol, por lo que deben pasar el complejo poro, que es muy específico y solo es atravesado si llevan una proteína de la familia **exportina**. 

En el caso del **ARNm**, el propio ARN se une a las exportinas en el motivo exón-exón, permitiendo la translocación al exterior. Una vez en el exterior, los mensajeros deben ser marcados (para participar en la síntesis y no ser degradado) por **IF** (initiation factors) en la caperuza y por las **PABP** (poliA binding protein) en la cola. Estas proteínas interactúan entre sí, haciendo que el ARNm haga una estructura circular donde los extremos 5’ y 3’ están cerca y pueden ser reconocidas por los ribosomas. 

Si este enrollamiento no se da, ya sea por una anomalía o porque ya hay suficientes proteínas, el gen es silencido por el motivo **RISC**, con ayuda de unos **micro RNA** . Estos micro RNA tienen un precursor pri-micro, que es más largo y tiene una estructura secundaria de tallo largo que es cortado a un pre-micro. El pre-micro sale al citosol con exportinas y es cortado por la enzima **DICER** a microRNA, que consta de una doble cadena que se separa en una cadena funcional y otra pasajera (que se degrada). La cadena funcional se une a la región UTR 3’ y silencia al gen porque impide físicamente la síntesis y además marca para la muerte al ARN. 

La ribointerferencia es una herramienta muy común para comprobar la función de un gen.
