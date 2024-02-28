# 1

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
\frac{1}{2}x^2+C_1,x>1\\
\end{cases}\\
1+C=\frac{1}{2}+C_1\\
C1=C+\frac{1}{2}\\
\begin{cases}
x+C,x\leq1\\
\frac{1}{2}x^2+\frac{1}{2}+C,x>1\\
\end{cases}\\
$$

# 2

$$
\begin{align}
&\int\frac{x+1}{x^2+4}dx\\
=&\int\frac{x}{x^2+4}dx+\int\frac{1}{x^2+4}dx\\
=&\frac{1}{2}\int\frac{1}{x^2+4}d(x^2+4)+\frac{2}{4}\int\frac{1}{(\frac{1}{2}x)^2+1}d(\frac{1}{2}x)\\
=&\frac{1}{2}\ln(x^2+4)+\frac{1}{2}\arctan(\frac{1}{2}x)+C
\end{align}
$$

$$
\begin{align}
&\int\frac{x+1}{(3x+1)^2}dx\\
=&\frac{1}{3}\int\frac{3x+3}{(3x+1)^2}dx\\
=&\frac{1}{3}(\int\frac{3x+1}{(3x+1)^2}dx+\int\frac{2}{(3x+1)^2}dx)\\
=&\frac{1}{3}(\frac{1}{6}\int\frac{1}{(3x+1)^2}d(3x+1)^2-\frac{2}{3}\frac{1}{3x+1})\\
=&\frac{1}{3}[\frac{1}{6}\ln(3x+1)^2-\frac{2}{3}\frac{1}{3x+1}]+C\\
\end{align}
$$

$$
\begin{align}
&\int\frac{x+2}{x^2+2x+3}dx\\
=&\int\frac{x+1+1}{(x+1)^2+2}dx\\
=&\int\frac{x+1}{(x+1)^2+2}dx+\int\frac{1}{(x+1)^2+2}dx\\
=&\frac{1}{2}\int\frac{1}{(x+1)^2+2}d[(x+1)^2+2]+\frac{\sqrt{2}}{2}\int\frac{1}{(\frac{x+1}{\sqrt{2}})^2+1}d\frac{x+1}{\sqrt{2}}\\
=&\frac{1}{2}\ln[(x+1)^2+2]+\frac{\sqrt{2}}{2}\arctan\frac{x+1}{\sqrt{2}}+C
\end{align}
$$

$$
\begin{align}
2x^2-&x-1=(x-1)(2x+1)\\
\frac{A}{x-1}+\frac{B}{2x+1}&=\frac{5x+1}{2x^2-x-1}=\frac{2}{x-1}+\frac{1}{2x+1}\\
&\int\frac{5x+1}{2x^2-x-1}dx\\
=&2\int\frac{1}{x-1}d(x-1)+\frac{1}{2}\int\frac{1}{2x+1}d(2x+1)\\
=&2\ln|x-1|+\frac{1}{2}\ln|2x+1|+C
\end{align}
$$

$$
\begin{align}
&\int\frac{\arctan\sqrt{x}}{\sqrt{x}(1+x)}dx\\
=&2\int\frac{\arctan\sqrt{x}}{2\sqrt{x}(1+x)}dx\\
=&2\int\frac{\arctan\sqrt{x}}{1+(\sqrt{x})^2}d\sqrt{x}\\
=&2\int\arctan\sqrt{x}d\arctan{\sqrt{x}}\\
=&\arctan^2{\sqrt{x}}+C
\end{align}
$$

$$
\begin{align}
&\int\frac{\arcsin\sqrt{x}}{\sqrt{x(1-x)}}dx\\
=&2\int\frac{\arcsin\sqrt{x}}{2\sqrt{x}\sqrt{1-x}}dx\\
=&2\int\frac{\arcsin\sqrt{x}}{\sqrt{1-(\sqrt{x})^2}}d\sqrt{x}\\
=&2\int\arcsin\sqrt{x}d\arcsin{\sqrt{x}}\\
=&\arcsin^2\sqrt{x}+C
\end{align}
$$

