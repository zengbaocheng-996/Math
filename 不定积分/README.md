$$
\begin{align}
&\int(x+1)e^{x^2+2x+3}dx\\
=&\int(x+1)e^{(x+1)^2+2}dx\\
=&\frac{1}{2}e^2 \int e^{(x+1)^2} d(x+1)^2\\
=&\frac{1}{2}e^2 e^{(x+1)^2}+C
\end{align}
$$

$$
\begin{align}
&\int \frac{x}{2x+1}dx\\
=&\frac{1}{2} \int \frac{2x+1-1}{2x+1}dx\\
=&\frac{1}{2} \int 1-\frac{1}{2x+1}dx\\
=&\frac{1}{2}(\int 1dx-\int\frac{1}{2x+1}dx)\\
=&\frac{1}{2}(x-\frac{1}{2}\ln |2x+1|)+C
\end{align}
$$

$$
\begin{align}
&\int \frac{dx}{x(x^3+2)}\\
=&\int\frac{x^2}{x^3(x^3+2)}dx\\
=&\frac{1}{3}\int\frac{1}{x^3(x^3+2)}dx^3\\
=&\frac{1}{6}\int\frac{1}{x^3}-\frac{1}{x^3+2}dx^3\\
=&\frac{1}{6}(\int\frac{1}{x^3}dx^3-\int\frac{1}{x^3+2}dx^3)\\
=&\frac{1}{6}(\ln|x^3|-\ln|x^3+2|)+C
\end{align}
$$

$$
\begin{align}
&\int \frac{\tan ^2 \sqrt{x}}{\sqrt{x}}dx\\
=&2\int\frac{\tan^2\sqrt{x}}{2\sqrt{x}}dx\\
=&2\int \tan^2\sqrt{x}d\sqrt{x}\\
=&2\int\frac{\sin^2\sqrt{x}}{\cos^2\sqrt{x}}d\sqrt{x}\\
=&2\int\frac{1-\cos^2\sqrt{x}}{\cos^2\sqrt{x}}d\sqrt{x}\\
=&2(\int\frac{1}{\cos^2\sqrt{x}}d\sqrt{x}-\int 1d\sqrt{x})\\
=&2(\tan\sqrt{x}-\sqrt{x})+C
\end{align}
$$

$$
\begin{align}
&\int \frac{dx}{\sqrt{x(1-x)}}\\
=&2\int\frac{dx}{2\sqrt{x}\sqrt{1-x}}\\
=&2\int\frac{1}{\sqrt{1-x}}d\sqrt{x}\\
=&2\int\frac{1}{\sqrt{1-(\sqrt{x})^2}}d\sqrt{x}\\
=&2\arcsin\sqrt{x}+C
\end{align}
$$

$$
\begin{align}
&\int \frac{e^x}{e^{2x}+e^x+1}dx\\
=&\int\frac{1}{(e^x+\frac{1}{2})^2+\frac{3}{4}}d(e^x+\frac{1}{2})\\
=&\frac{4}{3}\int\frac{1}{\frac{4}{3}(e^x+\frac{1}{2})^2+1}d(e^x+\frac{1}{2})\\
=&\frac{4}{3}\int\frac{1}{[\frac{2}{\sqrt{3}}(e^x+\frac{1}{2})]^2+1}d(e^x+\frac{1}{2})\\
=&\frac{4}{3}\frac{\sqrt{3}}{2}\int\frac{1}{[\frac{2}{\sqrt{3}}(e^x+\frac{1}{2})]^2+1}d\frac{2}{\sqrt{3}}(e^x+\frac{1}{2})\\
=&\frac{2\sqrt{3}}{3}\arctan{[\frac{2}{\sqrt{3}}(e^x+\frac{1}{2})]}+C
\end{align}
$$

$$
\begin{align}
&\int\frac{dx}{x(\ln x+1)^2}\\
=&\int\frac{1}{(\ln x +1)^2}d(\ln x +1)\\
=&-\frac{1}{\ln x+1}+C
\end{align}
$$

$$
\begin{align}
&\int e^\sqrt{x}dx\\
=&\int e^t dt^2\\
=&\int 2te^tdt\\
=&2\int tde^t\\
=&2(te^t-\int e^tdt)\\
=&2e^t(t-1)+C\\
=&2e^{\sqrt{x}}(\sqrt{x}-1)+C
\end{align}
$$

$$
\begin{align}
&\int x\arctan x dx\\
=&\frac{1}{2}\int \arctan x dx^2\\
=&\frac{1}{2}(x^2\arctan x - \int x^2 d\arctan x)\\
=&\frac{1}{2}(x^2\arctan x - \int \frac{x^2}{1+x^2} dx)\\
=&\frac{1}{2}(x^2\arctan x - \int 1 dx+\int \frac{1}{1+x^2} dx)\\
=&\frac{1}{2}(x^2\arctan x -x +\arctan x)+C
\end{align}
$$

$$
\begin{align}
&\int x\ln^2xdx\\
=&\frac{1}{2}\int\ln^2xdx^2\\
=&\frac{1}{2}(x^2\ln^2x-\int x^2d\ln^2x)\\
=&\frac{1}{2}(x^2\ln^2x-\int 2x\ln xdx)\\
=&\frac{1}{2}[x^2\ln^2x-(x^2\ln x-\frac{1}{2}x^2)]+C
\end{align}
$$

$$
\begin{align}
&\int\frac{\sin 2x}{4+\sin^4 x}dx\\
=&\int\frac{1}{4+\sin^4{x}}d\sin^2x\\
=&\frac{2}{4}\int\frac{1}{1+(\frac{1}{2}\sin^2x)^2}d\frac{1}{2}\sin^2x\\
=&\frac{1}{2}\arctan{(\frac{1}{2}\sin^2x)}+C
\end{align}
$$

$$
\int \max{\{1,x\}}dx\\
\begin{cases}
x+C,x\leq1\\
\frac{1}{2}x^2+C,x>1\\
\end{cases}
$$

