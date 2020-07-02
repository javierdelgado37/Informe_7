# INFORME 4

AUTORES: DAVID HINOJOSA,
         JAVIER DELGADO,
         JULIO ROSERO.

## 1. PLANTEAMIENTO DEL PROBLEMA
Es importante contar con diferentes herramientas que nos sirvan para la resolucion de circuitos, previamente se estudio el analisis de mallas para obtener la corriente de una malla, el analisis de nodos para obtener el voltaje de un nodo y esta vez es el turno de la superposicion. Este metodo puede simplificar en gran medida los calculos que se realizan al analizar un circuito y nos sirve para obtener la corriente o tambien el voltaje, dependiendo de lo que se requiera.
## 2. OBJETIVOS
GENERAL

- Comprobar experimentalmente el Teorema de Superposición.

ESPECÍFICOS

- Armar el circuito indicado en el programa TinkerCad.

- Medir y calcular el voltaje y corriente indicado en la guia.

- Determinar el error en las mediciones.


## 3. MARCO TEÓRICO 
Si un circuito tiene dos o más fuentes independientes, una forma de determinar el valor de una variable específica (tensión o corriente) es determinar la contribución de cada fuente independiente a la variable y después sumarlas. Este último método se conoce como superposición. Sadiku (2004) dice:

  El principio de superposición establece que la tensión entre los extremos (o la corriente a través) de un elemento en un circuito lineal es la suma algebraica de las tensiones   (o corrientes) a través de ese elemento debido a que cada fuente independiente actúa sola. (p.130)

El principio de superposición ayuda a analizar un circuito lineal con más de una fuente independiente, mediante el cálculo de la contribución de cada fuente independiente por separado. 

![image](https://user-images.githubusercontent.com/64505672/86199459-ca432600-bb1f-11ea-885d-704b37e5f886.png)

Pasos para aplicar el principio de superposición:
1. Apague todas las fuentes independientes, excepto una. Determine la salida (tensión o corriente) debida a esa fuente activa, aplicando las técnicas cubiertas en los capítulos 2 y 3.
2. Repita el paso 1 en cada una de las demás fuentes independientes.
3. Halle la contribución total sumando algebraicamente todas las contribuciones debidas a las fuentes independientes.


## 4. DIAGRAMAS



![chrome_rwenS5IKRn](https://user-images.githubusercontent.com/66037763/86203161-ea77e280-bb29-11ea-8777-ae63bd163266.png)



El circuito base que nos enseña como están posicionados los componentes eléctricos para el respectivo ensamblaje del circuito en el protoboard. 



![CircuitoSuperposición](https://user-images.githubusercontent.com/66037763/86204933-5a886780-bb2e-11ea-9f76-262823f08566.png)



Podemos identificar el número de fuentes que tiene el circuito (2 en total, una en cada extremo) en las cuales se aplicará el método de superposición para 
encontrar el voltaje (VA) y la corriente (Ix) de una manera mas sencilla que en un análisis de mallas.

## 5. LISTA DE COMPONENTES
A. Fuente de Voltaje de C.D.


![chrome_FxjHlWp3kM](https://user-images.githubusercontent.com/66037763/84236034-96df1f80-aabc-11ea-9159-3d2235bc315b.png)


B. Multímetro Digital

![Multimetro](https://user-images.githubusercontent.com/66037763/86204443-252f4a00-bb2d-11ea-8508-0edf4c96af71.png)


C. Resistor de 1 kΩ


![chrome_gxIw13c1Q1](https://user-images.githubusercontent.com/66037763/86204259-aafec580-bb2c-11ea-9077-c7547372cc76.png)


D. Resistor de 2.2 kΩ


![chrome_VDgV5hnKS3](https://user-images.githubusercontent.com/66037763/86204472-34ae9300-bb2d-11ea-84d2-02c17b97de6a.png)


E. Resistor de 820 Ω


![chrome_i2Yob2vsmi](https://user-images.githubusercontent.com/66037763/86204372-f6b16f00-bb2c-11ea-8486-014eb547b11f.png)


F. Resistor de 470 Ω


![chrome_qyYohEcMxn](https://user-images.githubusercontent.com/66037763/86204405-09c43f00-bb2d-11ea-972d-91ed7bde2ee1.png)


H. Protoboard

![chrome_gnkRWUT4Si](https://user-images.githubusercontent.com/66037763/84236208-e9b8d700-aabc-11ea-9985-2e94ef9d6adb.png)


## 6. DESCRIPCION DE PREREQUISITOS Y CONFIGURACION
Tabla 1.  Medición de voltaje aplicando superposición
|                    | Voltaje Total (VA) | Voltaje (VA) [V2 = 0] | Votaje (VA) [V1 = 0] |
|           ---      |         ---        |     ---               |     ---              |
|     Calculado      |      951.9 mV      |         7.479 V       |       -6.527 V       | 
|      Medido        |      952 mV        |         7.480 V       |       -6.530 V       |

Tabla 2.  Medición de corriente aplicando superposición
|                    | Corriente Total (Ix) | Corriente (Ix) [V2 = 0] | Corriente (Ix) [V1 = 0]|
|           ---      |         ---          |                ---      |                ---     |
|     Calculado      |       25.53 mA       |            0 A          |          25.53 mA      | 
|      Medido        |       25.50 mA       |            0 A          |          25.50 mA      |

En las tablas 1 y 2 se puede comprobar claramente que las magnitudes de voltajes y corrientes obtenidos fueron precisos gracias a la similitud que los datos calculados tienen con los medidos. Por medio de estos se relizan los respectivos cálculos de errores incluidos en la hoja técnica, de igual manera en las conclusiones.

## 7. CRONOGRAMA
![0041](https://user-images.githubusercontent.com/66037557/86209632-9f190080-bb38-11ea-8124-2261b92d44ac.png)



## 8.CONCLUSIONES
-El Teorema de Superposición es una técnica que nos puede resultar práctica cuando tenemos circuitos varias fuentes de voltaje o corriente en un mismo circuito, pues nos simplifica el circuito, facilitando los calculos.

-Se comprobó que las sumas de los voltajes correspondientes a la resistencia de 820ohms de cada circuito simplificado es igual al voltaje en esa resistencia del circuito inicial, algebraicamente se tiene que el V= 7,48-6,53 = 0.95v.

-Se comprobó experimentalmente que en el circuito propuesto cumple con el Teorema de Superposición. A través de la comparación de los resultados obtenidos en la simulación y en  los cálculos donde se obtuvo un error de -0.010505% respecto al Voltaje Total y 0.1175% respecto a la Corriente que pasa por el resistor de 470 ohm.

-Se comprobó que la Ix=0 cuando cortociruitamos la fuente de 12V debido a que el voltaje tiende a 0 y por tanto la Ix también tiende 0.
## 9.RECOMENDACIONES

-Se debe tener en cuenta que cuando cortocircuitamos la fuente 2, esta puede influye en la intensidad provocando que Ix=0 .

-Armar el circuito de una forma didáctica para que todos puedan entender el funcionamiento del mismo.

-Hacer las respectivas mediciones con cuidado para no obtener datos errónes y que esto no afecte nuestra practica.






## 10. BIBLIOGRAFÍA

-M.Sadiku, C.Alexander, Fundamentos de circuitos eléctricos (3ra Edición), 2004.

-Allan, H.Robbins, Análisis de Circuitos. Teoría y práctica(4ta Edición), 2008.
