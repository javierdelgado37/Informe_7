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


![chrome_rP150X7ps5](https://user-images.githubusercontent.com/66037763/90582332-0fd0b680-e193-11ea-92eb-9da54c06277f.png)



Circuito base con el que se realiza la respectiva implementación en el software Tinkercad. Se puede observar claramente que la alimentación es de corriente alterna gracias a la simbología utilizada en la fuente, de igual manera la resistencia donde se realizan las respectivas mediciones la cual es denominada RL. 




## 5. LISTA DE COMPONENTES
A. 1 Generador de Funciones


![chrome_LUEFWCOVi0](https://user-images.githubusercontent.com/66037763/90581763-a1d7bf80-e191-11ea-9e2b-1254612c8019.png)



B. 1 Multímetros Digitales

![Multimetro](https://user-images.githubusercontent.com/66037763/86204443-252f4a00-bb2d-11ea-8508-0edf4c96af71.png)


C. Resistor de 1 kΩ


![chrome_gxIw13c1Q1](https://user-images.githubusercontent.com/66037763/86204259-aafec580-bb2c-11ea-9077-c7547372cc76.png)



C. Resistor de 2.2 KΩ



![chrome_jqUtFL63t1](https://user-images.githubusercontent.com/66037763/90581829-d77ca880-e191-11ea-9959-dccbc9f60745.png)



D. Protoboard


![chrome_gnkRWUT4Si](https://user-images.githubusercontent.com/66037763/84236208-e9b8d700-aabc-11ea-9985-2e94ef9d6adb.png)




E. Oscilosciopio



![chrome_p6hVOC777I](https://user-images.githubusercontent.com/66037763/90581876-f2e7b380-e191-11ea-8fed-2af53bdc9daa.png)




## 6. DESCRIPCION DE PREREQUISITOS Y CONFIGURACION


![chrome_cscwVMl5uJ](https://user-images.githubusercontent.com/66037763/90583799-b79bb380-e196-11ea-942b-9e39c3c68db1.png)


Circuito ensamblado y en funcionamiento. Los equipos de medición se encuentran instalados de tal manera que se visualiza en el osciloscopio la forma de la onda mientras que en el multímetro se visualiza el voltaje que pasa por la resistencia en ese instante. 


PREGUNTAS:

-¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida? 
La amplitud de la onda abarca aproximadamente 3 y 1/3 de cuadrados (medidos desde el eje de abscisas).

-¿En qué valor está posicionada la perilla VOLTS/DIV?

![image](https://user-images.githubusercontent.com/66037763/90584790-04808980-e199-11ea-9b35-bb3282caddd8.png)

Esta perilla se suele encontrar en el ajuste vertical de los osciloscopios, sirve para aumentar o disminuir la amplitud de onda y en el presente caso se encuentra en 10 ya que dentro de las instrucciones dictadas se condiciona que existe una amplitud de pico a pico de 20 Vpp (V. peak to peak).


-¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida? 
Un ciclo completo abarca exactamente 4 cuadrados.


-¿En qué valor está posicionada la perilla TIME/DIV?


![chrome_IEFhnAMj3g](https://user-images.githubusercontent.com/66037763/90586259-5ecf1980-e19c-11ea-9d08-ed1190bab00a.png)


El tiempo por división se encuentra en 100 µs, este define las divisiones en la anterior pregunta. 


-. ¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla del osciloscopio?
La amplitud se encuentra entre 6 y 8 V. Esto es visible ya que dentro de la escala propuesta por el software, existen 5 divisiones de cuadrados en los 10 voltios que se presentan de amplitud. El periodo de la pantalla corresponde a 400 µs, siguiendo el mismo análisis previamente mencionado y al valor en la perilla TIME/DIV (recordar que 1 ms equivale a 1000 µs).

![image](https://user-images.githubusercontent.com/66037763/90585559-be2c2a00-e19a-11ea-8391-305d84e625bf.png)

RESULTADOS

1) Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de
salida
f = 2500 Hz
w = 5k π rad/s
(revisar hoja de cálculos)

2) Con el multímetro digital mida el voltaje de salida en RL:
https://media.giphy.com/media/f8hhHypbZ3YY4vvZcc/giphy.gif


3) Compare el voltaje medido en el punto 1) y el obtenido en el punto 2)
¿Coinciden? _______ ¿Por qué? 

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
