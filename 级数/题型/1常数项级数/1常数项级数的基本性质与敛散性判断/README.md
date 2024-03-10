$$
\begin{align}
&设\{u_n\}为常数列,下列结论正确的是(A)\\
&(A)若\sum_{n=1}^\infin u_n收敛,则\sum_{n=1}^\infin(u_{2n-1}+u_{2n})收敛\\
&(B)若\sum_{n=1}^\infin(u_{2n-1}+u_{2n})收敛,则\sum_{n=1}^\infin u_n收敛\\
&(C)若\sum_{n=1}^\infin u_n收敛,则\sum_{n=1}^\infin(u_{2n-1}-u_{2n})收敛\\
&(D)若\sum_{n=1}^\infin(u_{2n-1}-u_{2n})收敛,则\sum_{n=1}^\infin u_n收敛
\end{align}
$$

$$
级数加括号增加收敛性
$$

---

$$
\begin{align}
&设\sum_{n=1}^\infin u_n收敛,下列级数一定收敛的是(D)\\
&(A)\sum_{n=1}^\infin u_n^2\\
&(B)\sum_{n=1}^\infin (-1)^nu_n\\
&(C)\sum_{n=1}^\infin(u_{2n-1}-u_{2n})\\
&(D)\sum_{n=1}^\infin(u_n+u_{n+1})
\end{align}
$$

$$
\sum_{n=1}^\infin(u_n+u_{n+1})=2\sum_{n=1}^\infin u_n-a_1+a_{n+1}
$$

---

$$
\begin{align}
&若级数\sum_{n=1}^\infin u_n,\sum_{n=1}^\infin v_n发散,则(D)\\
&(A)\sum_{n=1}^\infin(u_n-v_n)发散\\
&(B)\sum_{n=1}^\infin(u_nv_n)发散\\
&(C)\sum_{n=1}^\infin(u_n+|v_n|)发散\\
&(D)\sum_{n=1}^\infin(|u_n|+|v_n|)发散\\
\end{align}
$$

$$
级数加绝对值增加发散性
$$

---

$$
\begin{align}
&设u_n\neq0,且\lim_{n\rightarrow\infin}\frac{u_n}{n}=1,则级数\sum_{n=1}^\infin(-1)^n(\frac{1}{u_n}+\frac{1}{u_{n+1}})(B)\\
&(A)发散\\
&(B)条件收敛\\
&(C)绝对收敛\\
&(D)敛散性不确定
\end{align}
$$

---

判断下列级数的敛散性：
$$
\sum_{n=1}^\infin\frac{n}{\sqrt{n^3+n+1}}\\
\frac{n}{\sqrt{n^3+n+1}}\sim n^{-\frac{1}{2}},发散
$$

$$
\sum_{n=1}^\infin\frac{1}{\int_0^n\sqrt[4]{1+x^4}dx}\\
0\leq\sum_{n=1}^\infin\frac{1}{\int_0^n\sqrt[4]{1+x^4}dx}\leq\frac{2}{n^2},收敛
$$

---

$$
判断级数\sum_{n=2}^\infin(-1)^n(n^{\frac{1}{n}}-1)绝对收敛还是条件收敛.
$$

$$
\because\frac{1}{n}>1~\therefore\sum_{n=2}^\infin(-1)^n(n^{\frac{1}{n}}-1)为交错级数\\
|(-1)^n(n^{\frac{1}{n}}-1)|=n^{\frac{1}{n}}-1\\
(n^{\frac{1}{n}}-1)'=(e^{\frac{1}{n}\ln n})'=n^{\frac{1}{n}}\frac{1-\ln n}{n^2}\\
n>e时,n^{\frac{1}{n}}-1单调递减\\
又\lim_{n\rightarrow\infin}n^{\frac{1}{n}}-1=0,\sum_{n=2}^\infin(-1)^n(n^{\frac{1}{n}}-1)收敛\\
\lim_{n\rightarrow\infin}\frac{n^{\frac{1}{n}}-1}{\frac{1}{n}}=\lim_{n\rightarrow\infin}\frac{n^{\frac{1}{n}}\frac{1-\ln n}{n^2}}{-\frac{1}{n^2}}=+\infin,故\sum_{n=2}^\infin(n^{\frac{1}{n}}-1)发散\\
综上,\sum_{n=2}^\infin(-1)^n(n^{\frac{1}{n}}-1)条件收敛
$$

---

$$
判断级数\sum_{n=1}^\infin[\frac{\sin an}{n^2}+\frac{(-1)^n}{\sqrt{n}}]的敛散性.
$$

$$
0\leq|\frac{\sin an}{n^2}|\leq\frac{1}{n^2},\sum_{n=1}^\infin\frac{\sin an}{n^2}绝对收敛\\
\sum_{n=1}^\infin\frac{1}{\sqrt{n}}发散,\frac{1}{\sqrt{n}}单调递减,\lim_{n\rightarrow\infin}\frac{1}{\sqrt{n}}=0,\sum_{n=1}^\infin\frac{(-1)^n}{\sqrt{n}}收敛\\
\sum_{n=1}^\infin[\frac{\sin an}{n^2}+\frac{(-1)^n}{\sqrt{n}}]条件收敛
$$

---

$$
判断级数\sum_{n=1}^\infin\int_{n\pi}^{(n+1)\pi}\frac{\sin x}{\sqrt{x}}dx的敛散性.
$$

$$
设u_n=\sum_{n=1}^\infin\int_{n\pi}^{(n+1)\pi}\frac{\sin x}{\sqrt{x}}dx,当n为偶数时,u_n>0;当n为奇数时，u_n<0.\\
故\sum_{n=1}^\infin\int_{n\pi}^{(n+1)\pi}\frac{\sin x}{\sqrt{x}}dx为交错级数.\\
0\leq|u_n|\leq\int_{n\pi}^{(n+1)\pi}\frac{dx}{\sqrt{x}}=2[\sqrt{(n+1)\pi}-\sqrt{n\pi}]\rightarrow0(n\rightarrow\infin)\\
|u_n|=\int_{n\pi}^{(n+1)\pi}\frac{|\sin x|}{\sqrt{x}}dx>\int_{n\pi}^{(n+1)\pi}\frac{\sin x}{\sqrt{x+\pi}}dx=\int_{(n+2)\pi}^{(n+2)\pi}\frac{|\sin t|}{\sqrt{t}}dt=|u_{n+1}|\\
综上,原级数收敛.
$$

