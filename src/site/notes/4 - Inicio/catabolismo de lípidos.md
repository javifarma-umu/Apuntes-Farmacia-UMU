---
{"dg-publish":true,"permalink":"/4 - Inicio/catabolismo de lípidos/","created":"2026-04-30T18:46:19.015+02:00","updated":"2026-05-19T18:36:32.739+02:00"}
---

# Introducción
Los AG puede estar saturado o insaturado, y estas insaturaciones pueden ser alfa o beta. Suelen tener un número de carbonos par, pero a veces ese número es impar. Suelen estar en el tejido adiposo o hígado. Los tejidos consumidores son sobre todo por tejidos de la glándua mamaria, glándulas suprarrenales, miocitos, hepatocitos, etc. A veces se consumen como cuerpos cetónicos en el cerebro. Nunca se consumen en eritrocitos o córnea.

El colesterol es un lípido complejo (derivado del ciclopentano perhidrofenantreno) que es comonente de las [membranas plasmáticas](membrana%20plasmática) y se usan para sintetizar hormonas esteroideas.

# Movilización de reservas de grasas
Cuando ha hay bajos niveles de glucosa (ayuno o ejercicio), el cuerpo tiende a tirar de depósitos de grasas (tejido adiposo). 

El cuerpo segrega hormonas lipolíticas (glucagón, adrenalina, ACTH), lo cause que una PKA active HSL (hormone sensible lipase) llamada triacilglicerol lipasa, que hidroliza los TAG, dejando AG y glicerol: el glicerol se incorpora a la [[4 - Inicio/glicólisis\|glicólisis]]/[[4 - Inicio/gluconeogénesis\|gluconeogénesis]] de los hepatocitos; mientras que los AG se unen a la albúmina y viajan por el torrente sanguíneo.

![Pasted image 20260316131805.png|300](/img/user/6%20-%20Fotos/Pasted%20image%2020260316131805.png)

De normal las gotas de TAG de los adipocitos están rodeadas por perilipina, que protege de las lipasas. Pero cuando se fosforila por la PKA (activada por hormonas lipolíticas) permite el paso a las HSL.

En situaciones de glucemia (como tras una ingesta), el cuerpo sintetiza hormonas lipogénicas como la insulina.

# Catabolismo de los ácidos grasos
Los ácidos grasos se transforman en acil-CoA el acilcoa, que para entrar a la matriz mitocondrial se tiene que transportar junto a la carnitina. Luego se rompen los AG de 2 carbonos en 2 carbonos, formando Acetil-CoAs. Cuando hay mucho acetilCoA, se sintetizarán cuerpos cetónicos (cetogénesis). El citrato será precursor de la ruta anabólica de síntesis de AG.

## Activación de los ácidos grasos y transporte a la matriz
La activación de los ácidos grasos es convertirlos en acil-CoA. Esto estámediado por el Acil-CoA sintasa, que une al AG a un CoA-SH, con el consumo de 2 ATP (en realidad es 1 ATP, pero se hidroliza a AMP). En este proceso el ácido graso primero se une al primer fosfato del ATP, liberando un pirofosfato; y luego se une al CoA-SH. 

Tras activarse el acil-CoA, este tiene que entrar a la [[2 - Wikifarma/Temas de 1º/mitocondria\|mitocondria]] para ser degradado, pero como no cuenta con un transportador específico, debe pasar por la lanzadera de carnitina:
![Pasted image 20260510130735.png|600](/img/user/6%20-%20Fotos/Pasted%20image%2020260510130735.png)
Como muestra la imagen, la aciltransferasa I le pasa el acilo a una carnitina, que si puede pasar a la mitocondria; que luego devuelve el acilo a un CoA-SH gracias a la aciltransferasa II.
## β-oxidación
En cada ciclo de la β-oxidación se quitan 2 C al acil-CoA en forma de acetil-CoA.Hay varios pasos:
![Pasted image 20260510131338.png|500](/img/user/6%20-%20Fotos/Pasted%20image%2020260510131338.png)

