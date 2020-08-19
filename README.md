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

- Realizar una simulación de un circuito con corriente alterna.

- Observar y analizar el comportamiento del voltaje en el resistor RL del circuito.

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


![image](https://user-images.githubusercontent.com/66037763/90594013-08b7a180-e1af-11ea-9043-0a27f2922117.png)


Circuito ensamblado y en funcionamiento. 


PREGUNTAS:

-¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida? 


![image](https://user-images.githubusercontent.com/66037763/90596788-5e8f4800-e1b5-11ea-82f8-39cd78a5a334.png)


La amplitud de la onda abarca 1 y 1/3 cuadrados (medidos desde el eje de abscisas).


-¿En qué valor está posicionada la perilla VOLTS/DIV?


![chrome_ctmXuTA3RS](https://user-images.githubusercontent.com/66037763/90596891-96968b00-e1b5-11ea-9471-36cbdd9df545.png)


Esta perilla se suele encontrar en el ajuste vertical de los osciloscopios, sirve para aumentar o disminuir la amplitud de onda y en el presente caso se encuentra en 5 ya que dentro de las instrucciones dictadas se condiciona que existe una amplitud de pico a pico de 20 Vpp (V. peak to peak).


-¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida? 

Un ciclo completo abarca exactamente 4 cuadrados.


-¿En qué valor está posicionada la perilla TIME/DIV?


![image](https://user-images.githubusercontent.com/66037763/90597120-0ad12e80-e1b6-11ea-9672-9935c680a80c.png)


El tiempo por división se encuentra en 100 µs, este define las divisiones en la anterior pregunta. 


RESULTADOS

1) ¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla del osciloscopio?

La amplitud es mayor a 5 V. Esto es visible en las imágenes previamente mostradas ya que una división por cuadro representa 5 V y esta ocupa 1/3 de más. El periodo de la pantalla corresponde a 400 µs, siguiendo el mismo análisis previamente mencionado y al valor en la perilla TIME/DIV.

2) Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de salida

f = 2500 Hz

w = 5000 π rad/s (revisar hoja de cálculos)

3) Con el multímetro digital mida el voltaje de salida en RL:


![image](https://user-images.githubusercontent.com/66037763/90595735-1e2eca80-e1b3-11ea-9726-6b0046736735.png)


El voltaje en RL se encuentra en 4.861 V.

4) Compare el voltaje medido en el punto 1) y el obtenido en el punto 3) ¿Coinciden? ¿Por qué? 

No coinciden ya que el valor entregado por el osciloscopio corresponde al voltaje máximo pero no el eficáz, además hasta llegar a la resistencia RL, la corriente pasa por una resistencia de 1000 Ω y al estar en serie, no llega el mismo voltaje.


## 7. CRONOGRAMA
![0005](https://user-images.githubusercontent.com/66037557/90582678-f67c3a00-e193-11ea-8796-7a2c781216f8.png)


## 8. CONCLUSIONES
-Se observó en el oscilador que una señal senoidal se puede expresar matemáticamente como función del tiempo, donde podemos encontrar las características básicas como el valor eficaz, periodo, frecuencia, valor pico, amplitud y valor promedio. 

-Se midió un voltaje rms de 4.85 V en la resistencia Rl, que además se pudo comprobar analíticamente al realizar los cálculos respectivos con un error experimental  del 0.23%.


## 9. RECOMENDACIONES

-Armar el circuito de una forma didáctica para que todos puedan entender el funcionamiento del mismo.

-Hacer las respectivas mediciones con cuidado para no obtener datos errónes y que esto no afecte nuestra practica.

-Comprobar con un programa alternativo de mayor confianza como proteus.




## 10. BIBLIOGRAFÍA

-M.Sadiku, C.Alexander, Fundamentos de circuitos eléctricos (3ra Edición), 2004.

-Allan, H.Robbins, Análisis de Circuitos. Teoría y práctica(4ta Edición), 2008.
