# Práctica 9
# *INDUCTOR Y CAPACITOR*
## *PLANTEAMIENTO DEL PROBLEMA*


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

Nuestro circuito consta de una fuente alterna, que será nuestro generador de funciones, dos resistencias, una de 1000 ohmios, y la segunda que será nuestra resistencia L, que será de 2200 ohmios. Al tener una fuente de voltaje alterno, tendremos como resultado una función sinusoidal, es decir que la gráfica de dicho voltaje describirá la función seno.

Al momento de implementar nuestra fuente, debemos tener en cuenta y fijarnos que la fuente este puesta en voltaje pico a pico, ya que este ese el valor que nos dan como dato, que es de 20 voltios. 

Para tomar las respectivas mediciones, deberemos utilizar nuestro osciloscopio ya que estamos trabajando con señal alterna. Al momento de conectar el osciloscopio, vemos perillas que indican cuantos voltios equivalen por cada cuadro que está presente en nuestro gráfico, que serán 3 cuadros por cada voltio, en donde vemos que, la amplitud de nuestro circuito será de 4.6, ya que se toma en cuenta dos veces el 2.3 que tenemos en nuestra primera cresta. Con ello podemos calcular nuestro Voltaje pico, y a partir de este procederemos a calcular el Voltaje RMS, que será el voltaje pico dividido para la raíz de 2.

## *PREGUNTAS*

1. Justifique los errores cometidos en las mediciones.



2. ¿Cómo se comportan la bobina y el capacitor en corriente continua (cero Hz)?



3. ¿Cómo se comportan la bobina y el capacitor en corriente alterna?



4. ¿Qué cree usted que ocurriría con el voltaje 𝑉𝑜 y la corriente de la resistencia en los
circuitos analizados en esta práctica, si se utilizan dos bobinas o dos capacitores de valores
distintos?




5. ¿Qué son los valores eficaces de voltaje y corriente?




## *ANÁLISIS DE RESULTADOS*
En general los resultados de las mediciones nunca serán exactas, a pesar del máximo cuidado que se tenga en el momento de realizar cada una de ellas, no es posible expresar el reultado como exacto, es por esto que a continuación se ha realizado el cálculo del error relativo del voltaje obtenido del osciloscopio con respecto al valor resultante de la medición del multímetro de voltaje en la resistencia RL. En nuestro caso consideraremos el resultado del multímetro como el valor teórico.

| V. osciloscopio | V. multímetro |
| ------------- | ------------- |
|4.8225  V | 4.865 V  |

Error relativo = |(Valor teórico - Valor experimental)/ Valor teórico | x 100%

Error relativo = |(4.865 - 4.8225)/ 4.865 | x 100%

Error relativo = 0.87 %



## *CONCLUSIONES*



## *RECOMENDACIONES*
1. Para realizar una práctica exitosa se debe tener conocimiento previo adquirido, principalmente entender perfectamente como es una onda senoidal.

2. En el momento de obtener los datos sobre los voltajes, no hay que confundir el  voltaje rms con el voltaje Pico.

3. Tener cuidado al momento de aproximar los valores que calculamos teóricamente ya que si lo hacemos mal , nos dará un porcentaje de error más alto de lo esperado.

4. Realizar paso a paso la práctica, siguiendo en orden el prodecimiento ya establecido en las guías de laboratorio, para así no cometer errores. 


## *CRONOGRAMA*

![alt text](https://github.com/Crislml/Practica-9/blob/master/Cronograma/Cronograma%20de%20actividades.png)

## *BIBLIOGRAFÍA*

Charles K. Alexander, Matthew N. O. Sadiku, Fundamentos de circuitos eléctricos. Tercera edición. México: McGrawHill, 2004.

Lifeder, Onda senoidal. Recuperado de: https://www.lifeder.com/onda-senoidal/

## *ANEXOS*

![alt text]()

Figura 7.  Calculos de distintos parámetros eléctricos.