$$
\begin{align}
&\int\frac{\tan^4{\sqrt{x}}}{\sqrt{x}}dx\\
=&2\int\frac{\tan^4{\sqrt{x}}}{2\sqrt{x}}dx\\
=&2\int\tan^4{\sqrt{x}}d\sqrt{x}\\
=&2\int\frac{\sin^4\sqrt{x}}{\cos^4\sqrt{x}}d\sqrt{x}\\
=&2\int\frac{(1-\cos^2\sqrt{x})^2}{\cos^4\sqrt{x}}d\sqrt{x}\\
=&2\int\frac{1}{\cos^4\sqrt{x}}-\frac{2}{\cos^2\sqrt{x}}+1d\sqrt{x}\\
=&2(\sqrt{x}-2\tan\sqrt{x}+\int\frac{1}{\cos^4\sqrt{x}}d\sqrt{x})\\
=&2(\sqrt{x}-2\tan\sqrt{x}+\int\frac{1}{\cos^2\sqrt{x}}d\tan\sqrt{x})\\
=&2(\sqrt{x}-2\tan\sqrt{x}+\int\frac{\sin^2\sqrt{x}+\cos^2\sqrt{x}}{\cos^2\sqrt{x}}d\tan\sqrt{x})\\
=&2(\sqrt{x}-2\tan\sqrt{x}+\int\tan^2{\sqrt{x}+1}d\tan\sqrt{x})\\
=&2(\sqrt{x}-2\tan\sqrt{x}+\frac{1}{3}\tan^3{\sqrt{x}}+\tan\sqrt{x})+C\\
=&2\sqrt{x}-2\tan\sqrt{x}+\frac{2}{3}\tan^3\sqrt{x}+C
\end{align}
$$

$$
\begin{align}
&\int\frac{x-1}{\sqrt{2x+1}}dx\\
=&\frac{1}{2}\int\frac{2x-3+1}{\sqrt{2x+1}}dx\\
=&\frac{1}{2}(\int\sqrt{2x+1}dx-3\int\frac{1}{\sqrt{2x+1}}dx)\\
=&\frac{1}{2}(\frac{1}{2}\int\sqrt{2x+1}d(2x+1)-\frac{3}{2}\int(2x+1)^{-\frac{1}{2}}d(2x+1))\\
=&\frac{1}{2}[\frac{1}{3}(2x+1)^{\frac{3}{2}}-3(2x+1)^\frac{1}{2}]+C
\end{align}
$$

# 3

$$
\begin{align}
&\int\frac{dx}{1+\cos x}\\
=&\int\frac{dx}{1+2\cos^2\frac{x}{2}-1}\\
=&\int\frac{d\frac{1}{2}x}{\cos^2\frac{x}{2}}\\
=&\tan\frac{x}{2}+C
\end{align}
$$

$$
\begin{align}
&\int\frac{\cos^2xdx}{1+\cos x}\\
=&\int\frac{\cos^2x-1}{1+\cos x}dx+\int\frac{1}{1+\cos x}dx\\
=&\int \cos x-1 dx+\tan\frac{x}{2}\\
=&\sin x-x+\tan\frac{x}{2}+C
\end{align}
$$

$$
\begin{align}
&\int\frac{1+\cos x}{1+\sin x}dx\\
=&\int\frac{1}{1+\sin x}dx+\int\frac{\cos x}{1+\sin x}dx\\
=&\int\frac{dx}{1+\cos(x-\frac{\pi}{2})}+\ln(1+\sin x)\\
=&\int\frac{dx}{1+2\cos^2(\frac{x}{2}-\frac{\pi}{4})-1}+\ln(1+\sin x)\\
=&\int\frac{d(\frac{x}{2}-\frac{\pi}{4})}{\cos^2(\frac{x}{2}-\frac{\pi}{4})}+\ln(1+\sin x)\\
=&\tan(\frac{x}{2}-\frac{\pi}{4})+\ln(1+\sin x)+C
\end{align}
$$

