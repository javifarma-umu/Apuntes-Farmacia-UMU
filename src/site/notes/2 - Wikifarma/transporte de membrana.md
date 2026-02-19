---
{"dg-publish":true,"permalink":"/2 - Wikifarma/transporte de membrana/","tags":["bioquimica"],"created":"2026-02-14T23:02:02.789+01:00","updated":"2026-02-18T18:27:50.533+01:00"}
---

# Generalidades
El paso de sustancias del interior al exterior de la célula/orgánulos es un proceso crucial en la vida que puede ocurrir de distintas formas: 
- La **difusión pasiva** es a través de membrana (sin proteínas) a favor del gradiente. 
- La **difusión facilitada** es un transporte mediada por proteínas a favor del gradiente. Puede ser mediado por **ionóforos**, que son moléculas que envuelven al ión y atraviesa la membrana; o por **canale iónicos**, que se activan por ligando o por voltaje.
- El **transporte activo** necesita aporte energético porque va en contra del gradiente. Puede ser **primario**, cuando es impulsado directamente por la hidrólisis de ATP; o secundario, cuando se usa como "moneda" el transporte de una sustancia a favor del gradiente

El transporte puede ser por uniporte (un tipo de partícula), simporte (dos tipos de partícula en la misma dirección) o antiporte (dos tipos de partícula en dirección opuesta).

La velocidad del transporte por difusión simple es dependiente de la diferencia de la concentración, pero también depende del área, espesor y composición de la membrana. Se supone que sigue la ley de Flick:  
$$
J = -D A \frac{\Delta C}{\Delta X}
$$
En esta expresión J es el flujo neto, D el coeficiente de difusión (depende del tamaño y permeabilidad), ΔC es la diferencia de concentración y ΔX es el espesor de la membrana.

Esta ley muestra una gráfica lineal, pero problema es que experimentalmente se ve una curva hiperbólica. Esta incongruencia significa que se produce una **saturación**, pero también hay sustancias con permeabilidad anómala y sustancias que pasan la membrana cuando no deberían (explicado por la existencia de proteínas trasportadoras). Por ello se establecen los fenómenos de transporte.

# Procesos de transporte

## Difusión simple
La difusión simple se produce con sustancias pequeñas gases y agua; y liposolubles. Siempre es a favor del gradiente y se da hasta que se llega a un equilibrio. No es saturable.

## Difusión facilitada
La difusión faclitada requiere una proteína llamada carrier (o permeasa), que une al soluto, provocambio un cambio de la conformación; y acto seguido libera la partícula al interior para luego volver a su conformación original. Son proteínas específicas. Los solutos transportados de esta manera siguen una curva hiperbólica (la permeasa se satura). 

La existencia de permeasas se justifica termodinámicamente: para que un soluto pase la membrana, debe deshacer de la capa de hidratación (agua) para atravesar la bicapa y luego recuperar la hidratación al salir. Esto conlleva cambios en ΔG:
- **ΔG>0:** El eliminar la capa de hidratación y sobre todo pasar de un entorno polar a uno apolar conlleva un aumento de la energía libre considerable.
- **ΔG<0:** El recuperar la hidratación y volver a un entorno polar restaura la energía libre a su estado original.

Lo que hace la permeasa es **disminuir la barrera energética** formando un poro hidrofílico, así los cambios de energía libre por pasar de entorno polar a apolar no existen. 

La difusión facilitada un transporte específico, saturable e inhibible (y por tanto regulable).

Un ejemplo es el GLUT4 del músculo, que se activa con insulina. Es una proteína de membrana politópica con hélices anfipáticas que adquieren una conformación donde los residuos hidrofóbicos están en la cara exterior de las hélices alfa y en parte interna hay residuos hidrofílicos que forman un poro.

## Transporte activo
Movimiento en contra del gradiente acoplado a la hidrólisis de ATP, generando un gradiente químico o electroquímico.

El **transporte primario** está acoplado directamente a la hidrólisis de ATP. El transportador (bomba) está asociado a una ATPasa en un mismo complejo.

En el **transporte secundario** no se usa directamente el ATP, sino que se usa un gradiente ya generado por un transportador primario para impulsar el cotransporte de otro soluto. 

## Consideraciones termodinámicas
El cambio de energía libre para mover una sustancia a través de la membrana depende de las concentraciones a cada lado de la misma y, en el caso de especies cargadas (iones), del potencial de membrana. 

Para sustancias que no pueden difundir directamente a través de la membrana, el transporte tiene que ser mediado por una proteína y puede o no requerir aporte energético, en función del gradiente y el sentido del transporte.

En especies sin carga, el proceso es **endergónico** (ΔG>0) si va en contra del gradiente y **exergónico** (ΔG<0) si va a favor de él.

