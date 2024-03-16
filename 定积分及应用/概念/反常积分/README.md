# 反常积分

## 右区间无限

### 定义

$$
f(x)\in C[a,+\infin),\int_a^{+\infin}f(x)dx\\
\lim_{b\rightarrow\infin}[F(b)-F(a)]=A\Rightarrow\int_a^{+\infin}f(x)dx=A\\
\lim_{b\rightarrow\infin}[F(b)-F(a)]不存在\Rightarrow\int_a^{+\infin}f(x)dx发散
$$

$$
\int_1^{+\infin}\frac{dx}{\sqrt{x}(1+x)}\\
\forall b>1, \int_1^{b}\frac{dx}{\sqrt{x}(1+x)}=2\int_1^{b}\frac{d\sqrt{x}}{1+(\sqrt{x})^2}=2\arctan\sqrt{x}\mid_1^b=2(\arctan\sqrt{b}-\frac{\pi}{4})\\
\because\lim_{b\rightarrow+\infin}2(\arctan\sqrt{b}-\frac{\pi}{4})=\frac{\pi}{2}\\
\therefore\int_1^{+\infin}\frac{dx}{\sqrt{x}(1+x)}=\frac{\pi}{2}
$$

### 判别法

$$
若\exist \alpha>1:\lim_{x\rightarrow+\infin}x^\alpha f(x)存在\Rightarrow收敛\\
若\exist \alpha\leq1:\lim_{x\rightarrow+\infin}x^\alpha f(x)
\begin{cases}
=A\neq 0\\
=\infin
\end{cases}
\Rightarrow发散
$$

$$
\int_0^{+\infin}\frac{\sqrt xdx}{4+x^2}\\
\because\lim_{x\rightarrow\infin}x^{\frac{3}{2}}*\frac{\sqrt{x}}{4+x^2}=1且\alpha=\frac{3}{2}>1\\
\therefore\int_0^{+\infin}\frac{\sqrt xdx}{4+x^2}收敛
$$

## 左区间无限

### 定义

$$
f(x)\in C(-\infin,a],\int_{-\infin}^af(x)dx\\
\forall b<a,\int_b^af(x)dx=F(a)-F(b)\\
若\lim_{b\rightarrow-\infin}[F(a)-F(b)]=A\Rightarrow\int_{-\infin}^af(x)dx=A\\
若\lim_{b\rightarrow-\infin}[F(a)-F(b)]不存在\Rightarrow\int_{-\infin}^af(x)dx发散\\
$$

### 判别法

$$
若\exist \alpha>1:\lim_{x\rightarrow-\infin}x^\alpha f(x)存在\Rightarrow收敛\\
若\exist \alpha\leq1:\lim_{x\rightarrow-\infin}x^\alpha f(x)
\begin{cases}
=A\neq 0\\
=\infin
\end{cases}
\Rightarrow发散
$$

## Gamma函数

$$
\Gamma(\alpha)=\int_0^{+\infin}x^{\alpha-1}e^{-x}dx\\
\int_0^{+\infin}x\sqrt{x}e^{-x}dx=\int_0^{+\infin}x^{\frac{3}{2}}e^{-x}dx=\Gamma(\frac{5}{2})\\
\begin{cases}
\Gamma(\alpha+1)=\alpha\Gamma(\alpha)\\
\Gamma(n+1)=n!\\
\Gamma(\frac{1}{2})=\sqrt{\pi}
\end{cases}
$$

$$
\int_0^{+\infin}x^7e^{-x^2}dx=\frac{1}{2}\int_0^{+\infin}(x^2)^3e^{-x^2}dx^2=\frac{1}{2}\int_0^{+\infin}x^3e^{-x}dx=\frac{1}{2}\Gamma(4)=3
$$

$$
\int_0^{+\infin}x\sqrt{x}e^{-x}dx=\int_0^{+\infin}x^{\frac{3}{2}}e^{-x}dx=\Gamma(\frac{3}{2}+1)=\frac{3}{2}\Gamma(\frac{3}{2})=\frac{3}{2}*\frac{1}{2}*\Gamma(\frac{1}{2})=\frac{3\sqrt{\pi}}{4}\\
$$

## 左端点无穷

### 定义

$$
f(x)\in C(a,b]且f(a+0)=\infin,\int_a^bf(x)dx\\
\forall\epsilon>0,\int_{a+\epsilon}^bf(x)dx=F(b)-F(a+\epsilon)\\
\lim_{\epsilon\rightarrow0^+}[F(b)-F(a+\epsilon)]=A\Rightarrow\int_a^bf(x)dx=A\\
\lim_{\epsilon\rightarrow0^+}[F(b)-F(a+\epsilon)]不存在\Rightarrow\int_a^bf(x)dx发散\\
$$

### 判别法

$$
若\exist\alpha<1:\lim_{x\rightarrow a^+}(x-a)^\alpha f(x)存在\Rightarrow收敛\\
若\exist\alpha\geq1:\lim_{x\rightarrow a^+}(x-a)^\alpha f(x)
\begin{cases}
=A\neq0\\
=\infin
\end{cases}
\Rightarrow发散
$$

$$
\int_0^\frac{1}{2}\frac{dx}{\sqrt{x(1-x)}}\\
\forall\epsilon>0,\int_\epsilon^\frac{1}{2}\frac{dx}{\sqrt{x(1-x)}}=2\int_\epsilon^\frac{1}{2}\frac{d\sqrt x}{\sqrt{1-(\sqrt x)^2}}=2\arcsin\sqrt{x}\mid_\epsilon^\frac{1}{2}=2(\frac{\pi}{4}-\arcsin\sqrt{\epsilon})\\
\because\lim_{\epsilon\rightarrow 0^+}2(\frac{\pi}{4}-\arcsin\sqrt{\epsilon})=\frac{\pi}{2}\\
\therefore\int_0^\frac{1}{2}\frac{dx}{\sqrt{x(1-x)}}=\frac{\pi}{2}
$$

$$
\int_0^1\frac{dx}{\sqrt{x(x+1)}}\\
\lim_{x\rightarrow 0^+}(x-0)^{\frac{1}{2}}\frac{1}{\sqrt{x(x+1)}}=1且\alpha=\frac{1}{2}<1,\therefore收敛\\
\int_0^1\frac{dx}{\sqrt{x(x+1)}}=2\int_0^1\frac{d\sqrt x}{\sqrt{(\sqrt x)^2+1}}=2\int_0^1\frac{dx}{\sqrt{x^2+1}}=2\ln(x+\sqrt{x^2+1})\mid_0^1=2\ln(1+\sqrt{2})
$$

## 右端点无穷

### 定义

$$
f(x)\in C[a,b)且f(b-0)=\infin,\int_a^bf(x)dx\\
\forall\epsilon>0,\int_a^{b-\epsilon}f(x)dx=F(b-\epsilon)-F(a)\\
\lim_{\epsilon\rightarrow0^+}[F(b-\epsilon)-F(a)]=A\Rightarrow\int_a^bf(x)dx=A\\
\lim_{\epsilon\rightarrow0^+}[F(b-\epsilon)-F(a)]不存在\Rightarrow\int_a^bf(x)dx发散\\
$$

### 判别法

$$
若\exist\alpha<1:\lim_{x\rightarrow b^-}(b-x)^\alpha f(x)存在\Rightarrow收敛\\
若\exist\alpha\geq1:\lim_{x\rightarrow b^-}(b-x)^\alpha f(x)
\begin{cases}
=A\neq0\\
=\infin
\end{cases}
\Rightarrow发散
$$

