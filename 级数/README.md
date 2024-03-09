# 常数项级数

$$
\sum_{n=1}^{\infin}a_n
$$

## 部分和

$$
S_n=a_1+a_2+...+a_n\\
\lim_{n\rightarrow\infin}S_n=\sum_{n=1}^{\infin}a_n\\
\lim_{n\rightarrow\infin}S_n=
\begin{cases}
=S,\sum_{n=1}^{\infin}a_n=S\\
不存在，\sum_{n=1}^{\infin}a_n发散
\end{cases}
$$

## 常数项级数的性质

1. 

$$
\sum_{n=1}^{\infin}a_n=A,\sum_{n=1}^{\infin}b_n=B\Rightarrow\sum_{n=1}^{\infin}(a_n\pm b_n)=\sum_{n=1}^{\infin}a_n\pm \sum_{n=1}^{\infin}b_n=a\pm b
$$

2. 

$$
\sum_{n=1}^{\infin}a_n=S\Rightarrow \sum_{n=1}^{\infin}ka_n=k\sum_{n=1}^{\infin}a_n=kS
$$

3. 级数前面添加、减少改变有限项，敛散性不变（若收敛，和会改变）

4. 添加括号不降收敛性

5. 若级数收敛，则
   $$
   \lim_{n\rightarrow\infin}S_n=S\\
   a_n=S_n-S_{n-1}\\
   \lim_{n\rightarrow\infin}a_n=\lim_{n\rightarrow\infin}S_n-\lim_{n\rightarrow\infin}S_{n-1}=S-S=0\\
   \sum_{n-1}^{\infin}a_n收敛\Rightarrow
   \begin{cases}
   \lim_{n\rightarrow\infin}a_n=0\\
   \lim_{n\rightarrow\infin}S_n\exist
   \end{cases}
   $$

6. 

## 两个重要的级数

### p-级数

$$
\sum_{n=1}^{\infin}\frac{1}{n^p}\\
p=1,\sum_{n=1}^{\infin}\frac{1}{n},调和级数\\
\begin{cases}
p>1,收敛\\
p\leq 1,发散
\end{cases}
$$

### 几何级数

$$
\sum_{n=1}^{\infin}aq^n(a\neq0)\\
\begin{cases}
|q|\geq 1,发散\\
|q|< 1,收敛于\sum_{n=1}^{\infin}aq^n=\frac{第一项}{1-q}
\end{cases}
$$

## 正项级数及敛散性

$$
\sum_{n=1}^{\infin}a_n(a_n\geq0,n=1,2,...)\\
S_1\leq S_2\leq S_3\leq ...,即\{S_n\}\uparrow\\
\{S_n\}无界\Rightarrow\lim_{n\rightarrow\infin}S_n=+\infin,即\sum_{n=1}^{\infin}a_n=+\infin\\
\exists M>0,使S_n\leq M\Rightarrow\lim_{n\rightarrow\infin}S_n\exist\Rightarrow\sum_{n=1}^{\infin}a_n收敛
$$

### 比较审敛法

$$
a_n\geq0,b_n\geq0(n=1,2,...)\\
a_n\leq b_n且\sum_{n=1}^{\infin}b_n收敛\Rightarrow\sum_{n=1}^{\infin}a_n收敛\\
a_n\geq b_n且\sum_{n=1}^{\infin}b_n发散\Rightarrow\sum_{n=1}^{\infin}a_n发散\\
$$

#### 极限

$$
a_n>0,b_n>0(n=1,2,...)\\
\lim_{n\rightarrow\infin}\frac{b_n}{a_n}=l(0<l<+\infin)\Rightarrow\sum_{n=1}^\infin a_n,\sum_{n=1}^\infin b_n敛散性同
$$

### 比值法

$$
a_n>0(n=1,2,...)\\
\lim_{n\rightarrow\infin}\frac{a_{n+1}}{a_n}<1\Rightarrow收敛\\
\lim_{n\rightarrow\infin}\frac{a_{n+1}}{a_n}>1\Rightarrow发散\\
\lim_{n\rightarrow\infin}\frac{a_{n+1}}{a_n}=1\Rightarrow ?\\
$$