$$
\begin{align}
&\int\frac{dx}{\sqrt{2}+\cos x-\sin x}\\
=&\frac{1}{\sqrt{2}}\int\frac{dx}{1+\frac{1}{\sqrt{2}}\cos x-\frac{1}{\sqrt{2}}\sin x}\\
=&\frac{1}{\sqrt{2}}\int\frac{dx}{1+\cos (x+\frac{\pi}{4})}\\
=&\frac{1}{\sqrt{2}}\int\frac{dx}{1+2\cos^2 (\frac{x}{2}+\frac{\pi}{8})-1}\\
=&\frac{1}{\sqrt{2}}\int\frac{d(\frac{x}{2}+\frac{\pi}{8})}{\cos^2 (\frac{x}{2}+\frac{\pi}{8})}\\
=&\frac{1}{\sqrt{2}}\tan(\frac{x}{2}+\frac{\pi}{8})+C
\end{align}
$$

$$
\begin{align}
&\int\frac{x^2}{\sqrt{1-x^2}}dx\\
=&\int\frac{x^2-1}{\sqrt{1-x^2}}dx+\int\frac{1}{\sqrt{1-x^2}}dx\\
=&-\int \sqrt{1-x^2}dx+\arcsin x\\
=&-(x\sqrt{1-x^2}-\int xd\sqrt{1-x^2})+\arcsin x\\
=&-x\sqrt{1-x^2}-\int\frac{x^2}{\sqrt{1-x^2}}dx+\arcsin x\\
&\int\frac{x^2}{\sqrt{1-x^2}}dx=\frac{-x\sqrt{1-x^2}+\arcsin x}{2}+C
\end{align}
$$

$$
\begin{align}
&\int\frac{x^3}{\sqrt{1-x^2}}dx\\
=&\frac{1}{2}\int\frac{x^2}{\sqrt{1-x^2}}dx^2\\
=&\frac{1}{2}(\int\frac{t-1}{\sqrt{1-t}}dt+\int\frac{1}{\sqrt{1-t}}dt)\\
=&\frac{1}{2}[\int\sqrt{1-t}d(1-t)-\int\frac{1}{\sqrt{1-t}}d(1-t)]\\
=&\frac{1}{2}[\frac{2}{3}(1-t)^{\frac{3}{2}}-2(1-t)^{\frac{1}{2}}]+C\\
=&\frac{1}{3}(1-x^2)^{\frac{3}{2}}-(1-x^2)^{\frac{1}{2}}+C
\end{align}
$$

$$
\begin{align}
&\int\frac{dx}{1+\sqrt{1-x^2}}\\
=&\int\frac{\cos tdt}{1+\cos t}\\
=& t-\int\frac{1}{1+\cos t}dt\\
=&t-\int\frac{1-\cos t}{1-\cos^2t}dt\\
=&t-\int\frac{1}{\sin^2t}dt+\int\frac{d\sin t}{\sin^2t}\\
=&t+\frac{1}{\tan t}-\frac{1}{\sin t}+C\\
=&\arcsin x+\frac{\sqrt{1-x^2}}{x}-\frac{1}{x}+C
\end{align}
$$

$$
\begin{align}
&\int\frac{dx}{x\sqrt{1+x^2}}\\
=&\int\frac{d\tan t}{\tan t\sqrt{1+\tan^2t}}\\
=&\int\frac{1}{\sin t}dt\\
=&\ln|\frac{1}{\sin t}-\frac{1}{\tan t}|+C\\
=&\ln|\frac{\sqrt{1-x^2}}{x}-\frac{1}{x}|+C
\end{align}
$$

$$
\begin{align}
&\int e^{3x}\cos x dx\\
=&\int e^{3x}d\sin x\\
=&e^{3x}\sin x-\int\sin xde^{3x}\\
=&e^{3x}\sin x+3\int e^{3x}d\cos x\\
=&e^{3x}\sin x+3(e^{3x}\cos x-\int\cos xde^{3x})\\
=&e^{3x}\sin x+3(e^{3x}\cos x-3\int e^{3x}d\sin x)\\
&\int e^{3x}\cos x dx=\frac{e^{3x}\sin x+3e^{3x}\cos x}{10}+C
\end{align}
$$

$$
\begin{align}
&\int\arcsin x\arccos x dx\\
=&
\end{align}
$$

