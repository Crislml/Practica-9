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
|  1 | Osciloscopio  |
| 1  | Multímetro digital |
|  1 | Resistor de 100 Ω |
|   2 | Capacitores de 10 µF |
|  2  | Inductores de 10m mH |

Tabla 1. Materiales
## *MARCO TEÓRICO*

**CORRIENTE DIRECTA Y ALTERNA**

**INDUCTORES**

En serie

En paralelo

**CAPACITORES**

En serie

En paralelo

**REACTANCIA**

**INDUCTANCIA**

**USO DEL OSCILOSCOPIO**


## *PROCEDIMIENTO*

1. Construya en el protoboard el circuito mostrado en la Figura 1.

![alt text]()

Figura 1.  Calculos de distintos parámetros eléctricos.

a. Utilice el osciloscopio para observar el voltaje 𝑉𝑜 variando la frecuencia entre los
valores de 0, 10, 50, 100, 500, 1000 𝐻𝑧. Anote los valores pico de las ondas observadas.

b. Utilice un multímetro para medir el voltaje 𝑉𝑜 variando la frecuencia entre los valores
de 0, 10, 50, 100, 500, 1000 𝐻𝑧. Anote los resultados.

c. Utilice un multímetro para medir la corriente que atraviesa la resistencia variando la
frecuencia entre los valores 0, 10, 50, 100, 500, 1000 𝐻𝑧. Anote los resultados.

2. Construya el circuito mostrado en la Figura 2
Realice las mismas mediciones de los ítems del numeral anterior y presente los resultados.

![alt text]()

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

![alt text]()

## *BIBLIOGRAFÍA*

Charles K. Alexander, Matthew N. O. Sadiku, Fundamentos de circuitos eléctricos. Tercera edición. México: McGrawHill, 2004.

Lifeder, Onda senoidal. Recuperado de: https://www.lifeder.com/onda-senoidal/

## *ANEXOS*

![alt text]()

Figura 7.  Calculos de distintos parámetros eléctricos.