### 根值法

$$
a_n>0(n=1,2,...)\\
\lim_{n\rightarrow\infin}\sqrt[n]{a_n}=\rho\\
\rho<1,收敛\\
\rho>1,发散\\
\rho=1,?\\
$$

## 交错级数及敛散性

$$
a_1-a_2+a_3-a_4+...=\sum_{n=1}^\infin(-1)^{n-1}a_n\\
-a_1+a_2-a_3+a_4-...=\sum_{n=1}^\infin(-1)^{n}a_n\\
(a_n>0,n=1,2,...)
$$

### 莱布尼茨法

$$
\sum_{n=1}^\infin(-1)^{n-1}a_n(a_n>0,n=1,2,...)\\
\{a_n\}\downarrow且\lim_{n\rightarrow\infin}a_n=0\Rightarrow\sum_{n=1}^\infin(-1)^{n-1}a_n收敛,S\leq a_1
$$

## 任意级数

$$
若\sum_{n=1}^{\infin}|a_n|收敛,称\sum_{n=1}^{\infin}a_n绝对收敛\\
若\sum_{n=1}^{\infin}a_n收敛,而\sum_{n=1}^{\infin}|a_n|发散,称\sum_{n=1}^{\infin}a_n条件收敛\\
若\sum_{n=1}^{\infin}a_n绝对收敛\Rightarrow\sum_{n=1}^{\infin}a_n收敛\\
$$

# 幂级数

$$
\sum_{n=0}^\infin a_nx^n=a_0+a_1x+a_2x^2+...\\
\sum_{n=0}^\infin a_n(x-x_0)^n=a_0+a_1(x-x_0)+a_2(x-x_0)^2+...\\
$$

## 收敛域

$$
\sum_{n=0}^\infin x^n=1+x+x^2+...\\
x=\frac{2}{3}:1+\frac{2}{3}+(\frac{2}{3})^2+...=\frac{1}{1-\frac{1}{3}}=3,x=\frac{2}{3}收敛点\\
x=2:1+2+2^2+...,x=2发散点
$$

一切收敛点构成的集合

## 收敛半径

$$
\sum_{n=0}^\infin a_nx^n,\exist R\geq0\\
当|x|<R或x\in(-R,R):绝对收敛\\
当|x|>R或x\in(-\infin,-R)\cup(R,+\infin):发散\\
当|x|=R,即x=\pm R:?
$$

R称为收敛半径

## R及收敛域

$$
\sum_{n=0}^\infin a_nx^n\\
\lim_{n\rightarrow \infin}|\frac{a_{n+1}}{a_n}|=\rho或\lim_{n\rightarrow \infin}\sqrt[n]{|a_n|}=\rho\\
\rho =+\infin\Rightarrow R=0,唯一收敛域x=0\\
\rho=0\Rightarrow R=+\infin,收敛域(-\infin,+\infin)\\
0<\rho<+\infin\Rightarrow R=\frac{1}{\rho}
$$

$$
\sum_{n=0}^\infin a_nx^{2n+1}\\
\lim_{n\rightarrow \infin}|\frac{a_{n+1}}{a_n}|=\rho或\lim_{n\rightarrow \infin}\sqrt[n]{|a_n|}=\rho\\
\Rightarrow R=\sqrt{\frac{1}{\rho}}\\
对\sum_{n=0}^\infin a_nx^{n},若\sum_{n=0}^\infin a_nx_0^{n}条件收敛\Rightarrow|x_0|=R
$$

## 分析性质

