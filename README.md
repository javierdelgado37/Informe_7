# INFORME Nº7 CARACTERÍSTICAS DE LA ONDA SENOIDAL 
AUTORES: DAVID HINOJOSA,
         JAVIER DELGADO,
         JULIO ROSERO.

## 1. PLANTEAMIENTO DEL PROBLEMA
A pesar de que la corriente directa es mas fácil de entender y de realizar cálculos, la mayoria de circuitos, sobretodo en la distribución eléctrica en las ciudades, es decir,  la forma en la que llega la electricidad en nuestros hogares, el voltaje llega en corriente alterna, por su eficiencia y su poco gasto económico.

## 2. OBJETIVOS
### GENERAL

- Determinar experimentalmente las características de señales senoidales.

### ESPECÍFICOS

- Realizar una la simulación de un circuito con corriente alterna.

- Observar y analizar el comportamiento de la corriente en el resistor RL del circuito.

- Responder las preguntas de la guía.

## 3. MARCO TEÓRICO 

### Corriente Alterna (Onda Senoidal)

La corriente alterna o senoidal, es el tipo de corriente que se utiliza en la distribución de energia en las ciudades, ya que es la más eficiente y econámica. Con respecto a este tema Sadiku menciona:

"Una corriente senoidal se conoce usualmente como corriente alterna (ca). Esta corriente se invierte a intervalos regulares y tiene valores alternadamente positivo y negativo. Los circuitos excitados por fuentes de corriente o tensión senoidal se llaman circuitos de ca. Una senoide es una señal que tiene la forma de la función seno o coseno" pag 370

La expresión más general para representar una función senoidal es

![image](https://user-images.githubusercontent.com/64505672/90580782-502e3580-e18f-11ea-947c-04ef7b2185bc.png)

donde vm es la amplitud del voltaje, w es la frecuencia angular, t es el tiempo y phi es la fase de la onda.

Aqui se puede observar dos ondas con diferente fase.

![image](https://user-images.githubusercontent.com/64505672/90580911-9b484880-e18f-11ea-9947-a62d8edc38fc.png)
 
 Es necesario saber que una onda senoidal tambien puede representarse como una funcion coseonidal considerando un angulo de desfase de 180 grados.
 Aqui se puede observar las conversiones trigonometricas que pueden ser útiles.
 
 ![image](https://user-images.githubusercontent.com/64505672/90581092-08f47480-e190-11ea-8870-c1b416981f52.png)


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
|     Calculado      |            5.055 v        |                298.855 Ω       |       
|      Medido        |            5.06 v         |                299   Ω         |       

Tabla 2.  Medición de voltaje y corriente en el circuito original y aplicando el teorema Thévenin
| PARÁMETRO ELÉCTRICO |   Circuito Original  |    Circuito Original    |   Circuito equivalente de Thevenin   |      Circuito equivalente de Thevenin       |
|           ---       |        ---           |             ---         |           ---                        |                        ---                  |
|           ---       |      Calculado       |      Medido             |              Calculado               |              Medido                         |  
|      Voltaje        |         3.893 v      |         3.89 v          |             3.893 v                   |                  3.85 v                     |
|      Corriente      |         3.893 mA     |         3.89 mA         |             3.893 mA                  |                  3.85 mA                    |


![vcricnormal](https://user-images.githubusercontent.com/66037763/87504718-d86b6900-c62c-11ea-9211-1636f60011e4.png)


Circuito original, se mide en el multímetro el voltaje que fluye por la resistencia 5.


![vequivalentethevenin](https://user-images.githubusercontent.com/66037763/87504782-fb961880-c62c-11ea-8af4-d6c13f025f91.png)


El circuito equivalente de Thévenin, se mide en el multímetro el voltaje que fluye por la resistencia.


![vthevenin](https://user-images.githubusercontent.com/66037763/87504812-0cdf2500-c62d-11ea-9ce9-7a66b70cc06e.png)


Circuito removiendo R5, oteniendo de tal manera el voltaje de Thévenin. 


![resis](https://user-images.githubusercontent.com/66037763/87504837-1799ba00-c62d-11ea-9f85-d0f8fcb43562.png)


Resistencia de Thévenin, donde se apagan las fuentes y en el lugar de R5 se pone el multímetro.

Finalmente, los errores respectivos a los resultados calculados son:


![chrome_9W8ZZ1xiE7](https://user-images.githubusercontent.com/66037763/87513623-9fd48b00-c63e-11ea-897b-b21f6a18d23a.png)



## 7. CRONOGRAMA
![0064](https://user-images.githubusercontent.com/66037557/87512435-9ea25e80-c63c-11ea-867b-50dd98a3fd8f.png)

## 8. CONCLUSIONES
-El voltaje de Thevenin nos permite reducir un circutio complejo a uno mas sencillo de analizar como se pudo comprobar al realizar los calculos.

-Se cobservo que el voltaje de Thevenin es el mismo que cae sobre la resistencia de 330ohms, y se debe a que se encuentran en paralelo con las terminales sobre las cuales se calculo el voltaje de Thevenin.

-Se compróbo que el valor obtenido del voltaje de Thevenin de forma experimental es (5.050V) muy cercano al calculado (5.056v)
con un error del 0,011%.

-Se comprobó que el valor del Voltaje de Thevenin con respecto del medido es del 1.03%, este se debe a que el software no nos permite colocar todas cifras de la resistencia y voltaje medido de Thevenin .


## 9. RECOMENDACIONES

-Armar el circuito de una forma didáctica para que todos puedan entender el funcionamiento del mismo.

-Hacer las respectivas mediciones con cuidado para no obtener datos errónes y que esto no afecte nuestra practica.



## 10. BIBLIOGRAFÍA

-M.Sadiku, C.Alexander, Fundamentos de circuitos eléctricos (3ra Edición), 2004.

-Allan, H.Robbins, Análisis de Circuitos. Teoría y práctica(4ta Edición), 2008.