1. Hay una deshidrogenación entre carbono alfa y beta por acil-CoA deshidrogenasa, que lleva asociado al FAD, que pasa a FADH2, y deja en el acil-CoA un doble enlace trans formando el Enoil-CoA. Hay isoenzimas para las distintas longitudes de cadena AG (VLCAD (12-18C), LCAD, MCAD (6-10C) y SCAD (4-6C). Es común la falta de la isoenzima para cadenas de media longitud, lo que causa el 10% de las muertes súbitas del lactante
2. El Enoil-CoA hidratasa deshace el doble enlace e hidroxila el carbono β, con el consumo de un H$_2$O. Si se hidrata un enlace trans se forma el isómero L y si se hidrata un enlace cis, se forma un isómero D.
3. La L-β-hidroxiacil-CoA deshidrogenasa oxida al hidroxiacil a cetoacil. Esta reacción es estereoespecífica al isómero L y depende del NAD$^+$, que se reduce a NADH + H$^+$.
4. Finalmente, la Tiolasa media una escisión tiólica, donde se separa un acetil-CoA de la cadena y se integra un CoA al nuevo acilo, creando un Acil-CoA con 2 carbonos menos que antes.

Se regula según la disponibilidad de sustrato o según la actividad de la lanzadera de carnitina

El rendimiento final es de 1NADH (2,5ATP), 1FADH$_2$ (1,5ATP) y 1 acetil-CoA (10ATP) por ciclo (exepto en el último ciclo que se forman 2acetil-CoA). En una cadena de n carbonos, hay (n/2)-1 ciclos. Además, hay que tener en cuenta el coste de activación del AG (2ATP). *el ácido esteárico (C18) produce 120ATP*.

### N.º impar de carbonos
En el caso de que hayan carbonos impares, el último ciclo, en vez de proporcionar 2acetil-CoA, da un acetil-CoA y un propionil-CoA, que se convierte en succinil-CoA y entra al [[4 - Inicio/ciclo de Krebs\|ciclo de Krebs]]:
![Pasted image 20260510134242.png](/img/user/6%20-%20Fotos/Pasted%20image%2020260510134242.png)

- La propionil-CoA carboxilasa es una enzima homóloga y con un mecanismo similar al piruvato carboxilasa. Dependiente de biotina.
- La metilmalonil-CoA epimerasa y mutasa: Catalizan una epimerización y un reordenamiento molecular. Cambio muy pequeño de energía libre. La mutasa depende de cobalamina (vitamina B12)

### Ácidos grasos insaturados
La enoil-CoA hidratasa es incapaz de hidratar enlaces cis, por lo que primero una enoil-CoA isomerasa cataliza la conversión del enlace de 3-cis a 2-trans, que sí puede ser catabolizado. Por cada insaturación, ya sea cis o trans, se pierde la posibilidad de obtener un FADH$_2$

## Otras vías de oxidación de AG
**α-oxidación:**
Es una vía minoritaria que transcurre en el [[2 - Wikifarma/Temas de 1º/retículo endoplasmático\|retículo endoplasmático]] y mitocondria usada por AG metilados. En ella se oxida el Cα y da un α-cetoácido (que se descarboxila). Hay 2 etapas, una hidroxilación y una oxidación a grupo ceto. 

A esta vía se le asocia la enfermedad de Refsum, donde falla de la enzima α-hidroxilante. Se acumula ácido fitánico (presente en productos lácticos) en los tejidos. Síntomas neurológicos importantes que mejoran con disminución del consumo de lácteos y carne de rumiante.

**ω-oxidación:**
Se oxida el último carbono. Sus enzimas se encuentran en el RE del hígado y riñón, que usan de sustrato a ácidos grasos de 10-12 C. Ocurre cuando hay problemas en la β-oxidación.

**β-oxidación peroxisómica:**
Más abundante que las otras (~30% de AG), sobre todo en cadenas muy largas o ramificados. Se produce en el peroxisoma, que puede considerarse una versión defectiva de la β-oxidación normal, con reoxidación de coenzimas por mecanismos independientes de CTE. Es la única que también aparece en plantas.

El transporte del acil-CoA es independiente de carnitina. El FADH$_2$ reduce al oxígeno a H$_2$O$_2$  y el NADH también se reoxida.

Un fallo (genético) en esta vía provoca adrenoleucodistrofia. Se acumulan AGSCML y aparece insuficiencia suprarrenal y desmielinización con síntomas neurológicos severos y progresivos. Pérdida de motricidad y muerte. Como el organismo sintetiza AGSCML, no es suficiente la eliminación de éstos de la dieta. Mejora con el aceite de Lorenzo, que inhibe parcialmente la síntesis de AGSCML.

# Metabolismo de cuerpos cetónicos
Los ácidos grasos viajan por sangre y llegan a los hepatocitos. Cuando hay un exceso de AG y la β-oxidación provoca una saturación del ciclo de Krebs (demasiado acetil-CoA), los AG se convierten en cuerpos cetónicos para evitar la acumulación de AG (hígado graso). Los cuerpos cetónicos pueden viajar por la sangre (son solubles)
## Vía
![Pasted image 20260510171825.png](/img/user/6%20-%20Fotos/Pasted%20image%2020260510171825.png)

La reacción se da en un sentido en el páncreas, pero en la célula consumidora se da la misma reacción pero invertida hasta llegar a acetil-CoA:
![Pasted image 20260510172919.png](/img/user/6%20-%20Fotos/Pasted%20image%2020260510172919.png)

## Cetoacidosis
En algunos casos (*ej:diabetes*), la producción de cuerpos cetónicos excede la capacidad de consumo, por lo que se acumulan en sangre y orina. Esto causa poliuria, acidosis, hipotensión, taquicardia y hasta el coma. Esto se trata con glucemia y control del equilibrio electrolítico.