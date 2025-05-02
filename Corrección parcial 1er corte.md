# PARES
## PUNTO 1
Ecuacion 
                      $$x"+4x=5$$ 

Tenemos las siguentes condiciones iniciales 
             $$x(0)=5$$    ;   $$x´(0)=0$$

$$s^{2}X(s)-sX(0)-X´(0)+4X(s)=\frac{5}{s}$$

$$s^{2}X(s)-5s+4X(s)=\frac{5}{s}$$

$$X(s)(s^{2}+4)=\frac{5}{s}+5s$$

$$X(s)=\frac{5s^{2}+2}{s(s^{2}+4)}$$

$$\frac{5s^{2}+2}{s(s^{2}+4)}=\frac{A}{s}+\frac{Bs+C}{s^{2}+4}$$

$$5s^{2}+2=A(s^{2}+2)+(Bs+C)(s)$$

$$5s^{2}+2=As^{2}+4A+Bs^{2}+Cs$$

$$(A+B=5)$$
$$(C=0)$$
$$(4A=2\Rightarrow A=\frac{1}{2})$$
$$S=\frac{1}{2}+B$$
$$\frac{10}{2}-\frac{1}{2}=B$$
$$B=\frac{9}{2}$$
$$X(s)=\frac{\frac{1}{2}}{s}+\frac{\frac{9}{2}s}{s^{2}+4}$$
$$x(s)=\frac{1}{2}+\frac{9}{2}cos(2t)$$

# PUNTO 2
$$F(s)=\frac{5(s+2)}{s^{2}-4s+8}$$
$$\frac{-b\frac{+}{-}\sqrt{b^{2}-4ac}}{2a}$$
$$\frac{4\frac{+}{-}\sqrt{16-4(1)(8)}}{2}$$
$$\frac{4\frac{+}{-}\sqrt{16-32}}{2}$$
$$\frac{4\frac{+}{-}\sqrt{16}}{2}$$
$$\frac{4\frac{+}{-}\sqrt{16i}}{2}$$
$$\frac{2\frac{+}{-}\sqrt{4i}}{2}$$
$$F(s)=\frac{5(s+2)}{s^{2}(s^{2}+4s+8)}$$
$$5(s+2)=\frac{A}{s^{2}}+\frac{B}{s}+\frac{Cs+D}{s^{2}-4s+8}$$
$$5(s+2)=A(s^{2}-4s+8)+B{s}(s^{2}-4s+8)+cs+d(s^{2})$$
$$\frac{5(s+2)}{s^{2}(s^{2}-4s+8)}$$
$$\frac{5(s+2)}{s^{2}(s^{2}-4s+8)}=\frac{A}{s}+\frac{B}{s^{2}}+\frac{Cs+D}{s^{2}-4s+8}$$
$$(s^{2}({s^{2}-4s+8}))$$
$$5(s+2)=As(s^{2}-4s+8)+B(s^{2}-4s+8)+(Cs+D)s^{2}$$
$$1.(As(s^{2}-4s+8)=A(s^{3}-4s^{2}+8s))$$
$$2.(B(s^{2}-4s+8)=Bs^{2}-4Bs+8B)$$
$$3.((Cs+D)s^{2}=Cs^{3}+D)$$
$$(A+C)s^{3}+(-4A+B+D)s^{2}+(8A-4B)s+8B$$
$$5s+10$$
$$s^{3}: A+C=0$$
$$s^{2}: -4A+B+D=0$$
$$s^{1}: 8A-4B=5$$
$$s^{0}: 8B=10$$
$$8B=10 \Rightarrow B=\frac{5}{4}$$
$$8A-4B=5 \Rightarrow 8A-4*\frac{5}{4}=5\Rightarrow 8A-5=5\Rightarrow A=\frac{10}{8}=\frac{5}{4}$$
$$A+C=0\Rightarrow C=-\frac{5}{4}$$
$$-4A+B+D=0\Rightarrow -4*\frac{5}{4}+\frac{5}{4}+D=0\Rightarrow -5+\frac{5}{4}+D=0$$
$$D=\frac{15}{4}$$
$$(A=\frac{5}{4})$$
$$(B=\frac{5}{4})$$
$$(C=-\frac{5}{4})$$
$$(D=\frac{15}{4})$$
$$\frac{5(s+2)}{s^{2}(s^{2}-4s+8)}=\frac{5}{4s}+\frac{5}{4s^{2}}+\frac{-\frac{5}{4}+\frac{15}{4}}{s^{2}-4s+8}$$
$$\frac{5}{4s}+\frac{5}{4s^{2}}+\frac{-\frac{5}{4}s+\frac{15}{4}}{s^{2}-4s+8}$$
$$L^{-1}(\frac{5}{4s})=\frac{5}{4}$$
$$L^{-1}(\frac{5}{4s})=\frac{5}{4}t$$
$$s^{2}-4s+8=(s-2)^{2}+4$$
$$\frac{-\frac{5}{4}s+\frac{15}{4}}{(s-2)^{2}+4}=\frac{-\frac{5}{4}(s-2)+\frac{5}{4}}{(s-2)^{2}+4}$$
$$\frac{-\frac{5}{4}(s-2)}{(s-2)^{2}+4}+\frac{\frac{5}{4}}{(s-2)^{2}+4}$$
$$L^{-1}\left ( \frac{-\frac{5}{4}(s-2)}{(s-2)^{2}+4} \right )= -\frac{5}{4}e^{2t}cos(2t)$$
L^$${-1}\left ( \frac{-\frac{5}{4}}{(s-2)^{2}+4} \right )= -\frac{5}{8}e^{2t}sin(2t)$$
$$L^{-1}\left ( \frac{5}{4s}+\frac{5}{4s^{2}}+\frac{-\frac{5}{4}s+\frac{15}{4}}{s^{2}-4s+8} \right ) =\frac{5}{4}+\frac{5}{4}t-\frac{5}{4}e^{2t}cos(2t)+\frac{5}{8}e^{2t}sin(2t)$$

