$$
将函数f(x)=2+|x|(|x|\leq 1)展开成以2为周期的傅里叶级数，并求\sum_{n=1}^\infin\frac{1}{n^2}.
$$

$$
f(x)在[-1,1]上满足收敛定理的条件，且f(x)为偶函数
$$

$$
\begin{align}
f(x)&=
\begin{cases}
2-x,-1\leq x<0\\
2+x,0\leq x\leq1
\end{cases}\\
l&=1\\
a_0&=\frac{1}{l}\int_{-l}^{l}f(x)dx=\int_{-1}^{1}f(x)dx=2\int_{0}^{1}f(x)dx=2\int_{0}^{1}(2+x)dx=5\\
a_n&=\frac{1}{l}\int_{-l}^{l}f(x)\cos\frac{n\pi x}{l}dx=\int_{-1}^{1}f(x)\cos{n\pi x}dx=2\int_{0}^{1}(2+x)\cos{n\pi x}dx=\frac{2[(-1)^n-1]}{(n\pi)^2}
(n=1,2,...)=
\begin{cases}
\frac{-4}{n^2\pi^2},n=1,3,5,...\\
0,n=2,4,6,...
\end{cases}\\
b_n&=\frac{1}{l}\int_{-l}^{l}f(x)\sin\frac{n\pi x}{l}dx=0\\
f(x)&=\frac{a_0}{2}+\sum_{n=1}^\infin(a_n\cos{n\pi x}+b_n\sin{n\pi x})=\frac{5}{2}+\sum_{n=1}^\infin\frac{2[(-1)^n-1]}{(n\pi)^2}\cos{n\pi x}=\frac{5}{2}-\sum_{n=0}^\infin\frac{4}{[(2n+1)\pi]^2}\cos{(2n+1)\pi x},|x|\leq1\\
\end{align}
$$

$$
令x=0,f(0)=2=\frac{5}{2}+\sum_{n=0}^\infin\frac{4}{[(2n+1)\pi]^2}=\frac{5}{2}-\sum_{n=0}^\infin\frac{4}{[(2n+1)\pi]^2}=\frac{5}{2}-\frac{4}{\pi^2}\sum_{n=0}^\infin\frac{1}{(2n+1)^2}\\
\begin{align}
\sum_{n=0}^\infin\frac{1}{(2n+1)^2}&=\frac{\pi^2}{8}\\
\sum_{n=1}^\infin\frac{1}{n^2}&=\sum_{n=0}^\infin\frac{1}{(2n+1)^2}+\sum_{n=1}^\infin\frac{1}{(2n)^2}\\
\sum_{n=1}^\infin\frac{1}{n^2}&=\frac{\pi^2}{6}
\end{align}
$$

---

$$
将函数f(x)=
\begin{cases}
|x|,0<|x|<\frac{\pi}{2}\\
0,\frac{\pi}{2}\leq|x|\leq\pi
\end{cases}
展开成傅里叶级数
$$

$$
显然f(x)在[-\pi,\pi]上满足收敛定理条件，将函数进行周期延拓
$$

$$
\begin{align}
l&=\pi\\
a_0&=\frac{2}{\pi}\int_{0}^\frac{\pi}{2}f(x)dx=\frac{\pi}{4}\\
a_n&=\frac{2}{\pi}\int_{0}^\frac{\pi}{2}f(x)\cos{nx}dx=\frac{2}{n\pi}(\frac{\pi}{2}\sin\frac{n\pi}{2}+\frac{1}{n}\cos\frac{n\pi}{2}-\frac{1}{n})\\
b_n&=0\\
f(x)&=
\begin{cases}
\frac{\pi}{8}+\sum_{n=1}^{\infin}\frac{2}{n\pi}(\frac{\pi}{2}\sin\frac{n\pi}{2}+\frac{1}{n}\cos\frac{n\pi}{2}-\frac{1}{n})\cos{nx},|x|\leq\pi且|x|\neq\frac{\pi}{2}\\
\frac{\pi}{4},|x|=\frac{\pi}{2}
\end{cases}
\end{align}
$$

---

$$
将函数f(x)=x-1(0\leq x\leq 2)展开成以4为周期的余弦级数
$$

$$
将f(x)进行偶延拓和周期延拓
$$

$$
\begin{align}
l&=2\\
b_n&=0\\
a_0&=\int_0^2x-1dx=0\\
a_n&=\int_0^2x\cos\frac{n\pi x}{2}dx-\int_0^2\cos\frac{n\pi x}{2}dx=(\frac{2}{n\pi})^2(\cos{n\pi}-1)\\
f(x)&=\sum_{n=1}^\infin (\frac{2}{n\pi})^2(\cos{n\pi}-1)\cos\frac{n\pi x}{2}=-2\sum_{n=0}^\infin (\frac{-2}{(2n+1)\pi})^2\cos\frac{(2n+1)\pi x}{2},0\leq x\leq2
\end{align}
$$

