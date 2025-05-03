# Sistemas Mecanicos
Se tratan de sistemas con un conjunto de elementos fisicos interconectados que al trabajar en conjunto logran realizar una accion especifica utilizando los principios de la mecanica.
## Resorte 
Se trata de un componente mecanico elastico diseñado para almacenar y liberar energia. Esto se genera cuando el resorte es oprimido por otro elemento externo, el resorte almacena energia comprimiendose para que despues libere la presion a la que es sometido devolviendo la energia a su origen.
los resortes se rigen por la siguiente formula al momento de ser modeladas:


$$F=kx=k(x_{1}-x_{2})$$

## Amortiguador
Es un dispositivo construido por un eje cromado y dos tubos de acero. Se trata de dispositivos hidraulicos el cual se encargara de amortiguar golpes o impactos por medio de la transformacion de energia, las piezas convierten la energia cinetica del impacto.
Al momento de realizar el modelamiento se utiliza la siguiente formula:


$$F=b\frac{\mathrm{d} x}{\mathrm{d} y}=b(\frac{\mathrm{d} x_{1}}{\mathrm{d} y_{1}}-\frac{\mathrm{d} x_{2}}{\mathrm{d} y_{2}})$$

# Friccion
Es un tipo de fuerza tangencial a la superficie que se opone a cualquier deslizamiento de un objeto a travez de una superficie
## Tipos de friccion
Friccion en seco: Esta friccion se produce cuando un cuerpo que no se encuentra lubricado se desliza por una superficie no lubricada.

Friccion estatica: Es la fuerza entre dos superficies que impide que alguna de estas se deslice o resbalen.

Friccion por deslizamiento: Se trata de la fuerza que se opone al movimiento de dos superficies que rozan entre si.

Friccion por rodamiento: Es la fuerza que se opone al movimiento de un solido que rueda sobre otro solido.

# Sistemas masa-Resorte-amortiguador
Se trata de sistemas que pueden almacenar energia potencial y cinetica, esto con el proposito de reducir las vibraciones y ruidos generados en la estructura a causa de algun impacto


Ley de Hooke        $$F_{R}=k_{2} * X$$  


Friccion viscosa    $$F_{F}=k_{1} * v_{m}$$ 


Leyes de Newton     $$F= m * a$$

# Ejemplo en clase 1


$$ u - F_{R}-F_{F} = m * a$$


$$ F_{R}= k_{2} * y(t)$$


$$ u(t) - k_{2} * y(t) - F_{F} = m * a$$


$$ F_{F} = k_{1} * \frac{dy(t)}{dt}$$


$$ u(t) - k_{2} * y(t) - k_{1} * \frac{dy(t)}{dt} = m * a$$


$$ a = \frac{d^{2}y(t)}{dt^{2}}$$


$$ u(t) - k_{2} * y(t) - k_{1} * \frac{dy(t)}{dt} = m * \frac{d^{2}y(t)}{dt^{2}}$$


# Ejemplo en clase 2


$$ \sum f = m * a$$


$$ u + F_{w} - F_{R} - F_{F} = m * a$$


$$ mg + u(t) - k_{2}y(t) - k_{1}dy(t) = mdy(t)$$


$$ u(t) + mg - k_{2}y(t) - k_{1}dy(t) = md^{2}y(t)$$


# Ejemplo en clase 3
Sistemas mecanicos mas complejos 


masa 1


$$ u - F_{R1} - F_{R2} - F_{F} = m_{1} * a_{m1}$$


$$ u(t) - k_{1} * x_{1}(t) - k_{2} * (x_{1}(t)-x_{2}(t)) - b *\frac{d(x_{1}(t)-x_{2}(t))} {dt} = m_{1} * \frac{d^{2}x_{1(t)}}{dt^{2}}$$


masa 2


$$ F_{R2} - F_{F} - F_{R3} = m_{2} * a_{m2}$$


$$ k_{2} * (x_{1}(t)-x_{2}(t)) + b *\frac{d(x_{1}(t)-x_{2}(t))}{dt} - k_{3} * x_{2}(t) = m_{2} * \frac{d^{2}x_{2(t)}}{dt^{2}}$$
