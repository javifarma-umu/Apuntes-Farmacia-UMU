---
{"dg-publish":true,"permalink":"/2 - Wikifarma/cinética enzimática/","tags":["bioquimica"],"created":"2025-12-29T01:29:56.683+01:00","updated":"2026-01-24T20:11:29.553+01:00"}
---

# Generalidades
La cinética enzimática estudia la velocidad de las reacciones y los factores que la afectan. Para esto hay que recurrir que la reacción requiere que dos partículas colisionen, rompan enlaces y formen unos nuevos. Es muy importante las concentraciones de enzima y sustrato, capacidad catalítica y condiciones ambientales. 
Son reacciones regulables, es decir, pueden ser inhibidos o activados dependiendo de las condiciones fisiológicas.
![Pasted image 20251229014037.png](/img/user/7%20-%20Fotos/Pasted%20image%2020251229014037.png)
Cuando hay varias etapas, la velocidad depende del paso más lento (limitante). Si la 1ª reacción es reversible, hay un "estado de preequilibrio" donde la formación y descomposición de intermedios alcanza un equilibrio; hay un balance directo e inverso; la concentración de los intermedios es constante; el estudio cinético es "sencillo". Esto pasa en las reacciones enzimáticas:
![Pasted image 20251229014429.png](/img/user/7%20-%20Fotos/Pasted%20image%2020251229014429.png)

## Factores ambientales
- **pH:** los cambios de pH pueden afectar la afinidad enzima-sustrato.
- **T:** El aumento de T provoca un aumento de velocidad, hasta que se desnaturaliza la enzima.
Por ello, la actividad enzimática se miden a T y pH óptimo en unidades de actividad enzimática (U), que es un μmol/min.
# Michaelis-Menten
Se considera un estado estacionario donde la formación y descomposición de ES es constante. La concentración de P es muy baja (casi 0, ósea al inicio de la reacción), por lo que se obtendrán velocidades iniciales. El sustrato está en exceso cuando la concentración de éste es mucho mayor que el de la enzima. Si se grafica la cantidad de producto frente al tiempo se obtienen gráficas como estas:
![Pasted image 20251229020056.png](/img/user/7%20-%20Fotos/Pasted%20image%2020251229020056.png)

Para encontrar los factores cinéticos hay que saber que:
$$
V_0 = \frac{V_{\max}[S]}{K_m + [S]}
$$
$$
K_m = \frac{k_{-1}+k_2}{k_1}
$$
A concentraciones bajas de sustrato, la concentración de este es proporcional a la velocidad, pero cuando la cantidad de sustrato aumenta mucho, la enzima se satura y alcanzará una meseta donde la velocidad dependa solamente de la liberación de productos.

## Capacidad catalítica
Se mide con la constante de especifidad (kcat/Km).
- Km es la \[S] para cual V0=1/2Vmax. Cuanto mayor es Km, menor es la afinidad.
- Vmax es la velocidad cuando la enzima está saturada y depende de \[E]. Permite calcular el número de recambios de la enzima (kcat), es decir, el número de unidad de sustratos que se convierten en producto por unidad de tiempo. kcat= Vmax/\[E]

## Linealización de Michaelis-Menten
La linealización de Michaelis-Menten se puede obtener por varios métodos y es una manera de poder pasar los datos experimentales a un formato más manejable (ej: permite los mínimos cuadrados).
Una manera de determinar Km y Vmax es mediante la ecuación de Linewever-Burk:
$$
\frac{1}{V_0} = \frac{K_m}{V_{\max}} \frac{1}{[S]} + \frac{1}{V_{\max}}
$$
Aquí 1/Vmax es el origen y Km/Vmax es la pendiente.

# Inhibición enzimática
Es la disminución de la actividad enzimática por medio de un inhibidor, que puede ser irreversible (unión covalente) o reversible (unión no covalente). Un ejemplo es la penicilina, que desactiva la transpeptidasa necesaria para la síntesis de peptidoglucano de las paredes bacterianas mediante una inhibición covalente irreversible.

## Tipos de inhibidores
- **Competitivos:** Tienen una estructura similar al sustrato, por lo que compite con él para unirse al centro activo. Se puede amortiguar la acción de este tipo de inhibidores si la concentración de sustrato es lo suficientemente elevada. No varía la Vmax, pero si aumenta la Km, que pasa a ser Kmap, que es igual a α\*Km; α=1+\[I]/Ki. 
![Pasted image 20251229134809.png|390](/img/user/7%20-%20Fotos/Pasted%20image%2020251229134809.png)
- **No competitivos:** Se unen a un sitio distinto al centro activo, provocando un cambio conformacional en el centro activo. No varía la Km, pero disminuye la Vmax, que será Vmax/α. ![Pasted image 20251229134950.png|390](/img/user/7%20-%20Fotos/Pasted%20image%2020251229134950.png)
- **Acompetitivos:** Inhibidores irreversibles que se unen al complejo enzima-sustrato en un lugar distinto al centro activo. Disminuye tanto la Km (Km/α) como la Vmax (Vmax/α).

# Enzimas alostéricas.
Son enzimas con varias subunidades y varios centros. Estos centros pueden ser centros activos o centros alostéricos (que pueden aumentar o disminuir la afinidad E-S). Esto crea un efecto alostérico que puede ser ser homotrópico (sustrato y efector son el mismo compuesto) o heterotrópico (un ligando afecta la fijación de otro), que crea ligandos moduladores que actúan sobre centros activos.
Estos efectos están medidos por la cooperatividad entre subunidades y crean curvas sigmoides que no siguen el modelo de Michaelis-Menten que marcan etapas clave de rutas metabólicas.

- **Modelo simétrico (Monod):** Asume que la enzima es un oligómero simétrico donde cada protómero tiene un centro para el ligando. Tiene dos estados conformacionales (tenso y relajado) y la transformación es simultánea en todos los los oligómeros.
- **Modelo de encaje inducido (Koshland):** El ligando crea un cambio conformacional en su protómero que cambia la afinidad hacia S en otras subunidades. Hay un cambio progresivo entre las subunidades con varios estados intermedios que "contagian" a los otros protómeros.

Un ejemplo es la ATCasa, que participa en la primera  etapa de la ruta de síntesis de pirimidinas. Tiene 2 trímeros catalíticos y 3 reguladores. Los reguladores pasan la enzima a estado T (estabilizado por la presencia de inhibidores) durante la inhibición y a estado R (estabilizado por sustratos y activadores) en la activación.

# Enzimas de interés biológico
Hay enzimas que pueden usarse como marcadores patológicos tanto directos o indirectos.

| Enzima                              | Alteración                                                                                       |
| ----------------------------------- | ------------------------------------------------------------------------------------------------ |
| α-amilasa                           | **Elevada:** pancreatitis e insuficiencia renal<br>**Disminuida:** pérdida de función pancrática |
| Creatina quinasa (CK)               | **Elevada:** infarto de miocardio y afecciones musculares                                        |
| Aminotransferasas                   | **Elevada:** enfermedades hepáticas                                                              |
| Acetilcolinesterasa                 | Determina la intoxicación por insecticidas<br>**Disminuida:** hepatopatías e infarto             |
| Fosfatasa ácida                     | **Elevada:** cáncer de próstata                                                                  |
| Enzima convertidora de angiotensina | **Elevada:** cáncer de pulmón                                                                    |
