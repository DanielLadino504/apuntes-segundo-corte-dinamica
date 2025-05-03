# Sistemas Electricos
Al estudiar dinámica de sistemas, nos encontramos con los sistemas eléctricos normalmente definidos como el conjunto de elementos conectados entre sí con la finalidad de generar, transmitir, distribuir y utilizar la energía eléctrica de manera eficiente y segura.
## Circuito RLC
El modelamiento de sistemas eléctricos RLC (Resistor, Inductor, Capacitor) se realiza con ecuaciones diferenciales. Estas ecuaciones diferenciales normalmente son de primer y segundo orden, se reconocen a simple vista gracias a los elementos acumuladores de energía, debido a la presencia de inductancia y capacitancia. Estas ecuaciones describen el comportamiento dinámico de la corriente y el voltaje en el circuito en función del tiempo.

En los circuitos RLC, las leyes que los rigen son   la ley de Ohm y las leyes de Kirchhoff y los elementos a estudiar se pueden dividir en 3 tipos, en elementos resistivos, inductivos y capacitivos por esto al momento de modelar un sistema eléctrico RLC tenemos que tener encuentra las siguientes fórmulas: 

# Ejemplo de un sistema electrónico RLC

## Análisis del Circuito Eléctrico

Este documento presenta un ejemplo de análisis de un circuito eléctrico utilizando la ley de Kirchhoff de voltajes.

## Elementos del Circuito
- $$\( R \)$$: Resistencia  
- $$\( L \)$$: Inductancia  
- $$\( \frac{1}{1000} \)$$: Posiblemente el valor de la capacitancia $$(\ C = \frac{1}{1000} \text{ F} \)$$  
- $$\( u \)$$: Fuente de voltaje de entrada  
- $$\( v \)$$: Voltajes en componentes (subíndices indican el componente)  
- $$\( c \)$$: Posible error tipográfico (debería ser \( C \) para capacitancia)  
- $$\( y \)$$: Variable de salida (voltaje en el capacitor)  
 

## Aplicación de la Ley de Kirchhoff

La ecuación fundamental obtenida es:  
$$-u + v_R + v_L + v_C = 0$$  

Que se desarrolla como:  
$$-u(t) + i(t) \cdot R + L \frac{di(t)}{dt} + y(t) = 0$$  

## Transformación a términos de \( y(t) \)

Como \( y(t) \) es el voltaje en el capacitor (\( v_C \)), se usa la relación:  
$$i(t) = C \frac{dy(t)}{dt}$$  

Sustituyendo se obtiene la ecuación diferencial final:  
$$-u(t) + RC \frac{dy(t)}{dt} + LC \frac{d^2 y(t)}{dt^2} + y(t) = 0$$  

Esta es una ecuación diferencial de segundo orden que describe la dinámica del circuito RLC en serie, donde:  
- $$\( u(t) \)$$: Entrada (fuente de voltaje)  
- $$\( y(t) \)$$: Salida (voltaje en el capacitor)  
- **Términos**:  
  - $$\( RC \frac{dy(t)}{dt} \)$$: Componente resistivo  
  - $$\( LC \frac{d^2 y(t)}{dt^2} \)$$: Componente inductivo  
  - $$\( y(t) \)$$: Componente capacitivo  
