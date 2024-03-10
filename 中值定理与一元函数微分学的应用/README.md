# 中值定理

## 罗尔定理 Rolle

$$
f(x)\in C[a,b]\\
f(x)在(a,b)可导\\
f(a)=f(b)
$$

$$
\exists \xi \in(a,b),使f'(\xi)=0
$$

<img src="C:\Users\ASUS\Desktop\Math\1.png" style="zoom:50%;" />
$$
f(x)\in C[a,b]\Rightarrow m,M
$$

1. m=M
   $$
   f(x)\equiv C_0,则\forall \xi \in (a,b),有f'(\xi)=0
   $$

2. m<M
   $$
   \because f(a)=f(b)\therefore m,M至少一个在(a,b)内取到\\
   设\exists\xi\in(a,b),使f(\xi)=M\Rightarrow\xi为极大值\Rightarrow f'(\xi)=0或不存在\\
   \because f(x)可导 \therefore f'(\xi)=0
   $$

$$
f(0)=1,f(1)=2,f(2)=-1\\
h(x)=f(x)-1\\
h(0)=0,h(1)=1,h(2)=-2\\
\exists c\in (1,2),h(c)=h(0)=0\\
\exists \xi\in (0,c)\subset(0,2),h'(\xi)=0=f'(\xi)
$$

$$
f(0)+2f(1)=2f(2)+f(3)\\
m\leqslant \frac{f(0)+2f(1)}{3}=\frac{2f(2)+f(3)}{3}\leqslant M\\
\exists\xi_1\in(0,1),\xi_2\in(2,3),使f(\xi_1)=\frac{f(0)+2f(1)}{3}=f(\xi_2)=\frac{2f(2)+f(3)}{3}\\
\exists\xi\in(\xi_1,\xi_2)\subset(0,3),使f'(\xi)=0
$$

$$
f(x)在[0,1]上二阶可导\\
连接端点A(0,f(0)),B(1,f(1))的线段交曲线y=f(x)于点C(c,f(c))(0<c<1)\\
\exists \xi_1\in(0,c),\xi_2\in(c,1),使f'(\xi_1)=\frac{f(c)-c(0)}{c-0}=f'(\xi_2)=\frac{f(1)-c(c)}{1-c}\\
\exists\xi\in(\xi_1,\xi_2)\subset(0,1),使f''(\xi)=0
$$

$$
f'(\xi)=-f(\xi)\cot\xi\\
f(x)\cos x+f'(\xi)\sin x=(f(x)\sin x)'
$$

$$
f'(\xi)+2f(\xi)g'(\xi)=0\\
(f(x)e^{2g(x)})'=f'(x)e^{2g(x)}+e^{2g(x)}2g'(x)f(x)=e^{2g(x)}(f'(x)+2g'(x)f(x))
$$

