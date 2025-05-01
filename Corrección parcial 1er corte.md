## pares
# PUNTO 1


$$x"+4x=5$$ 

$$x(0)=5$$           

$$x´(0)=0$$

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
\frac{-b\frac{+}{-}\sqrt{b^{2}-4ac}}{2a}
\frac{4\frac{+}{-}\sqrt{16-4(1)(8)}}{2}
\frac{4\frac{+}{-}\sqrt{16-32}}{2}
\frac{4\frac{+}{-}\sqrt{16}}{2}
\frac{4\frac{+}{-}\sqrt{16i}}{2}
\frac{2\frac{+}{-}\sqrt{4i}}{2}
F(s)=\frac{5(s+2)}{s^{2}(s^{2}+4s+8)}
5(s+2)=\frac{A}{s^{2}}+\frac{B}{s}+\frac{Cs+D}{s^{2}-4s+8}
5(s+2)=A(s^{2}-4s+8)+B{s}(s^{2}-4s+8)+cs+d(s^{2})
\frac{5(s+2)}{s^{2}(s^{2}-4s+8)}
\frac{5(s+2)}{s^{2}(s^{2}-4s+8)}=\frac{A}{s}+\frac{B}{s^{2}}+\frac{Cs+D}{s^{2}-4s+8}
(s^{2}({s^{2}-4s+8}))
5(s+2)=As(s^{2}-4s+8)+B(s^{2}-4s+8)+(Cs+D)s^{2}
1.(As(s^{2}-4s+8)=A(s^{3}-4s^{2}+8s))
2.(B(s^{2}-4s+8)=Bs^{2}-4Bs+8B)
3.((Cs+D)s^{2}=Cs^{3}+D)
(A+C)s^{3}+(-4A+B+D)s^{2}+(8A-4B)s+8B
5s+10
s^{3}: A+C=0
s^{2}: -4A+B+D=0
s^{1}: 8A-4B=5
s^{0}: 8B=10
8B=10 \Rightarrow B=\frac{5}{4}
8A-4B=5 \Rightarrow 8A-4*\frac{5}{4}=5\Rightarrow 8A-5=5\Rightarrow A=\frac{10}{8}=\frac{5}{4}
A+C=0\Rightarrow C=-\frac{5}{4}
-4A+B+D=0\Rightarrow -4*\frac{5}{4}+\frac{5}{4}+D=0\Rightarrow -5+\frac{5}{4}+D=0
D=\frac{15}{4}
(A=\frac{5}{4})
(B=\frac{5}{4})
(C=-\frac{5}{4})
(D=\frac{15}{4})
\frac{5(s+2)}{s^{2}(s^{2}-4s+8)}=\frac{5}{4s}+\frac{5}{4s^{2}}+\frac{-\frac{5}{4}+\frac{15}{4}}{s^{2}-4s+8}
\frac{5}{4s}+\frac{5}{4s^{2}}+\frac{-\frac{5}{4}s+\frac{15}{4}}{s^{2}-4s+8}
L^{-1}(\frac{5}{4s})=\frac{5}{4}
L^{-1}(\frac{5}{4s})=\frac{5}{4}t
s^{2}-4s+8=(s-2)^{2}+4
\frac{-\frac{5}{4}s+\frac{15}{4}}{(s-2)^{2}+4}=\frac{-\frac{5}{4}(s-2)+\frac{5}{4}}{(s-2)^{2}+4}
\frac{-\frac{5}{4}(s-2)}{(s-2)^{2}+4}+\frac{\frac{5}{4}}{(s-2)^{2}+4}
L^{-1}\left ( \frac{-\frac{5}{4}(s-2)}{(s-2)^{2}+4} \right )= -\frac{5}{4}e^{2t}cos(2t)
L^{-1}\left ( \frac{-\frac{5}{4}}{(s-2)^{2}+4} \right )= -\frac{5}{8}e^{2t}sin(2t)
L^{-1}\left ( \frac{5}{4s}+\frac{5}{4s^{2}}+\frac{-\frac{5}{4}s+\frac{15}{4}}{s^{2}-4s+8} \right ) =\frac{5}{4}+\frac{5}{4}t-\frac{5}{4}e^{2t}cos(2t)+\frac{5}{8}e^{2t}sin(2t)

## impar
2\ddot{x}+2\dot{x}+x=1  






