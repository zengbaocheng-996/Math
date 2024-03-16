# 定积分定义与一般性质

$$
\lim_{n\rightarrow\infin}(\frac{1}{\sqrt{n^2+1}}+\frac{1}{\sqrt{n^2+2}}+...+\frac{1}{\sqrt{n^2+n}})\\
\frac{n}{\sqrt{n^2+n}}\leq b_n\leq\frac{n}{\sqrt{n^2+1}}\\
原式=1
$$

$$
\lim_{n\rightarrow\infin}(\frac{1}{\sqrt{n^2+1^2}}+\frac{1}{\sqrt{n^2+2^2}}+...+\frac{1}{\sqrt{n^2+n^2}})\\
原式=\lim_{n\rightarrow\infin}\sum_{i=1}^n\frac{1}{\sqrt{n^2+i^2}}=\lim_{n\rightarrow\infin}\frac{1}{n}\sum_{i=1}^n\frac{1}{\sqrt{(\frac{i}{n})^2+1}}=\int_0^1\frac{dx}{\sqrt{x^2+1}}=\ln(x+\sqrt{x^2+1})|^1_0=\ln(1+\sqrt{2})
$$

$$
\lim_{n\rightarrow \infin}(\frac{\sqrt{n^4-i^4}}{n^4}+\frac{2\sqrt{n^4-2^4}}{n^4}+...+\frac{n\sqrt{(n^4-n^4)}}{n^4})\\
原式=\lim_{n\rightarrow \infin}\sum_{i=1}^n\frac{i\sqrt{n^4-i^4}}{n^4}=\lim_{n\rightarrow \infin}\frac{1}{n}\sum_{i=1}^n\frac{i}{n}\sqrt{1-(\frac{i}{n})^4}=\int_0^1 x\sqrt{1-x^4}dx
$$

$$
\lim_{n\rightarrow \infin}(\frac{1}{n^2+1^2}+\frac{2}{n^2+2^2}+...+\frac{n}{n^2+n^2})\\
原式=\lim_{n\rightarrow \infin}\sum_{i=1}^{n}\frac{i}{n^2+i^2}=\lim_{n\rightarrow \infin}\frac{1}{n}\sum_{i=1}^{n}\frac{\frac{i}{n}}{1+(\frac{i}{n})^2}=\int_0^1\frac{x}{1+x^2}dx=\frac{1}{2}\ln 2
$$

$$
-|f(x)|\leq f(x)\leq|f(x)|\\
-\int_a^b|f(x)|dx\leq\int_a^bf(x)dx\leq\int_a^b|f(x)|dx\\
-B\leq A\leq B\\
|\int_a^bf(x)dx|\leq\int_a^b|f(x)|dx
$$

$$
积分中值定理\\
f(x)\in C[a,b],\exists\xi\in[a,b]\\
\int_a^bf(x)dx=f(\xi)(b-a)
$$

$$
f(x)\in[a,b]\Rightarrow\exists m,M,使m\leq f(x)\leq M\\
\int_a^bmdx\leq\int_a^bf(x)dx\leq\int_a^bMdx\\
m(b-a)\leq\frac{1}{b-a}\int_a^bf(x)dx\leq M(b-a)\\
\exist\xi\in[a,b],使f(\xi)=\frac{1}{b-a}\int_a^bf(x)dx
$$

$$
f(x)\in C[0,1],(0,1)可导,f(1)=4\int_0^\frac{1}{4}f(x)dx\\
证:\exists\xi\in(0,1),使f'(\xi)=0\\
f(x)\in C[0,\frac{1}{4}]\Rightarrow\exists c\in[0,\frac{1}{4}],使\\
\int_0^\frac{1}{4}f(x)dx=f(c)(\frac{1}{4}-0)\Rightarrow 4\int_0^\frac{1}{4}f(x)dx=f(c)\\
\Rightarrow f(c)=f(1)\\
\exist\xi\in(c,1)\subset(0,1),使f'(\xi)=0
$$

# 积分基本定理与特殊性质

$$
积分上限函数\\
\Phi(x)=\int_a^xf(x)dx=\int_a^xf(t)dt
$$

$$
\int_a^xf(x,t)dt在表达式中的x与上限x同
$$