## impar
# PUNTO 1
$$2\ddot{x}+2\dot{x}+x=1$$
$$x(0)=0$$
$$\dot{x}(0)=2$$
$$2(s^{2}X(s)-sX(0)-\dot{x}(0))+2(sX(s)-X(0))+X(s)=\frac{1}{s}$$
$$2(s^{2}X(s)-2)+2sX(s)+X(s)=\frac{1}{s}$$
$$2s^{2}X(s)-4+2sX(s)+X(s)=\frac{1}{s}$$
$$(2s^{2}+2s+1)X(s)=\frac{1}{s}+4$$
$$(2s^{2}+2s+1)X(s)=\frac{1+4s}{s}$$
$$X(s)=\frac{1+4s}{s(2s^{2}+2s+1)}$$
$$\frac{1+4s}{s(2s^{2}+2s+1)}=\frac{A}{s}+\frac{Bs+C}{2s^{2}+2s+1}$$
$$1+4s=A(2s^{2}+2s+1)+(Bs+C)s$$
$$1=A(1)\Rightarrow A=1$$
$$1+4s=A(2s^{2}+2s+1)+Bs^{2}+C$$
$$1+4s=(2A+B)s^{2}+(2A+C)s+A$$
$$(A=1)$$
$$(2A+B=0\Rightarrow B=-2)$$
$$(2A+C=4\Rightarrow C=2)$$
$$\frac{1+4s}{s(2s^{2}+2s+1)}=\frac{1}{s}+\frac{-2s+2}{2s^{2}+2s+1}$$
$$X(s)=\frac{1}{s}+\frac{s}{s^{2}+s+\frac{1}{2}}+\frac{1}{2s^{2}+s+\frac{1}{2}}$$
$$s^{2}+s+\frac{1}{2}=\left ( s+\frac{1}{2} \right )^{2}+\frac{1}{4}$$
$$X(s)=\frac{1}{s}-\frac{s}{\left ( s+\frac{1}{2} \right )^{2}+\left ( \frac{1}{2} \right )^{2}}+\frac{3}{\left (s+\frac{1}{2}  \right )^{2}+\left ( \frac{1}{2} \right )^{2}}$$
$$(L^{-1}\left ( \frac{1}{2} \right )=1)$$
$$(L^{-1}\left ( \frac{s+a}{(s+a)^{2}+b^{2}} \right )=e^{-at}cos(bt))$$
$$(L^{-1}\left ( \frac{b}{(s+a)^{2}+b^{2}} \right )=e^{-at}sin(bt))$$
$$X(t)=1+e^{-\frac{t}{2}}\left ( -cos\left ( \frac{1}{2}t\right )+3sin\left ( \frac{1}{2}t \right ) \right )$$

# PUNTO 2