$$
f'(\xi)+2\xi f(\xi)=0\\
(f(x)e^{x^2})'=f'(x)e^{x^2}+e^{x^2}2xf(x)=e^{x^2}(f'(x)+2xf(x))
$$

$$
\frac{f(a)-f(\xi)}{g(\xi)-g(b)}=\frac{f'(\xi)}{g'(\xi)}\\
F'(x)=f'(\xi)[g(\xi)-g(b)]-g'(\xi)[f(a)-f(\xi)]=[f'(\xi)g(\xi)+g'(\xi)f(\xi)]-[g(b)f'(\xi)+f(a)g'(\xi)]\\
F(x)=f(x)g(x)-[f(x)g(b)+f(a)g(x)]
F(a)=F(b)=-f(a)g(b)\\
\exists \xi\in (a,b),使F'(\xi)=0
$$

$$
f(a)+f(b)<f(a+b)\\
f(a)-f(0)=f'(\xi_1)a\\
f(a+b)-f(b)=f'(\xi_2)a\\
f'(\xi_1)a<f'(\xi_2)a\\
f(a)+f(b)<f(a+b)
$$

$$
|f(0)|+|f(2)|\leqslant 2M\\
\exists c\in(0,2),f(c)=0\\
f(c)-f(0)=f'(\xi_1)c\\
f(2)-f(c)=f'(\xi_2)(2-c)\\
|f(0)|=|f'(\xi_1)c|\leqslant cM\\
|f(2)|=|f'(\xi_2)(2-c)|\leqslant (2-c)M\\
|f(0)|+|f(2)|\leqslant 2M
$$

$$
|f'(a)|+|f'(b)|\leqslant M(b-a)\\
\exists c\in(a,b),使f'(c)=0\\
f'(c)-f'(a)=f''(\xi_1)(c-a)\\
f'(b)-f'(c)=f''(\xi_2)(b-c)\\
|f'(a)|=|f''(\xi_1)(c-a)|\leqslant M|c-a|\\
|f'(b)|=|f''(\xi_2)(b-c)|\leqslant M|b-c|\\
|f'(a)|+|f'(b)|\leqslant M[|c-a|+|b-c|]\leqslant M|b-a|
$$

## 拉格朗日中值定理 Lagrange

$$
f(x)\in C[a,b]\\
f(x)在(a,b)可导
$$

$$
\exists \xi \in(a,b),使f'(\xi)=\frac{f(b)-f(a)}{b-a}
$$

<img src="C:\Users\ASUS\Desktop\Math\2.png" style="zoom:50%;" />
$$
L:y=f(x)\\
L_{AB}:y-f(a)=\frac{f(b)-f(a)}{b-a}(x-a)\\
即L_{AB}:y=f(a)+\frac{f(b)-f(a)}{b-a}(x-a)\\
令\psi(x)=L-L_{AB}=f(x)-f(a)-\frac{f(b)-f(a)}{b-a}(x-a)\\
\psi\in C[a,b],在(a,b)内可导\\
又\psi(a)=\psi(b)=0,\therefore\exists\xi\in(a,b),使\psi'(\xi)=0\\
而\psi'(x)=f'(x)-\frac{f(b)-f(a)}{b-a}\\
\therefore f'(\xi)=\frac{f(b)-f(a)}{b-a}
$$

$$
\exists \xi(0,\frac{1}{2}),\eta(\frac{1}{2},1)\\
f'(\xi)=\frac{f(\frac{1}{2})-f(0)}{\frac{1}{2}-0}=2[f(\frac{1}{2})-f(0)]\\
f'(\eta)=\frac{f(1)-f(\frac{1}{2})}{1-\frac{1}{2}}=2[f(1)-f(\frac{1}{2})]\\
f'(\xi)+f'(\eta)=2[f(1)-f(0)]=0
$$

## 柯西中值定理 Cauchy

$$
f(x),g(x)\in C[a,b]\\
f(x),g(x)在(a,b)可导\\
g'(x)\neq 0\ (a<x<b)
$$

$$
\exists \xi \in(a,b),使\frac{f(b)-f(a)}{g(b)-g(a)}=\frac{f'(\xi)}{g'(\xi)}
$$

$$
\psi(x)=L-L_{AB}=f(x)-f(a)-\frac{f(b)-f(a)}{b-a}(x-a)\\
令\psi(x)=f(x)-f(a)-\frac{f(b)-f(a)}{g(b)-g(a)}[g(x)-g(a)]\\
\psi\in C[a,b],(a,b)内可导\\
\psi(a)=\psi(b)=0\\
\exists\xi\in(a,b),使\psi'(\xi)=0\\
而\psi'(x)=f'(x)-\frac{f(b)-f(a)}{g(b)-g(a)}g'(x)\\
\therefore f'(\xi)=\frac{f(b)-f(a)}{g(b)-g(a)}g'(x)\\
\because g'(\xi)\neq0,\therefore \frac{f(b)-f(a)}{g(b)-g(a)}=\frac{f'(\xi)}{g'(\xi)}
$$

$$
f(b)-f(a)=(1+\xi)f'(\xi)\ln \frac{1+b}{1+a}\\
\frac{f(b)-f(a)}{\ln{(1+b)}-\ln{(1+a)}}=\frac{f'(\xi)}{\frac{1}{1+\xi}}\\
g(x)=\ln{(1+x)}\\
\frac{f(b)-f(a)}{g(b)-g(a)}=\frac{f'(\xi)}{g'(\xi)}
$$

$$
ae^b-be^a=(a-b)(1-\xi)e^{\xi}\\
\frac{e^b-e^a}{\frac{1}{b}-\frac{1}{a}}=\frac{e^\xi}{\frac{1}{1-\xi}}\\
f(x)=e^x,g(x)=lnx\\
\frac{f(b)-f(a)}{g(b)-g(a)}=\frac{f'(\xi)}{g'(\xi)}
$$

$$
f(2)=\xi f'(\xi)-f(\xi)\\
F(x)=\frac{f(x)}{x},G(x)=-\frac{1}{x}\\
\frac{F(2)-F(1)}{G(2)-G(1)}=\frac{F'(\xi)}{G'(\xi)}\\
\frac{\frac{f(2)}{2}}{-\frac{1}{2}-(-1)}=\frac{\frac{\xi f'(\xi)-f(\xi)}{\xi^2}}{\frac{1}{\xi^2}}
$$

$$
4f(2)=\xi^2f(\xi)+\xi^3\\
F(x)=xf(x),G(x)=-\frac{1}{x}\\
\frac{F(2)-F(1)}{G(2)-G(1)}=\frac{F'(\xi)}{G'(\xi)}
$$

$$
f'(\xi)=\frac{a+b}{2\eta}f'(\eta)\\
F(x)=x^2,F'(x)=2x\\
\frac{f(b)-f(a)}{F(b)-F(a)}=\frac{f'(\eta)}{F'(\eta)}\\
\frac{f(b)-f(a)}{b-a}=\frac{a+b}{2\eta}f'(\eta)\\
f'(\xi)=\frac{a+b}{2\eta}f'(\eta)
$$

$$
\frac{f'(\zeta)}{f'(\xi)}=\frac{\xi}{\eta}\\
F(x)=\ln x,F'(x)=\frac{1}{x}\\
\frac{f(2)-f(1)}{F(2)-F(1)}=\frac{f'(\xi)}{F'(\xi)}\Rightarrow \frac{f(2)-f(1)}{\ln 2- \ln 1}=\frac{f'(\xi)}{\frac{1}{\xi}}=\xi f'(\xi)\\
\ln 2-\ln 1=\frac{1}{\eta}*(2-1)=\frac{1}{\eta}\\
f(2)-f(1)=\frac{\xi}{\eta}f'(\xi)\\
f(2)-f(1)=f'(\zeta)(2-1)=f'(\zeta)\\
\frac{f'(\zeta)}{f'(\xi)}=\frac{\xi}{\eta}
$$

## 泰勒中值定理 Taylor

$$
f(x)在x=x_0领域内n+1阶可导\\
f(x)=P_n(x)+R_n(x)\\
P_n(x)=f(x_0)+f'(x_0)(x-x_0)+\frac{f''(x_0)}{2!}(x-x_0)^2+...+\frac{f^{(n)}(x_0)}{n!}(x-x_0)^n\\
R_n(x)=\begin{cases}
\frac{f^{(n+1)}(\xi)}{(n+1)!}(x-x_0)^{n+1} & \xi介于x_0与x之间& 拉格朗日型\\
o((x-x_0)^n)&皮亚诺型
\end{cases}
$$

$$
x_0=0\\
f(x)=f(0)+f'(0)x+\frac{f''(0)}{2!}x^2+...+\frac{f^{(n)}(0)}{n!}x^n+R_n(x)\\
R_n(x)=\begin{cases}
\frac{f^{(n+1)}(\xi)}{(n+1)!}x^{n+1} & \xi介于0与x之间\\
o(x^n)
\end{cases}
$$

$$
\lim_{x\rightarrow0}\frac{\sqrt{1+x}+\sqrt{1-x}-2}{x^2}\\
f(x)=f(0)+f'(0)x+\frac{f''(0)}{2!}x^2\\
a(x)=\sqrt{1+x}\\
a'(x)=\frac{1}{2}(1+x)^{-\frac{1}{2}}\\
a''(x)=-\frac{1}{4}(1+x)^{-\frac{3}{2}}\\
a(x)=1+\frac{1}{2}x-\frac{1}{4*2}x^2\\
b(x)=\sqrt{1-x}\\
b'(x)=-\frac{1}{2}(1-x)^{-\frac{1}{2}}\\
b''(x)=-\frac{1}{4}(1+x)^{-\frac{3}{2}}\\
b(x)=1-\frac{1}{2}x-\frac{1}{4*2}x^2\\
原式=-\frac{1}{4}
$$

$$
\lim_{x\rightarrow0}\frac{e^{-\frac{x^2}{2}}-1+\frac{x^2}{2}}{x^3\arcsin x}\\
\lim_{x\rightarrow0}\frac{e^{-\frac{x^2}{2}}-1+\frac{x^2}{2}}{x^4}\\
f(x)=f(0)+f'(0)x+\frac{f''(0)}{2!}x^2\\
a(x)=e^x\\
a'(x)=e^x\\
a''(x)=e^x\\
a(x)=1+x+\frac{1}{2}x^2\\
a(-\frac{x^2}{2})=1-\frac{x^2}{2}+\frac{1}{2}*\frac{x^4}{4}\\
原式=\frac{1}{8}
$$

$$
|f'(x)|\leqslant \frac{M}{2}\\
f(0)=f(x)+f'(x)(0-x)+\frac{f''(\xi)}{2!}(0-x)^2,\xi\in(0,x)\\
f(1)=f(x)+f'(x)(1-x)+\frac{f''(\eta)}{2!}(1-x)^2,\eta\in(x,1)\\
f(x)+f'(x)(0-x)+\frac{f''(\xi)}{2!}(0-x)^2=f(x)+f'(x)(1-x)+\frac{f''(\eta)}{2!}(1-x)^2\\
f'(x)=\frac{f''(\xi)}{2!}(0-x)^2-\frac{f''(\eta)}{2!}(1-x)^2\\
|f'(x)|=\frac{1}{2}|f''(\xi)x^2-f''(\eta)(1-x)^2|\leqslant \frac{M}{2}|2x-1|\leqslant\frac{M}{2}
$$

$$
f(x)在(a,b)内为凹函数\\
x_0=\frac{x_1+x_2}{2}\\
f(x)=f(x_0)+f'(x_0)(x-x_0)+\frac{f''(\xi)}{2!}(x-x_0)^2,\xi\in(x_0,x)\\
f''(x)>0,\therefore f(x)\geqslant f(x_0)+f'(x_0)(x-x_0),当且仅当x=x_0等式成立\\
\begin{cases}
\frac{1}{2}f(x_1)>\frac{1}{2}f(x_0)+\frac{1}{2}f'(x_0)(x_1-x_0)\\
\frac{1}{2}f(x_2)>\frac{1}{2}f(x_0)+\frac{1}{2}f'(x_0)(x_2-x_0)
\end{cases}\\
\frac{f(x_1)+f(x_2)}{2}>f(x_0)\\
\frac{f(x_1)+f(x_2)}{2}>f(\frac{x_1+x_2}{2})\\
由凹函数定义得,f(x)在(a,b)内为凹函数
$$

