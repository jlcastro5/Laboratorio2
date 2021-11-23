# InformeLaboratorio
1. OBJETIVOS 

   Objetivo general
   
Demostrar de forma teórica y experimental la veracidad que tienen las leyes de Kirchhoff con respecto a los voltajes y las corrientes, todo esto se llevara a cabo mediante el desarrollo del presente laboratorio  que abordará el tema “Análisis de mallas”  de un circuito eléctrico mixto planteado por el tutor de la asignatura, para dicho desarrollo, se utilizara simuladores virtuales de circuitos eléctricos los cuales brindaran oportunidad de corroborar la exactitud de los datos teóricos obtenidos.

   Objetivos específicos
   
   * Comprender el uso de la ley de Kirchhoff y como aplicarlo dentro de un circuito mixto utilizando simuladores virtuales que permitan su corroboración o en su defecto permita la localización de fallas.
   * Identificar las diferencias obtenidas por medio de la ejecución de un circuito mixto, dichas respuestas serán obtenidas de manera teórica, experimental y de simuladores.
   * Conocer el comportamiento de la corriente dentro de diferentes mallas y como esta interactúa con los componentes que integran dichas mallas.
   
2. MARCO TEORICO

![](https://github.com/jlcastro5/Laboratorio2/blob/d03c08afc908b0b693f3a1ae63d49739c72b334f/MarcoT.jpeg)
  
3. EXPLICACION DEL PROCEDIMIENTO

 En este laboratorio vamos aplicar el analisis de malla para el siguiente circuito que contiene 5 resistencias y dos fuentes de voltaje.

 ![](https://github.com/jlcastro5/Laboratorio2/blob/d03c08afc908b0b693f3a1ae63d49739c72b334f/MALLA.PNG)   
 
 Figura 1. Circuito para el analisis de mallas

 Luego representamos el circuito en nuestro simulador de tinkercad colocando respectivamente cada valor de resistencia y de cada fuente de alimentacion los cuales podemos ver en la figura 2, que nos mostrara la corriente que pasa por dicho circuito.
 
 ![](https://github.com/jlcastro5/Laboratorio2/blob/c0dc82d8731b7fff5540030139e0f3190eea423a/PROTO.PNG)

 Figura 2. Protoboard 
 
 Analisis y dibujamos las corrientes que pasa en este circuito, la cuales dibujamos con diferentes colores para entenderlo y analizarlo de mejor manera la cual contiene 3 corrientes.
 
 ![](https://github.com/jlcastro5/Laboratorio2/blob/efb26b9cc102905a19ffd7a864b3d2213bacd2d3/MALLA2.PNG)

 Figura 3. Intepretacion de las corrientes en cada malla
 
 Entonces una vez encontrado y analizado cuantas corrientes estan en nuestro circuitos, dibujamos respectivamente las corrientes que pasa por cada resistencia para poder aplicar el analisis de mallas mediante la aplicacion de la ley de Kichhoff.
 
 ![](https://github.com/jlcastro5/Laboratorio2/blob/efb26b9cc102905a19ffd7a864b3d2213bacd2d3/CORRIENTES.PNG)
 
 Figura 4. Diagrama de las corrientes de cada resistencia
 
 Por lo tanto, realizamos un analisis en el protoboard para ver los valores de corriente que pasan por cada malla y respectivamente por cada resistencia tomando en cuanta, el proceso adecuado para encontrar y comprobar dichos datos.

 ![](https://github.com/jlcastro5/Laboratorio2/blob/7884183da6ba4f479e0bba6a4d47935ae1e0c207/SIMULADOR.PNG)
   
 Figura 5. Colocacion de multimetros para medir el amperaje
 
4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

 Realizamos el respectivo analisis mediante el proceso de analisis de malla en este el circuito con el que trabajos contiene 3 malas las cuales contendra tres   intensidades de corriente, las cuales son I1, I2, I3.

 ![](https://github.com/jlcastro5/Laboratorio2/blob/f56cd28a231cda38201686f2c593e00146c6dec4/TABLA2.1.PNG)
 
 Figura 6. Tabla de datos 

 Para el analisis de malla podemos darnos cuenta las corrientes respectivamente pasan por cada resistencia las cuales tomaremos los valores de sus voltajes para aplicar  las leyes de kichhoff, las cuales nos permitira obtener los valores de las intensidades de corriente como se muestra en la siguiente figura.

 ![](https://github.com/jlcastro5/Laboratorio2/blob/efb26b9cc102905a19ffd7a864b3d2213bacd2d3/CORRIENTES.PNG)

 Figura 7. Grafico de las corrientes en cada malla.

 En la malla 1, podemos tomar en cuenta que tenemos 3 elementos las cuales son la fuente de 18V,R1 y R2, aplicando leyes de kichhoff sumatoria de sus voltajes es igual a 0, por lo cual realizamos lo siguiente:

 18v-VR1-VR2 = 0 , Donde conocemos que V = I.R

 Tal que en la observacion en el VR2, los cuales pasan dos corrientes y se realiza el siguiente procedimiento de la figura 8.

 ![](https://github.com/jlcastro5/Laboratorio2/blob/a0ab0bacecc18d6e96d12259daf002af6379f359/MALLA.1.PNG)

 Figura 8. Analisis de la malla 1

 Para la malla 2, tenemos otra corriente diferente a la malla 1 la cual aplicando las leyes nos quedaria:

 -VR3-VR4-VR2=0 , Donde V = I.R

 En la figura 9. Realizamos el procedimiento adecuado para obtener la segunda ecuacion y con su respectivo analisis en las corrientes que pasan en VR2 Y VR4

 ![](https://github.com/jlcastro5/Laboratorio2/blob/a0ab0bacecc18d6e96d12259daf002af6379f359/MALLA.2.PNG)

 Figura 9. Analisis de la malla 2 

 Ahora analizaremos la ultima malla la cual contiene VR5, 5V, VR4 la cual nos quedaria de la siguiente manera:

 -VR5-5-VR4 = 0 , donde V = I.R

 Lo cual, analizaremos cada voltaje que contenga su respectiva corriente y realizar el siguiente procedimiento de la figura 10.

 ![](https://github.com/jlcastro5/Laboratorio2/blob/a0ab0bacecc18d6e96d12259daf002af6379f359/MALLA.3.PNG)

 Figura 10. Analisis de la malla 3

 Luego de haber obtenido de cada malla una ecuacion, podemos darnos cuenta que formamos un sistema de ecuaciones de 3 incognitas las cuales son I1,I2,I3 lo cual utiliaremos una calculadora online o un simulador matematico para resolver dichas ecuaciones.

 ![](https://github.com/jlcastro5/Laboratorio2/blob/a0ab0bacecc18d6e96d12259daf002af6379f359/SISTEMA.PNG)

 Figura 11. Sistema de ecuaciones

   Luego de haber realizado los procesos mediante matrices o soluciones de ecuacion obtenemos los valores de nuestras corrientes I1,I2,I3

 ![](https://github.com/jlcastro5/Laboratorio2/blob/f56cd28a231cda38201686f2c593e00146c6dec4/CORRIENTES1.2.PNG)

 Figura 11. Obtencion de las I1,I2,I3

   Luego, vamos al simulador de tinkercad lo cual armaremos nuestro protoboard con las resistencias correspondiente, y colocaremos nuestros multimetro para verificar y ver  los valores de las corrientes en cada malla, lo cual podemos observar que los valores calculador tiene una similitud ya que varia por decimales, y verificamos que dichos valores si corresponde al circuito medidos en el simulador.

 ![](https://github.com/jlcastro5/Laboratorio2/blob/7884183da6ba4f479e0bba6a4d47935ae1e0c207/SIMULADOR.PNG)

 Figura 12. Medicion del amperaje en nuestro circuito.
     


5. VIDEO

   

6. CONCLUSIONES

     * Las leyes de Kirchhoff han permitido obtener resultados muy similares entre los datos obtenidos mediante la experimentación y la simulación, los cuales no se alejan relativamente nada de los datos teóricos.
     * Para asegurar su efectividad se empleó el laboratorio virtual tinkercad, mismo que nos ha permitido identificar los valores de las resistencias, el voltaje de la fuente y los valores que ha tenido la corriente en sus respectivas mallas dentro de los circuitos eléctricos.


7. BIBLIOGRAFÍA 

   Latam, M. (2020, 6 julio). Leyes de Kirchhoff. Mecatrónica LATAM. https://www.mecatronicalatam.com/es/tutoriales/teoria/leyes-de-kirchhoff/
 
   Floyd,T. L. (2007). Principios de circuitos electricos. Mexico: Octava Edicion.