$$\frac{6s}{(s-\frac{5}{2})(s^{2}-4s+8)}$$
$$(s-\frac{s}{2})$$
$$(s^{2}-4$$
$$\frac{6s}{(s-\frac{5}{2})(s^{2}-4s+8)}=\frac{A}{s-\frac{5}{2}}+\frac{Bs+C}{s^{2}-4s+8}$$
$$((s-\frac{5}{2})(s^{2}-4s+8))$$

$$6s=A(s^{2}-4s+8)+(Bs+C)(s-\frac{5}{2})$$

$$A(s^{2}-4s+8)=As^{2}-4As+8A$$

$$(Bs+C)(s-\frac{5}{2})=Bs^{2}-\frac{5}{2}Bs+Cs-\frac{5}{2}C$$

$$6s=(A+B)s^{2}+\left ( (-4A+C-\frac{5}{2}B)s \right )+\left ( 8A-\frac{5}{2}C \right )$$
$$(6s)$$

$$(s^{2}):(A+B=0)$$

$$(s):\left ( -4A+C-\frac{5}{2}B=6  \right )$$

$$\left ( 8A-\frac{5}{2}C=0 \right )$$

$$A+B=0\Rightarrow B=-A$$
$$-4A+C-\frac{5}{2}(-A)=6$$
$$-4A+C+\frac{5}{2}A=6$$

$$(-4A+\frac{5}{2})A+C=6\Rightarrow -\frac{3}{2}A+C=6   (1)$$
$$8A-\frac{5}{2}C=0\Rightarrow \frac{5}{2}C=8A\Rightarrow C=\frac{16}{5}A           (2)$$
$$-\frac{3}{2}A+\frac{16}{5}A=6$$
$$\left ( -\frac{3}{2}+\frac{16}{5} \right )A=6$$
$$\frac{-15+32}{10}A=6\Rightarrow \frac{17}{10}A=6$$
$$A=\frac{60}{17}$$
$$B=-A=-\frac{60}{17}$$
$$C=\frac{16}{5}A=\frac{16}{5}*\frac{60}{17}=\frac{960}{85}=\frac{192}{17}$$

$$\frac{6s}{\left ( s-\frac{5}{2} \right )(s^{2}-4s+8)}=\frac{60}{17}*\frac{1}{s-\frac{5}{2}}-\frac{60s}{17(s^{2}-4s+8)}+\frac{192}{17(s^{2}-4s+8)}$$

$$\frac{60}{17}*\frac{1}{s-\frac{5}{2}}-\frac{60s}{17(s^{2}-4s+8)}+\frac{192}{17(s^{2}-4s+8)}$$


$$L^{-1}\left ( \frac{1}{s-a} \right )=e^{at}$$

$$L^{-1}\left ( \frac{60}{17}*\frac{1}{s-\frac{5}{2}} \right )=\frac{60}{17}e^{\frac{5}{2}t}$$

$$s^{2}-4s+8=(s-2)^{2}+4$$

$$\frac{60s}{17((s-2)^{2}+4)}=\frac{60}{17}*\frac{s}{(s-2)^{2}+4}$$

$$s=(s-2)+2$$

$$\frac{s}{(s-2)^{2}+4}=\frac{s-2}{(s-2)^{2}+4}+\frac{2}{(s-2)^{2}+4}$$

$$L^{-1}\left ( \frac{s-a}{(s-a)^{2}+b^{2}} \right )=e^{at}cos(bt)$$

$$L^{-1}\left ( \frac{b}{(s-a)^{2}+b^{2}} \right )=e^{at}sin(bt)$$

$$L^{-1}\left ( \frac{60s}{17((s-2)^{2}+4)} \right )= \frac{60}{17}(e^{2t}cos(2t)+e^{2t}sin(2t))$$

$$L^{-1}\left ( \frac{192}{17((s-2)^{2}+4)} \right )= \frac{192}{17}*\frac{1}{2}e^{2t}sin(2t)=\frac{96}{17}e^{2t}sin(2t)$$


$$L^{-1}\left ( \frac{60}{17}*\frac{1}{s-\frac{5}{2}}-\frac{60s}{17(s^{2}-4s+8)}+\frac{192}{17(s^{2}-4s+8)}\right )$$

$$=\frac{60}{17}e^{\frac{5}{2}t}-\frac{60s}{17}e^{2t}cos(2t)+\left ( -\frac{60}{17}+\frac{96}{17} \right )e^{2t}sin(2)$$

$$=\frac{60}{17}e^{\frac{5}{2}t}-\frac{60}{17}e^{2t}cos(2t)+\frac{36}{17}e^{2t}sin(2t)$$






















