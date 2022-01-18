# InformeLaboratorio6
**1. TEMA:**

Teorema de la Máxima Transferencia de Potencia.

**2. OBJETIVO**

**2.1. Objetivo General**

Comprobar experimentalmente el Teorema de la Máxima Transferencia de Potencia.

**2.2. Objetivos Específicos**

- Definir el teorema de Thevenin.
- Entender sus pasos y la aplicación del Teorema de la Máxima Transferencia de Potencia.
- Realizar el circuito propuesto de manera correcta y funcional.
- Tomar las medidas de volatjes y corrientes en el circuito para comparar el teorema.
- Realizar el teorema de MTP manualmente y comparar con las medidas obtenidas en Tinkercad.
- Observar los resultados y concluir si el teorema es funcional. 

**3. MARCO TEÓRICO**

**3.1. Teorema de Thevenin**

El teorema de Thevenin establece que un circuito lineal de dos terminales puede sustituirse por un circuito equivalente formado por una fuente de tensión VTH en serie con una resistencia RTH

[![Teorema-de-Thevenin.png](https://i.postimg.cc/zB9YjLn8/Teorema-de-Thevenin.png)](https://postimg.cc/zbSQDGtc)

**3.2. Teorema de Transformación de Potencia Máxima**

El teorema de máxima transferencia de potencia establece que, dada una fuente, con una resistencia de fuente fijada de antemano, la resistencia de carga que maximiza la transferencia de potencia es aquella con un valor óhmico igual a la resistencia de fuente.

[![Teorema-de-Transferencia-de-Potencia-M-xima.png](https://i.postimg.cc/52MvrnxF/Teorema-de-Transferencia-de-Potencia-M-xima.png)](https://postimg.cc/zV0VbwHJ)

**4. EXPLICACIÓN DEL PROCEDIMIENTO**

**4.1.** Se realizará el siguiente circuito simple en Tinkercad. Se utilizarán las siguientes herramientas:

- Una Placa de pruebas pequeña.
- Una Resistencias.
- Un Suminitrador de Energía.
- Un multímetro.
- Un Potenciómetro.

[![1.png](https://i.postimg.cc/j2bJL4M7/1.png)](https://postimg.cc/8JZCYMQp)

**4.2.** Conectamos el suministrador de energía en la placa pequeña, de tal forma que el diseño del circuito dado en el informe sea similar al realizado.

[![2.png](https://i.postimg.cc/2j710vH0/2.png)](https://postimg.cc/DmmfZW3G)

**4.3.** Ahora posicionamos el resistor y lo conectaremos con un cable verde, siguiendo el modelo. De igual manera conectaremos el potenciómetro para poder obtener la resistencia requerida. Al final conectaremos el circuito hasta tierra para poder cerrarlo por completo.

[![4.png](https://i.postimg.cc/P5Qhjzw7/4.png)](https://postimg.cc/0zjhGSZG)

[![3.png](https://i.postimg.cc/CMRFqq3Z/3.png)](https://postimg.cc/9zj53rFV)

**5. RESULTADOS OBTENIDOS**

**5.1**. Primero mediremos el voltaje que pasa por la resistencia Rl, en cada caso. Lo haremos a través de Tinkercad.

[![5.png](https://i.postimg.cc/HLWJDLVQ/5.png)](https://postimg.cc/yD560shd)

Con resistencia de 220 ohms.

[![6.png](https://i.postimg.cc/rmBFmyFZ/6.png)](https://postimg.cc/mzSGps97)

Con resistencia de 470 ohms.

[![7.png](https://i.postimg.cc/137SXRv0/7.png)](https://postimg.cc/87v9nGQs)

Con resistencia de 680 ohms.

[![8.png](https://i.postimg.cc/bwsM6xRb/8.png)](https://postimg.cc/JsCP0Bv4)

Con resistencia de 820 ohms.

De igual manera continuo analizando los voltajes con las resistencias sobrantes.

**5.2**. Ahora mediremos la corriente que pasa por la resistencia Rl, en cada caso. Lo haremos a través de Tinkercad.

[![9.png](https://i.postimg.cc/FRD8WDwy/9.png)](https://postimg.cc/WFq5t6Nz)

Con resistencia de 220 ohms.

[![10.png](https://i.postimg.cc/hG33Vfms/10.png)](https://postimg.cc/xkMR2jtN)

Con resistencia de 470 ohms.

[![11.png](https://i.postimg.cc/8cdHX57q/11.png)](https://postimg.cc/7J60fqMV)

Con resistencia de 680 ohms.

[![12.png](https://i.postimg.cc/jSnWR1Xj/12.png)](https://postimg.cc/4YZ45BjC)

Con resistencia de 820 ohms.

De igual manera continuo analizando las corrientes con las resistencias sobrantes.

**5.3**. Ahora mediremos la potencia experimental conseguida en cada uno de las Rl con los datos dados por Tinkercad.

[![Whats-App-Image-2022-01-17-at-11-41-07-PM.jpg](https://i.postimg.cc/5tBw8m0b/Whats-App-Image-2022-01-17-at-11-41-07-PM.jpg)](https://postimg.cc/WD4FvggH)

**5.4**. Ahora mediremos la potencia con el teorema de máxima potencia transferida conseguida en cada uno de las Rl con los datos dados por Tinkercad.

[![Whats-App-Image-2022-01-17-at-11-42-25-PM.jpg](https://i.postimg.cc/jSVwvJB5/Whats-App-Image-2022-01-17-at-11-42-25-PM.jpg)](https://postimg.cc/xcR11qfD)

**5.5.** Cómo ya poseemos todos los datos necesarios; rellenamos la tabla de potencias, voltajes y corrientes.

| RL(Ω)  | Corriente Medida (mA)  | Voltaje Medido (V)   |Potencia Calculada Experimentalmente (W)  |Potencia Calculada Teóricamente (W) |
| ------------ | ------------ | ------------ | ------------ | ------------ | 
| 220 | 10.6 mA  | 2.33 V  | 24.70 W  | 24.55 W  | 
| 470 | 8.98 mA | 4.22 V  | 37.89 W |37.92 W  |
| 680 |7.98 mA  |5.43 V  |43.33 W |43.28 W  |
| 820 |7.42 mA  |6.09 V |45.19 W  |45.22 W |
| 1000 |6.82 mA |6.82 V  |46.51 W |46.49 W  |
| 1500 |5.55 mA |8.33 V  |46.23 W |46.29 W  |
| 1800 |5 mA  |9 V  |45 W  |45 W |
| 2200 |4.41 mA |9.71 V  |42.82 W |42.82 W  |
| 3900 |2.94 mA  |11.5 V  |33.81 W  |33.74 W |
| 4700 |2.54 mA  |11.9 V  |30.23 W  |30.38 W |

**5.6.** Luego de haber obtenido los datos necesarios, podemos responder a las preguntas que el informe me presenta.

**5.6.1.** ¿Se cumple el teorema de la máxima transferencia de potencia? 

Sí, se cumple el teorema de la máxima transferencia de potencia debido a que los resultados son los mismo al usar la ecuación de Potencia normal. 

**5.6.2.** ¿Cuál fue la potencia máxima en RL? 

Es de 46.49 W

**5.6.3.** ¿Para qué valor de RL se obtiene MTP? 

Para 1000 Ω

**6. VÍDEO**

https://www.youtube.com/watch?v=4mpXsCcd-NE

**7. CONCLUSIONES**

Con el siguiente informe de laboratorio pudimos observar y aplicar el concepto de MTP el cuál nos habla sobre la transferencia de máxima potencia en un circuito, especialemente cuando se trata de uno de Thevenin. Se aplicó sus características y se vio los pasos necesarios para lograr conseguir esta potencia requerida. De igual forma observamos y comparamos la ecuación de MTP con la ecuación normal de potencia, la cual también fue usada para describir las potencias de cada RL.

Luego realizamos el circuito requerido en Tinkercad y tomamos las medidas requeridas para completar el cuadro de datos. Gracias a esto es que pudimos darnos cuenta de la semenaja que se hay al usar el teorema de MTP y las ecuaciones normales de potencia. Logrando así encontrar la potenica máxima del circuito. 

De igual forma, respondidmos a las preguntas planteadas por este informe y argumentamos cada una de ellas con su respectivo resultado y el porque de este.

**8. BIBLIOGRAFÍA**

- Circuit. (2010). Multisim. Obtenido de https://www.multisim.com/create/
- Ministerio de Educaión . (2011). inet. Obtenido de http://www.inet.edu.ar/wp-content/uploads/2020/07/ELECTRONICA_Gu--a07-Mallas-y-Nodos.pdf
- Eris, N. (20 de Noviembre de 2017). Sesoricx. Obtenido de https://sensoricx.com/circuitos-electricos-dc/analisis-de-circuitos-empleando-nodos/
- Hain, J. (14 de Septiembre de 2019). Khan Academy. Obtenido de https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-node-voltage-method

