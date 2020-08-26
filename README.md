# Práctica 9
# *INDUCTOR Y CAPACITOR*
## *PLANTEAMIENTO DEL PROBLEMA*

Ya al haber trabajado en el funcionamiento de una onda senoidal, podemos analizar dos elementos muy importantes en el estudio de circuitos eléctricos, como lo son los capacitores y los inductores, donde veremos para que sirve cada uno de ellos y porque debe funcionar con una fuente alterna, y de qué forma trabaja con una fuente continua. Vamos a realizar los debidos cálculos, con variación en la frecuencia de la fuente, tanto de voltaje, como de corriente, y a ver su respectivo error, al comparar los cálculos de nuestro osciloscopio, con los cálculos del multímetro en corriente alterna.

## *OBJETIVOS*
# Objetivo general
- Diseñar un circuito que permita representar la manera en que se comportan los capacitores e inductores en circuitos con distintas corriente mediante la simulación en el laboratorio virtual DCACLab con el fin de relacionar los conicimientos adquiridos en clase con la práctica.

# Objetivos específico
- Verificar el comportamiento de la bobina y el capacitor en circuitos DC.
- Verificar el comportamiento de la bobina y el capacitor en circuitos AC.
- Verificar las combinaciones serie y paralelo de bobinas y capacitores.
- Familiarizarse con el uso del osciloscopio y el multímetro.

## *LISTA DE MATERIALES*


| Cantidad | Material de Equipo |
| ------------- | ------------- |
| 1  | Generador de Funciones |
| 1  | Fuente DC |
|  1 | Osciloscopio  |
| 1  | Protoboard |
| 1  | Multímetro digital |
| 1  | Cables conductores |
|  1 | Resistor de 100 Ω |
|   2 | Capacitores de 10 µF |
|  2  | Inductores de 10m mH |

Tabla 1. Materiales
## *MARCO TEÓRICO*

Los inductores y capacitores son elementos que sirven para almacenar energía, donde para entender un poco sobre estos elementos hay que tomar en cuenta la diferencia que hay entre estas dos, por ejemplo los inductores guardan energía en forma de campo magnético pero los capacitores guardan la energía en forma de campo eléctrico.

**INDUCTORES**

Los inductores son elementos pasivos como las resistencias y capacitores pero, que tienen la característica de almacenamiento de energía en forma de campo magnético. Tambien es una bobina de alambre que tiende a mantener su campo magnético.

En serie

Este va actuar de una manera similar, al de las resistencias ya conocidas.