$$
设f(x)\in C[a,b],\Phi(x)=\int_a^xf(t)dt则\\
\Phi'(x)=\frac{d}{dx}\int_a^xf(t)dt=f(x)\\
证: \Delta\Phi=\Phi(x+\Delta x)-\Phi(x)=\int_a^{x+\Delta x}f(t)dt-\int_a^xf(t)dt=\int_x^{x+\Delta x}f(t)dt\\
\because f(x)\in C[a,b],\therefore\Delta\Phi=f(\xi)\Delta x~(\xi在x与x+\Delta x之间)\\
\Rightarrow\frac{\Delta\Phi}{\Delta x}=f(\xi)\Rightarrow\lim_{\Delta x\rightarrow 0}\frac{\Delta\Phi}{\Delta x}=\lim_{\Delta x\rightarrow 0}f(\xi)\\
\because f(x)连续,\therefore\lim_{\Delta x\rightarrow 0}f(\xi)=\lim_{\xi\rightarrow x}f(\xi)=f(x)\\
\Rightarrow\Phi'(x)=f(x)
$$

$$
\frac{d}{dx}\int_a^{\phi(x)}f(t)dt=f[\phi(x)]\phi'(x)
$$

$$
f(x)连续,f(0)=0,f'(0)=\pi,求\lim_{x\rightarrow 0}\frac{\int_0^xf(t)dt}{x-\ln(1+x)}\\
原式=\lim_{x\rightarrow 0}\frac{f(x)}{1-\frac{1}{x+1}}=\lim_{x\rightarrow 0}\frac{(x+1)f(x)}{x}=\lim_{x\rightarrow 0}\frac{f(x)+(x+1)f'(x)}{1}=f(0)+f'(0)=\pi
$$

$$
设函数f(x)连续,\phi(x)=\int_0^x(x-t)f(t)dt,求\phi''(x)
$$

$$
\begin{align}
\phi(x)&=x\int_0^xf(t)dt-\int_0^xtf(t)dt\\
\phi'(x)&=\int_0^xf(t)dt+xf(x)-xf(x)\\
\phi''(x)&=f(x)
\end{align}
$$

$$
\int_a^bf(x)dx=\lim_{\lambda\rightarrow 0}\sum_{i=1}^nf(\xi_i)\Delta x_i\\
牛顿莱布尼茨公式\\
f(x)\in C[a,b],F'(x)=f(x)\\
则\int_a^bf(x)dx=F(b)-F(a)\\
证:\Phi(x)=\int_a^xf(t)dt,\Phi'(x)=f(x)\\
\because F'(x)=f(x),\therefore F(x)-\Phi(x)=C_0(a\leq x\leq b)\\
\Rightarrow F(a)-\Phi(a)=F(b)-\Phi(b)\\
\because \Phi(a)=0,\therefore\Phi(b)=F(b)-F(a)\\
即\int_a^bf(t)dt=F(b)-F(a)或\int_a^bf(x)dx=F(b)-F(a)
$$

$$
\int_0^1\frac{x}{1+x^4}dx=\frac{1}{2}\int_0^1\frac{d(x^2)}{1+(x^2)^2}=\frac{1}{2}\arctan x^2\mid_0^1=\frac{\pi}{8}
$$

## 换元积分法

$$
\begin{align}
&~~~~~\int_0^4\frac{x+1}{\sqrt{2x+1}}dx\\
&=\frac{1}{4}\int_0^4\frac{(2x+1)+1}{\sqrt{2x+1}}d(2x+1)\\
&=\frac{1}{4}\int_0^4(2x+1)^{\frac{1}{2}}d(2x+1)+\frac{1}{2}\int_0^4\frac{d(2x+1)}{2\sqrt{2x+1}}\\
&=\frac{1}{4}*\frac{2}{3}(2x+1)^{\frac{3}{2}}\mid_0^4+\frac{1}{2}\sqrt{2x+1}\mid_0^4\\
&=\frac{16}{3}
\end{align}
$$

$$
\begin{align}
&\int_0^4\frac{x+1}{\sqrt{2x+1}}dx\\
令\sqrt{2x+1}&=t\Rightarrow x=\frac{1}{2}(t^2-1)\\
&=\int_1^3\frac{\frac{1}{2}(t^2+1)}{t}*tdt\\
&=\int_1^3\frac{1}{2}(t^2+1)dt\\
&=\frac{1}{2}*(\frac{t^3}{3}\mid_1^3+2)\\
&=\frac{16}{3}
\end{align}
$$

$$
\int_0^2xe^{-x^2}dx=\frac{1}{2}\int_0^2e^{-x^2}d(x^2)=\frac{1}{2}\int_0^4e^{-x}d(x)=-\frac{1}{2}e^{-x}\mid_0^4=\frac{1}{2}(1-e^{-4})
$$

$$
设f(x)连续,f(0)=0,f'(0)=4,求\lim_{x\rightarrow 0}\frac{\int_0^xtf(x^2-t^2)dt}{x^4}\\
\int_0^xtf(x^2-t^2)dt=-\frac{1}{2}\int_0^xf(x^2-t^2)d(-t^2)=-\frac{1}{2}\int_0^xf(x^2-t^2)d(x^2-t^2)=-\frac{1}{2}\int_{x^2}^0f(u)du=\frac{1}{2}\int_0^{x^2}f(u)du\\
\lim_{x\rightarrow 0}\frac{\int_0^xtf(x^2-t^2)dt}{x^4}=\frac{1}{4}\lim_{x\rightarrow 0}\frac{f(x^2)}{x^2}=\frac{1}{4}\lim_{x\rightarrow 0}\frac{f(x^2)-f(0)}{x^2}=\frac{1}{4}f'(0)=1\\
$$

## 分部积分法

$$
(uv)'=u'v+uv'\\
\Rightarrow uv\mid_a^b=\int_a^bvdu+\int_a^budv\\
\Rightarrow\int_a^budv=uv\mid_a^b-\int_a^bvdu
$$

$$
\begin{align}
&~~~~~\int_0^1x\ln(1+x)dx\\
&=\int_0^1\ln(1+x)d(\frac{1}{2}x^2)\\
&=\frac{x^2}{2}\ln(1+x)\mid_0^1-\frac{1}{2}\int_0^1\frac{(x^2-1)+1}{x+1}dx\\
&=\frac{1}{2}\ln 2-\frac{1}{2}\int_0^1(x-1+\frac{1}{x+1})dx\\
&=\frac{1}{2}\ln 2-\frac{1}{2}(\frac{1}{2}-1+\ln 2)\\
&=\frac{1}{4}
\end{align}
$$

## 特殊性质

### 对称区间

$$
设f(x)\in C[-a,a],则\int_{-a}^af(x)dx=\int_{0}^a[f(x)+f(-x)]dx\\
证:左=\int_{-a}^0f(x)dx+\int_{0}^af(x)dx\\
而\int_{-a}^0f(x)dx=\int_{-a}^0f(-t)d(-t)=\int_{0}^af(-t)dt=\int_{0}^af(-x)dx\\
左=\int_{0}^a[f(x)+f(-x)]dx\\
若f(-x)=-f(x)\Rightarrow\int_{-a}^af(x)dx=0\\
若f(-x)=f(x)\Rightarrow\int_{-a}^af(x)dx=2\int_{0}^af(x)dx
$$

$$
\int_{-\frac{\pi}{4}}^{\frac{\pi}{4}}\frac{1}{e^x+1}dx=\int_0^{\frac{\pi}{4}}(\frac{1}{e^x+1}+\frac{1}{e^{-x}+1})dx=\int_0^{\frac{\pi}{4}}(\frac{1}{e^x+1}+\frac{e^{x}}{e^{x}+1})dx=\frac{\pi}{4}\\
$$

$$
I=\int_{-\frac{\pi}{4}}^{\frac{\pi}{4}}\frac{1}{1-\sin x}dx=\int_0^{\frac{\pi}{4}}(\frac{1}{1-\sin x}+\frac{1}{1+\sin x})dx=\int_0^{\frac{\pi}{4}}\frac{2}{1-\sin^2x}=2\int_0^{\frac{\pi}{4}}\sec^2xdx=2\tan x\mid_0^\frac{\pi}{4}=2
$$

### 三角函数

$$
设f(x)\in C[0,1],则\int_0^\frac{\pi}{2}f(\sin x)dx=\int_0^\frac{\pi}{2}f(\cos x)dx\\
x=-t,\int_0^{-a}=\int_0^a\\
x+t=a+b,\int_a^b=\int_a^b\\
证:x+t=\frac{\pi}{2},d(x+t)=dx+dt=0\\
\int_0^\frac{\pi}{2}f(\sin x)dx=\int_\frac{\pi}{2}^0f(\cos t)(-dt)=\int_0^\frac{\pi}{2}f(\cos t)dt\\
\int_0^\frac{\pi}{2}f(\sin x)dx=\int_0^\frac{\pi}{2}f(\cos x)dx
$$

$$
I=\int_0^{\frac{\pi}{2}}\frac{\sin x}{\sin x+\cos x}dx\\
I=\int_0^{\frac{\pi}{2}}\frac{\cos x}{\cos x+\sin x}dx\\
2I=\int_0^{\frac{\pi}{2}}1dx=\frac{\pi}{2}\\
I=\frac{\pi}{4}
$$

$$
I=\int_0^{\frac{\pi}{2}}\sin^2xdx\\
I=\int_0^{\frac{\pi}{2}}\cos^2xdx\\
2I=\int_0^{\frac{\pi}{2}}1dx=\frac{\pi}{2}\\
I=\frac{\pi}{4}
$$

$$
记:\int_0^{\frac{\pi}{2}}\sin^nxdx=\int_0^{\frac{\pi}{2}}\cos^nxdx=I_n\\
\begin{cases}
I_n=\frac{n-1}{n}I_{n-2}\\
I_0=\frac{\pi}{2}\\
I_1=1
\end{cases}
$$

$$
\int_0^{\frac{\pi}{2}}\sin^{10}x=I_{10}=\frac{9}{10}I_8=\frac{9}{10}*\frac{7}{8}*I_6=\frac{9}{10}*\frac{5}{6}*\frac{3}{4}*\frac{1}{2}*I_0=\frac{9}{10}*\frac{5}{6}*\frac{3}{4}*\frac{1}{2}*\frac{\pi}{2}\\
\int_0^{\frac{\pi}{2}}\cos^{11}x=I_{11}=\frac{10}{11}*\frac{8}{9}*\frac{6}{7}*\frac{4}{5}*\frac{2}{3}*I_1=\frac{10}{11}*\frac{8}{9}*\frac{6}{7}*\frac{4}{5}*\frac{2}{3}*1
$$

$$
I=\int_0^{\frac{\pi}{2}}\sin^8x\cos^2xdx\\
I=\int_0^{\frac{\pi}{2}}\sin^8x(1-\sin^2x)dx=\int_0^{\frac{\pi}{2}}\sin^8xdx-\int_0^{\frac{\pi}{2}}\sin^{10}xdx=\frac{7}{8}*\frac{5}{6}*\frac{3}{4}*\frac{1}{2}*I_0-\frac{9}{10}*\frac{7}{8}*\frac{5}{6}*\frac{3}{4}*\frac{1}{2}I_0=\frac{1}{10}*\frac{7}{8}*\frac{5}{6}*\frac{3}{4}*\frac{1}{2}*\frac{\pi}{2}
$$

$$
\int_0^1x^3\sqrt{1-x^2}dx=\int_0^\frac{\pi}{2}\sin^3t*\cos^2tdt=\int_0^\frac{\pi}{2}\sin^3t*(1-\sin^2t)dt=I_3-I_5
$$

$$
I=\int_{-\frac{\pi}{2}}^{\frac{\pi}{2}}\frac{\sin^4x}{1+e^{-x}}dx=\int_{0}^{\frac{\pi}{2}}(\frac{\sin^4x}{1+e^{-x}}+\frac{\sin^4x}{1+e^{x}})dx=\int_{0}^{\frac{\pi}{2}}\sin^4x(\frac{e^x}{1+e^{x}}+\frac{1}{1+e^{x}})dx=\int_{0}^{\frac{\pi}{2}}\sin^4xdx=I_4=\frac{3}{4}*\frac{1}{2}*I_0=\frac{3\pi}{16}
$$
