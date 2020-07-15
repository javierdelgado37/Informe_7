# INFORME Nº5 TEOREMA DE THÉVENIN
AUTORES: DAVID HINOJOSA,
         JAVIER DELGADO,
         JULIO ROSERO.

## 1. PLANTEAMIENTO DEL PROBLEMA
Al momento de diseñar circuitos, en ocasiones nos encontramos con resistencias que pueden variar, durante el desarrollo del circuito, por lo que es importante saber transformar un circuito complejo a uno más simple que sea equivalente, aplicando el teorema de Thevenin, sin embargo, se debe contar con conocimiento previo en resolucion de circuitos por mallas y nodos.

## 2. OBJETIVOS
### GENERAL

Encontrar el circuito equivalente de Thevenin para el resistor 5.

### ESPECÍFICOS

Determinar el voltaje y corriente del resistor 5.

Determinar la resistencia de Thevenin para el resistor 5.

Determinar el voltaje de Thevenin para el resistor 5.

Determinar la corriente de Thevenin para el resistor 5.

Comparar los valores obtenidos en el circuito de Thevenin y el circuito original.

Determinar el error experimental.

## 3. MARCO TEÓRICO 

El teorema de Thevenin nos sirve para convertir un circuitos complejo a uno más simple, encontrando un voltaje y una resistencia que hagan este circuito equivalente, denominados como voltaje de Thevenin y resistencia de Thevenin respectivamente. Sadiku (2004) afirma:

"El teorema de Thevenin establece que un circuito lineal de dos terminales puede remplazarse por un circuito equivalente que consta de una fuente de tensión VTh en serie con un resistor RTh, donde VTh es la tensión de circuito abierto en las terminales y RTh es la entrada o resistencia equivalente en las terminales cuando las fuentes independientes se apagan". pag(139)

![teo](https://user-images.githubusercontent.com/64505672/87502309-e322ff80-c626-11ea-8e00-5b545140122e.PNG)

EL proceso a seguir para encontrar el circuito equivalente es el siguiente:

1) Se anulan todas las fuentes y se quita la resistencia que actua como terminal, ahora se calcula la resistencia de ese circuito. Esta sera la resistencia de Thevenin.
2) Se prenden las fuentes y se calcula el voltaje del circuito, considerando que la resistencia que actua como terminal no se toma en cuenta. Este voltaje es el voltaje de Thevenin.
3) Se reeplantea el circuito tomando como fuente al voltaje de Thevenin, se coloca en serie la resistencia de Thevenin y la resistencia del terminal. El voltaje que cae sobre la resistencia del terminal se lo obtiene facilmente utilizando divisor de voltaje y la corriente se la obtiene aplicando la ley de Ohm. 


## 4. DIAGRAMAS



![chrome_RB7j3LYyof](https://user-images.githubusercontent.com/66037763/87493730-1196df80-c613-11ea-952b-1663cdba35ba.png)



El circuito base otorgado en la guía de la práctica, en este se describe de que manera están distribuidos los componentes eléctricos y sus respectivos valores. Facilita de gran manera el reconocer la resistencia que se removerá para aplicar el teorema.



![fVZ6vry9mI](https://user-images.githubusercontent.com/66037763/87501391-95a59300-c624-11ea-80c6-b3645eed8ec2.png)



En la parte derecha, encerrado en rojo, se encuentra la resistencia que se ignorará al hacer el respectivo análisis por medio del teorema de Thévening. Encerrado en rectángulos se encuentran las fuentes del circuito, las cuales apagaremos para buscar la resistencia de Th. 



## 5. LISTA DE COMPONENTES
A. 2 Fuentes de Voltaje de C.D.


![chrome_FxjHlWp3kM](https://user-images.githubusercontent.com/66037763/84236034-96df1f80-aabc-11ea-9159-3d2235bc315b.png)


B. 2 Multímetros Digitales

![Multimetro](https://user-images.githubusercontent.com/66037763/86204443-252f4a00-bb2d-11ea-8508-0edf4c96af71.png)


C. Resistor de 1 kΩ


![chrome_gxIw13c1Q1](https://user-images.githubusercontent.com/66037763/86204259-aafec580-bb2c-11ea-9077-c7547372cc76.png)


D. Resistor de 560 Ω


![chrome_Ih8MAuGPLY](https://user-images.githubusercontent.com/66037763/87492914-40ac5180-c611-11ea-92f2-1ac0009fb676.png)



E. Resistor de 4.7 kΩ



![chrome_U2pfjesE6R](https://user-images.githubusercontent.com/66037763/87492962-59b50280-c611-11ea-9627-ce1b74b186de.png)



F. Resistor de 330 Ω



![chrome_V3LCaMSZyo](https://user-images.githubusercontent.com/66037763/87492992-6fc2c300-c611-11ea-9f3f-0836bb10c9bc.png)



G. Resistor de 100 Ω


![chrome_wn2rPVIKdK](https://user-images.githubusercontent.com/66037763/87493052-908b1880-c611-11ea-9e11-f4636f495820.png)



H. Protoboard


![chrome_gnkRWUT4Si](https://user-images.githubusercontent.com/66037763/84236208-e9b8d700-aabc-11ea-9985-2e94ef9d6adb.png)




## 6. DESCRIPCION DE PREREQUISITOS Y CONFIGURACION
Tabla 1.  Medición de voltaje y resistencia de Thévenin
|                    | Voltaje de Thévenin (Vth) | Resistencia de  Thévenin (Rth) |
|           ---      |             ---           |                  ---           |     
|     Calculado      |                           |                                |       
|      Medido        |                           |                                |       

Tabla 2.  Medición de voltaje y corriente en el circuito original y aplicando el teorema Thévenin
| PARÁMETRO ELÉCTRICO |   Circuito Original  |    Circuito Original    |   Circuito equivalente de Thevenin   |      Circuito equivalente de Thevenin       |
|           ---       |        ---           |             ---         |           ---                        |                        ---                  |
|           ---       |      Calculado       |      Medido             |              Calculado               |              Medido                         |  
|      Voltaje        |                      |                         |                                      |                                             |
|      Corriente      |                      |                         |                                      |                                             |



## 7. CRONOGRAMA





## 8. CONCLUSIONES
-El voltaje de Thevenin nos permite reducir un circutio complejo a uno mas sencillo de analizar como se pudo comprobar al realizar los calculos.

-Se comprobó que el voltaje de Thevenin es el mismo que cae sobre la resistencia de 330ohms, y se debe a que se encuentran en paralelo con las terminales sobre las cuales se calculo el voltaje de Thevenin.

-Se  compróbo que el valor obtenido del voltaje de Thevenin de forma experimental es muy cercano al calculado con un error del 0,011%


## 9. RECOMENDACIONES

-Para tomar el voltaje de Thevenin, conectar el multímetro en serie.

-Armar el circuito de una forma didáctica para que todos puedan entender el funcionamiento del mismo.

-Hacer las respectivas mediciones con cuidado para no obtener datos errónes y que esto no afecte nuestra practica.





## 10. BIBLIOGRAFÍA

-M.Sadiku, C.Alexander, Fundamentos de circuitos eléctricos (3ra Edición), 2004.

-Allan, H.Robbins, Análisis de Circuitos. Teoría y práctica(4ta Edición), 2008.
