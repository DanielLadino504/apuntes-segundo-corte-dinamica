# Sistemas Rotacionales
Conocidos como sistemas que generan movimiento rotativo, los cuerpos que forman el sistema realizan rotaciones en el mismo plano.
estos sistemas estan compuestos por tres componetes fisicos basicos como: elemento de inercia, resortes y elementos de friccion.
Al momento de realizar un modelamiento de este tipo de sistemas se debe tener en cuenta las siguientes leyes:


$$F_{R}=K\cdot \varphi$$


con \varphi siendo el angulo de torsion


$$F_{F}=b\frac{\mathrm{d} \varphi }{\mathrm{d} t}$$


Donde $\frac{\mathrm{d} \varphi }{\mathrm{d} t}$ es la velocidad angular


$$T=J\cdot \frac{\mathrm{d^{2}} \varphi }{\mathrm{d} t^{2}}$$

Donde $\frac{\mathrm{d^{2}} \varphi }{\mathrm{d} t^{2}}$ es el momento de inersia

# Ejemplo
Formula general


$$T-F_{R}-F_{F}=J*\alpha$$

Donde $\alpha$ es la aceleracion angular


Formula particular

$$T(t)-F_{F}=J*\alpha$$

Donde $\alpha$ es la aceleracion angular


$$T(t)* k*\theta (t)-b*\frac{d\theta (t)}{dt}=J*\frac{d^{2}\theta (t)}{dt^{2}}$$