![alt text](https://github.com/Crislml/Practica-9/blob/master/Img/inductores%20en%20serie.png)

Fig 1. Inductores en serie.

Para Calcular Leq, este sera la sumatoria de todos los elementos en serie.

Leq=L1+L2+L3+...+ln


En paralelo

Este, de igual forma, actuará de manera similiar al de las resistencias ya conocidas.

![alt text](https://github.com/Crislml/Practica-9/blob/master/Img/inductores%20en%20paralelo.png)

Fig 2. Inductores en paralelo.

Para calcular Leq, seguirá siendo una sumatoria pero no igual a las que estan en serie.

1/leq=1/L1 +1/L2 +...+1/ln

**CAPACITORES**

Un capacitor es un elemento pasivo diseñado para almacenar energía en su campo eléctrico. Junto con los resistores, los componentes eléctricos más comunes son los capacitores, los cuales son de amplio uso en electrónica.

En serie

Aquí, estos capacitores en serie, no actuaran de manera similar, sino de manera inversa al de las resistencias conocidas.

![alt text](https://github.com/Crislml/Practica-9/blob/master/Img/Capacitores%20en%20serie.png)

Fig 3. Capacitores en serie.

Para calcular Ceq, aplicamos la siguiente formula:

1/Ceq=1/C1 +1/C2 +...+1/Cn

En paralelo

En paralelo, los capacitores como actúan de manera inversa a los resistores, es la sumatoria de todas.

![alt text](https://github.com/Crislml/Practica-9/blob/master/Img/Capacitores%20en%20paralelo.png)

Fig 4. Capacitores en paralelo.

Para calcular Ceq, aplicamos la siguiente formula:

Ceq=C1+C2+...+Cn

**REACTANCIA**

Reactancia inductiva.

La reactancia inductiva (XL) es la capacidad que tiene un inductor para reducir la corriente en un circuito de corriente alterna y su modelo matemático es :

![alt text](https://github.com/Crislml/Practica-9/blob/master/Img/Reactancia%20inductiva.png)

Reactancia capacitiva.

La reactancia capacitiva (XC) es la propiedad que tiene un capacitor para reducir la corriente en un circuito de corriente alterna y su modelo matemático es :

![alt text](https://github.com/Crislml/Practica-9/blob/master/Img/reactancia%20capacitiva.png)


**INDUCTANCIA**

La inductancia es la propiedad de un circuito eléctrico para resistir el cambio de corriente. Una corriente que fluye a través de un cable tiene un campo magnético alrededor.

![alt text](https://github.com/Crislml/Practica-9/blob/master/Img/inductancia.png)


## *PROCEDIMIENTO*

1. Construya en el protoboard el circuito mostrado en la Figura 1.

![alt text](https://github.com/Crislml/Practica-9/blob/master/Img/Circuito%20con%20capacitores.png)

Figura 1.  Calculos de distintos parámetros eléctricos.

a. Utilice el osciloscopio para observar el voltaje 𝑉𝑜 variando la frecuencia entre los
valores de 0, 10, 50, 100, 500, 1000 𝐻𝑧. Anote los valores pico de las ondas observadas.

b. Utilice un multímetro para medir el voltaje 𝑉𝑜 variando la frecuencia entre los valores
de 0, 10, 50, 100, 500, 1000 𝐻𝑧. Anote los resultados.

c. Utilice un multímetro para medir la corriente que atraviesa la resistencia variando la
frecuencia entre los valores 0, 10, 50, 100, 500, 1000 𝐻𝑧. Anote los resultados.

2. Construya el circuito mostrado en la Figura 2
Realice las mismas mediciones de los ítems del numeral anterior y presente los resultados.

![alt text](https://github.com/Crislml/Practica-9/blob/master/Img/Circuito%20con%20inductores.png)

Figura 2.  Calculos de distintos parámetros eléctricos.

## *Ecuaciones*

Las ecuaciones en esta sección serán exclusivamente de la interpretación gráfica senoidal, obteniendo las siguientes formulas:

Frecuencia angular (W)

W=2πf

Frecuencia (f)

f=1/T

Ecuación de la onda:

V(t)=VpSen(wt+θ)

La amplitud vendría a ser el valor pico que alcanza la onda (Vp)

Fase:

Vendría a ser lo que se desplaza la onda en θ y sus unidades (radianes)

Pero si queremos la ecuación en forma de coseno tenemos:

V(t)=VpCos(Wt+θ+π/2).

Ecuación para determinar el voltaje o período a partir del número de divisiones y la escala.

![alt text](https://github.com/Crislml/Practica-7/blob/master/Imagenes/Ecuaci%C3%B3n.png)

## *DIAGRAMA*

![alt text]()

Figura 6. Circuito implementado con osciloscopio.

 **EXPLICACIÓN DEL CIRCUITO**

En el caso de nuestro circuito RC, tenemos dos capacitores en paralelo, los cuales estarán conectados en serie con una resistencia, y esta con una fuente de voltaje alterno. En nuestra fuente tendremos una frecuencia variable, al tener nosotros una frecuencia de 0, tendremos en teoría una fuente DC, por lo cual en los capacitores se producirá un cortocircuito y no abra flujo de corriente. En los otros valores de frecuencia, tendremos determinados valores de corriente en nuestra resistencia, y diferencia de tensión en nuestros capacitores que nos permitirán responder nuestras preguntas y sacar nuestras conclusiones.


En cambio, en el circuito RL, tenemos dos inductores en paralelo, los cuales están en serie con nuestra resistencia, la cual está alimentada de una fuente de voltaje alterna con frecuencia variable. En el caso de que la frecuencia vale 0, tendremos, teóricamente una fuente DC, por lo cual el inductor actuará como cable, y tendremos un flujo de corriente máximo. Con los otros valores de la frecuencia, podremos calcular nuestros respectivos datos, que la igual que en nuestro capacitor, nos permitirá responder nuestras preguntas y sacar las debidas conclusiones.

## *ANÁLISIS DE RESULTADOS*
**Comparación de voltajes**

En general los resultados de las mediciones nunca serán exactas, a pesar del máximo cuidado que se tenga en el momento de realizar cada una de ellas, no es posible expresar el reultado como exacto, es por esto que a continuación se ha realizado el cálculo del error relativo del voltaje obtenido del osciloscopio con respecto al valor resultante de la medición del multímetro de voltaje en los capacitores e inductores. En nuestro caso consideraremos el resultado del multímetro como el valor teórico.

Para el calculo del voltaje Vo se ha realizado la división del voltaje pico para raíz de dos para encontrar el voltaje rms y compararlo con el valor del multímetro.

Error relativo = |(Valor teórico - Valor experimental)/ Valor teórico | x 100%



| Frecuencia (Hz) | Voltaje pico (V) | Vo osciloscopio (V) | Vo multímetro (V) | % Error |
|:---------------:|------------------|---------------------|-------------------|---------|
| 0               | 9.98             | 7.0569              | 7.112             | 0.75    |
| 10              | 9.42             | 6.66                | 6.71              | 0.74    |
| 50              | 8.44             | 5.968               | 6.081             | 1.86    |
| 100             | 6.2              | 4.3841              | 4.551             | 3.67    |
| 500             | 1.56             | 1.1031              | 1.168             | 5.56    |
| 1000            | 0.796            | 0.5628              | 0.587             | 4.12    |

Tabla 2. Comparación de voltajes en circuito con capacitores.


| Frecuencia (Hz) | Voltaje pico (V) | Vo osciloscopio (V) | Vo multímetro (V) | % Error |
|:---------------:|------------------|---------------------|-------------------|---------|
| 0               | 0.309            | 0.2185              | 0.221             | 1.13    |
| 10              | 0.314            | 0.222               | 0.225             | 1.13    |
| 50              | 1.56             | 1.1031              | 1.103             | 0.009   |
| 100             | 2.97             | 2.1001              | 2.094             | 0.29    |
| 500             | 8.33             | 5.8902              | 5.828             | 1.07    |
| 1000            | 9.48             | 6.7034              | 6.606             | 1.47    |


Tabla 3. Comparación de voltajes en circuito con inductores.

**Cálculo de reactancia**

![alt text](https://github.com/Crislml/Practica-9/blob/master/Img/Tabla%20capacitancia.png)

Tabla 4. Reactancia en capacitores y capacitancia equivalente.


![alt text](https://github.com/Crislml/Practica-9/blob/master/Img/Tabla%20inductancia.png)

Tabla 5. Reactancia inductores e inductancia equivalente.


## *PREGUNTAS*

1. Justifique los errores cometidos en las mediciones.

El principal error se debe a los instrumentos de medición utilizados, en este caso el multímetro nos dará un valor mucho más preciso, mientras que en el osciloscopio es mucho más probable que haya un error de lectura ya que debemos tomar en uenta la escala utilizada y la cantidad de cuadros en el caso de la medición del voltaje. 

2. ¿Cómo se comportan la bobina y el capacitor en corriente continua (cero Hz)?

En el caso de de la bobina, su comportamiento dentro del circuito es como el de un cortocircuito, donde fluirá la corriente normalmente. Mientras que para el caso del capacitor cuando la frecuencia es igual a 0 Hz se observa que existe un comportamiento de circuito abierto, por lo que no habrá flujo de corriente por el componente.

3. ¿Cómo se comportan la bobina y el capacitor en corriente alterna?

La bobina en corriente alterna se comporta algo similar a la resistencia, ya que se opone al flujo de la corriente, su principal diferencia es que este valor de oposición se conoce como reactancia inductiva, la cual hemos calcula con la ley de ohm, donde X = V/I. En el capacitor se obtiene un comportamiento diferente, ya que el voltaje que se obtiene entre los terminales nos muestra que este voltaje está desfasado o adelantado 90 grados, esto ocurre principalmente porque el capacitor se opone a cambios bruscos que ocurren entres sus terminales.

4. ¿Qué cree usted que ocurriría con el voltaje 𝑉𝑜 y la corriente de la resistencia en los
circuitos analizados en esta práctica, si se utilizan dos bobinas o dos capacitores de valores
distintos?

Se observaría una variación tanto el el voltaje como en la corriente, ya que reactancia del capacitor o inductor equivalente cambiará.

Como ya sabemos que por la ley de ohm X=V/I, podemos decir que el voltaje cambiará de manera proporcional a la reactancia y la corriente cambiará de forma inversamente proporcional a la reactancia.


5. ¿Qué son los valores eficaces de voltaje y corriente?
 
Los valores eficaces corresponden a  los valores RMS, Raíz Media Cuadrática, que representan un valor equivalente, ya sea de voltaje o de corriente, que producirá el mismo efecto de disipación de calor en corriente directa. En nuestro circuito hemos obtenido el voltaje pico con ayuda del osciloscopio, para convertirlo en un valor rms tendremos que dividirlo para la raíz de dos, en el caso del multímetro no hay problema alguno debido a que este ya nos da el valor rms directamente.



## *CONCLUSIONES*

- Se ha comprendido el comportamiento de las bobinas y capacitores en corriente directa, donde se determinó que en un capacitor el comportamiento es parecido al de un circuito abierto, mientras que para la bobina el comportamiento se asemeja al de un cortocirctuio. Además fue posible evidenciar otros comportamiento de estos componentes cuando es usada la corriente alterna.

- Se determinó distintos valores de reactancia dependiendo de el componente usado y se comprendió como se calcula la capacitancia equivalente en un circuito en serie y paralelo. Para los capacitores en paralelo se suman las capacitancias mientras que para las bobinas, el recíproco de la inductancia equivalente será la suma algebraica de los rec;iprocos de las inductancias individuales.

- Se han determinado distinto errores entre entre los voltajes, ya que existe un error de lectura frente al osciloscopio, además de que el coltaje rms calculado es una medida indirecta, mientras que el multímetro nos da un valor rms mejor aproximado.

## *RECOMENDACIONES*

1. Para realizar una práctica exitosa se debe tener conocimiento previo adquirido, principalmente entender perfectamente como funciona la corriente alterna y directa.

2. En el momento de obtener los datos sobre los voltajes, no hay que confundir el  voltaje rms con el voltaje Pico.

3. Tener cuidado al momento de aproximar los valores que calculamos teóricamente ya que si lo hacemos mal , nos dará un porcentaje de error más alto de lo esperado.

4. Realizar paso a paso la práctica, siguiendo en orden el prodecimiento ya establecido en las guías de laboratorio, para así no cometer errores. 


## *CRONOGRAMA*

![alt text](https://github.com/Crislml/Practica-9/blob/master/Cronograma/Cronograma%20de%20actividades.png)

## *BIBLIOGRAFÍA*

Charles K. Alexander, Matthew N. O. Sadiku, Fundamentos de circuitos eléctricos. Tercera edición. México: McGrawHill, 2004.

Lifeder, Onda senoidal. Recuperado de: https://www.lifeder.com/onda-senoidal/

## *ANEXOS*

![alt text](https://github.com/Crislml/Practica-9/blob/master/Img/Calculos1.png)

Figura 7.  Calculo errores.


![alt text](https://github.com/Crislml/Practica-9/blob/master/Img/calculos2.png)

Figura 7.  Calculo reactancia.