$$
\sum_{n=0}^\infin a_nx^{n}=S(x),x\in(-R,R)\\
S(x)\in C(-R,R)\\
x=-R为收敛点，则\sum_{n=0}^\infin a_n(-R)^{n}=S(-R+0)\\
x=R为收敛点，则\sum_{n=0}^\infin a_nR^{n}=S(R-0)\\
(逐项可导性)x\in(-R,R):\\
S'(x)=(\sum_{n=0}^\infin a_nx^{n})'=\sum_{n=0}^\infin (a_nx^{n})'=\sum_{n=1}^\infin na_nx^{n-1}\\
且\sum_{n=1}^\infin na_nx^{n-1}收敛半径R\\
(逐项可积性)x\in(-R,R):\\
\int_0^xS(x)dx=\int_0^x(\sum_{n=0}^\infin a_nx^{n})dx=\sum_{n=0}^\infin \int_0^x a_nx^{n}dx=\sum_{n=0}^\infin \frac{a_n}{n+1}x^{n+1}\\
且\sum_{n=0}^\infin \frac{a_n}{n+1}x^{n+1}收敛半径R
$$

## 函数展成幂级数

$$
f(x):x=x_0\\
\sum_{n=0}^\infin a_n(x-x_0)^n
$$

### 直接法

$$
f(x)在x=x_0邻域内有n+1阶导数\\
\Rightarrow f(x)=P_n(x)+R_n(x)\\
P_n(x)=f(x_0)+f'(x_0)(x-x_0)+...+\frac{f^{(n)}(x_0)}{n!}(x-x_0)^n\\
R_n(x)=
\begin{cases}
\frac{f^{(n+1)}(\xi)}{(n+1)!}(x-x_0)^{n+1},拉格朗日型\\
o((x-x_0)^n),皮亚诺型
\end{cases}\\
f(x)在x=x_0邻域内任意阶可导\\
f(x)=\sum_{n=0}^\infin\frac{f^{(n)}(x_0)}{n!}(x-x_0)^n,(?)\\
x_0=0:f(x)\sum_{n=0}^\infin\frac{f^{(n)}(0)}{n!}x^n,麦克劳林级数,(?)\\
$$

$$
e^x=1+x+\frac{x^2}{2!}+...+\frac{x^n}{n!}+...=\sum_{n=0}^\infin\frac{x^n}{n!},(-\infin<x<+\infin)\\
\sin x=x-\frac{x^3}{3!}+\frac{x^5}{5!}-...=\sum_{n=0}^\infin\frac{(-1)^n}{(2n+1)!}x^{2n+1},(-\infin<x<+\infin)\\
\cos x=1-\frac{x^2}{2!}+\frac{x^4}{4!}-...=\sum_{n=0}^\infin\frac{(-1)^n}{(2n)!}x^{2n},(-\infin<x<+\infin)\\
\frac{1}{1-x}=1+x+...+x^n+...=\sum_{n=0}^\infin x^n,(-1<x<1)\\
\frac{1}{1+x}=\sum_{n=0}^\infin (-1)^nx^n,(-1<x<1)\\
\ln(1+x)=x-\frac{x^2}{2}+\frac{x^3}{3}-\frac{x^4}{4}+...=\sum_{n=1}^\infin\frac{(-1)^{n-1}}{n}x^n,(-1<x\leq 1)\\
1-\frac{1}{2}+\frac{1}{3}-\frac{1}{4}+...=\ln 2\\
-\ln(1-x)=\sum_{n=1}^\infin\frac{x^n}{n},(-1\leq x< 1)\\
$$

### 间接法

$$
\begin{cases}
1到7\\
逐项可导,逐项可积
\end{cases}
$$

## 求S(x)

$$
\sum P(n)x^n:4、5\\
\sum\frac{x^n}{P(n)}
\begin{cases}
6、7\\
逐项可积性\\
\end{cases}
$$

# 傅里叶级数

## 参数计算