En especies con carga, sigue esta fórmula:
$$
\Delta G_T = RT \ln \left( \frac{[A]_{\text{int}}}{[A]_{\text{ext}}} \right) + Z_A F \Delta \Psi
$$
Donde Za es la carga del ion, F es la constante de Faraday y Ψ es el potencial electrónico de la membrana.

## Tipos de transportadores
las ATPasas son 
- tipo P ([bombas](bombas%20y%20canales)): que están presentes en todas las células y forman gradientes de Na K H o Ca tienen 7 partes
- Las de tipo F son de la membrana mitocondrial y participan en la fosforilación oxidativa, sintetizando ATP a partir de un gradiente. Presentan dominio transmembrana (F0) y periférica (F1)
- Las de tipo V acidifican orgánulos
- La superfamilia ABC son transportadores de fármacos, que pueden usar células tumorales para rechazar fámacos. Son también transportadores de lípidos.

Las de **tipo V** se llaman así porque son típicas de vesículas y vacuolas. Tienen un dominio v1 periférico y V0 integral. Bombean protones del citosol al orgánulo, acidificándolo. Para realizar ese proceso se necesita el aporte energético de la hidrólisis de ATP, que se produce en V1.

Las **tipo F** (o ATP sintasas) tienen estructura parecida a V, con dominio transmembrana F0 y periférico F1. Son típicas en la membrana interna mitocondrial participando en la fosforilación oxidativa, bombeando protones a favor del gradiente para sintetizar ATP.

La superfamilia ABC permite el transporte de moléculas hidrofóbicas (como colesterol) y fármacos. Hay 7 subfamilias (ABCA, ABCG, etc). 
- La ABCA1 transporta el colesterol hacia las HDL
- La PGP o MDR1 es la ABCB1 se dedica a sacar fármacos y otros xenobióticos de la célula. Los tumores sobreexpresan su gen para resistir fármacos.
- El CFR (regulación de conductancia transmembrana de fobrosis quística) transporta Cl- hacia el exterior. Como se hidrata el Cl- la sobreexpresión produce moco y es síntoma de la fibrosis quística.

## Digestión
La absorción de nutrientes se produce en la membrana apical de los enterocitos del intestino para luego transportarlo al torrente por la parte apical. Para llegar al torrente, los nutrientes deben ser transportados:

### Monosacáridos
Los [glúcidos](glúcido) son polares, por lo que necesitan difusión facilitada o transporte activo. En un primer momento es difusión facilitada, pero luego será transporte activo secundario, aprovechando el gradiente de Na producido por la bomba ATPasa, haciendo un simporte. Hay distintos tipos de transportadores: 
- **SLGT1** son mayoritarios de glu y gal.
- **GLUT2** menos específica.
- **GLUT5** especializado en fructosa.
- **GLUT4** es sensible a la insulina.

Para pasar a los capilares, se usa la difusión facilitada.

### Aminoácidos
Hay distintos tipos de transportadores específicos a distintos tipos. Pueden transportarse tanto [aa](aminoácidos) como dipéptidos. Se transportan por grupos:
- AA neutros con cadenas polares o cortas
- AA neutros hidrofóbicos/aromáticos
- taurina
- básicos + cistina
- iminoácidos
- ácidos
- dipéptidos/tripéptidos

Lo hacen por simporte de protones. Cuando falla un transportador se acumulan los aa, produciendo patologías:
- **Enfermedad de Hartnup:** es general benigna, pero casos graves puede causar lesiones de piel, fotosensibilidad y algunos síntomas neurológicos. Se da por la acumulación de aminoácidos neutros. La malabsorción de Trp en el intestino hace que la flora intestinal produzca indicán (pañal azul). 
- **Cistinuria clásica:** Causada por la malabsorción de la cisteína, causa cálculos renales.
### Lípidos
Como son liposolubles, los [lípidos](lípido) no necesitan transportadores. Los AG de cadena corta y MAG atraviesan fácilmente. En el enterocito se reconstruyen el los TAG y se asocian a proteínas para formar quilomicrones.

## Reabsorción de agua
Las acuaporinas favorecen el movimiento de [[2 - Wikifarma/agua\|agua]] en las membranas y se encuentran en abundancia en tejidos como el del [riñón](aparato%20urinario#Riñón).

La más común es la AQP1, de 4 subunidades idénticas que constan de 6 hélices largas y 2 cortas. Multiplica el transporte de agua por 3x10^9, pero no el de urea, glicerol o iones. Tiene residuos hidrofílicos y su punto más estrecho tiene el ancho justo para 1 molécula de agua y su His y Asn repelen los iones.

La AQP2 se regula por vasopresina

AQP3 permite el paso de sustancias como glicerol y urea.