$$
周期为2\pi的傅里叶函数f(x):\\
f(x)可否分解为\frac{a_0}{2}+\sum_{n=1}^{+\infin}(a_n\cos {nx}+b_n\sin{nx})\\
\frac{a_0}{2},直流成份\\
a_1\cos{x}+b_1\sin x,一次谐波\\
f(x)与\frac{a_0}{2}+\sum_{n=1}^{+\infin}(a_n\cos{nx}+b_n\sin{nx})\\
(狄利克雷充分条件)设f(x)以2\pi为周期，在[-\pi,\pi)上:\\
f(x)连续或有有限个第一类间断点\\
f(x)有有限个极值点\\
则f(x)可以展成\frac{a_0}{2}+\sum_{n=1}^{+\infin}(a_n\cos {nx}+b_n\sin{nx}),且\\
a_0=\frac{1}{\pi}\int_{-\pi}^{\pi}f(x)dx\\
a_n=\frac{1}{\pi}\int_{-\pi}^{\pi}f(x)\cos nxdx\\
b_n=\frac{1}{\pi}\int_{-\pi}^{\pi}f(x)\sin nxdx\\
n=1,2,...\\
若x为f(x)的连续点，则\frac{a_0}{2}+\sum_{n=1}^{+\infin}(a_n\cos {nx}+b_n\sin{nx})=f(x)\\
若x为f(x)的间断点，则\frac{a_0}{2}+\sum_{n=1}^{+\infin}(a_n\cos {nx}+b_n\sin{nx})=\frac{f(x-0)+f(x+0)}{2}\\
$$

## 周期延拓

$$
f(x)定义域[-\pi,\pi),f(x)周期延拓:\\
a_0=\frac{1}{\pi}\int_{-\pi}^{\pi}f(x)dx\\
a_n=\frac{1}{\pi}\int_{-\pi}^{\pi}f(x)\cos{nx}dx\\
b_n=\frac{1}{\pi}\int_{-\pi}^{\pi}f(x)\sin{nx}dx\\
f(x)=\frac{a_0}{2}+\sum_{n=1}^\infin(...),(-\pi<x<\pi)\\
$$

## 奇延拓、展成正弦级数

$$
f(x)定义域[0,\pi)\\
f(x)奇延拓或展成正弦级数\\
$$

$$
\begin{align}
&1.奇延拓、周期延拓\\
&2.a_0=0,a_n=0,b_n=\frac{2}{\pi}\int_0^\pi f(x)\sin{nx} dx\\
&3.f(x)=\sum_{n=1}^\infin b_n\sin nx,(0\leq x<\pi)
\end{align}
$$

## 偶延拓、展成余弦级数

$$
\begin{align}
&1.偶延拓、周期延拓\\
&2.a_0=\frac{2}{\pi}\int_0^{\pi}f(x)dx,a_n=\frac{2}{\pi}\int_0^\pi f(x)\cos{nx} dx,b_n=0\\
&3.f(x)=\frac{a_0}{2}+\sum_{n=1}^\infin a_n\cos nx,(0\leq x\leq\pi)
\end{align}
$$

## 以2l为周期的函数f(x)

$$
\begin{align}
&1.作图\\
&2.a_0=\frac{1}{l}\int_{-l}^{l}f(x)dx,a_n=\frac{1}{l}\int_{-l}^lf(x)\cos\frac{n\pi x}{l}dx,b_n=\frac{1}{l}\int_{-l}^{l}\sin\frac{n\pi x}{l}dx\\
&3.x为f(x)的连续点,f(x)=\frac{a_0}{2}+\sum_{n=1}^\infin a_n\cos \frac{n\pi x}{l}+b_n\sin\frac{n\pi x}{l},(-\infin<x<+\infin,x\neq?)\\
&4.x=?,\frac{a_0}{2}+\sum_{n=1}^\infin(...)=\frac{f(x-0)+f(x+0)}{2}
\end{align}
$$

## f(x)定义域[-l,l)上

1. 周期延拓

2. $$
   \begin{cases}
   a_0=\frac{1}{l}\int_{-l}^l f(x)dx\\
   a_n=\frac{1}{l}\int_{-l}^l f(x)\cos\frac{n\pi x}{l}dx\\
   b_n=\frac{1}{l}\int_{-l}^l f(x)\sin\frac{n\pi x}{l}dx\\
   \end{cases}
   $$

3. $$
   f(x)=\frac{a_0}{2}+...()
   $$

   