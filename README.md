# 高等数学经典题收藏

## Section1.极限计算

【1】计算
$$
\lim_{n\rightarrow \infty} \frac{1}{n}\sum_{k=1}^n{\sqrt{1+\frac{k}{n}}}
$$

【2】计算
$$
\lim_{n\rightarrow \infty} \frac{1^p+2^p+\cdots +n^p}{n^{p+1}}
$$

【3】计算
$$
\lim_{n\rightarrow \infty} \frac{1}{n}\sum_{k=1}^n{\frac{1}{3^k}\left( 1+\frac{1}{k} \right) ^{k^2}}
$$

【4】计算
$$
\lim_{x\rightarrow 0} \frac{1-\cos x\sqrt{\cos 2x}\cdots \sqrt[n]{\cos nx}}{x^2}
$$

【5】计算
$$
\lim_{x\rightarrow 0} \frac{\tan\tan x-\sin\sin x}{\tan x-\sin x}
$$

【6】计算
$$
\lim_{x\rightarrow 0} \frac{\ln \left( e^{\sin x}+\sqrt[3]{1-\cos x} \right) -\sin x}{\text{arc}\tan \left( 4\sqrt[3]{1-\cos x} \right)}
$$

【7】计算
$$
\lim_{x\rightarrow +\infty} \frac{\int_1^x{\left[ t^2\left( e^{\frac{1}{t}}-1 \right) -t \right] dt}}{x^2\ln \left( 1+\frac{1}{x} \right)}
$$

【8】计算
$$
\lim_{x\rightarrow 0} \frac{\cos x-\cos 3x}{x^2}
$$

【9】计算
$$
\lim_{n\rightarrow \infty} \sin \left( n\sqrt{4n^2+1}\pi \right)
$$

【10】计算
$$
\lim_{n\rightarrow \infty} n\sin \sqrt{4n^2+1}\pi
$$

【11】计算
$$
\lim_{x\rightarrow 0} \frac{\sqrt{1+x}-\sqrt{1-x}}{\sqrt[3]{1+x}-\sqrt[3]{1-x}}
$$

【12】设$f\left( x \right)$在$x=0$的某邻域内可导，且在$x=0$处存在二阶导数，又设$f\left( 0 \right) =f'\left( 0 \right) =0$，$f''\left( 0 \right) \ne 0$，求极限
$$
I=\lim_{x\rightarrow 0} \frac{\int_0^x{\left( x-t \right) f\left( t \right) dt}}{x\int_0^x{f\left( x-t \right) dt}}
$$

【13】已知$f\left( x \right)$在$x=0$处连续，计算
$$
\lim_{x\rightarrow 0} \frac{\int_0^x{\left( x-t \right) f\left( t \right) dt}}{x\int_0^x{f\left( x-t \right) dt}}
$$

【14】计算
$$
\lim_{x\rightarrow 1} \frac{\left( 1-\sqrt[3]{x} \right) \left( 1-\sqrt[4]{x} \right) \cdots \left( 1-\sqrt[n]{x} \right)}{\left( 1-x \right) ^{n-2}}
$$

【15】计算
$$
\lim_{n\rightarrow \infty} \left( n! \right) ^{\frac{1}{n^2}}
$$

## Section2.递推式极限

【1】设$a_1=1$，$a_{n+1}=a_n+\frac{1}{a_n}\left( n\in N_+ \right)$，证明
$$
\lim_{n\rightarrow \infty} \frac{a_n}{\sqrt{n}}=\sqrt{2}
$$

【2】设数列$\left\{ x_n \right\}$满足$x_1=2$，$x_{n+1}=2+\frac{1}{x_n}$，$n\in N_+$，证明数列$\left\{ x_n \right\}$收敛，并求其极限值。

【3】设数列$\left\{ x_n \right\}$满足$0<x_1<3$，$x_{n+1}=\sqrt{x_n\left( 3-x_n \right)}$，$n\in N_+$，证明数列$\left\{ x_n \right\}$极限存在并求其极限值。

【4】证明数列$\sqrt{2},\sqrt{2+\sqrt{2}},\sqrt{2+\sqrt{2+\sqrt{2}}},\cdots$极限存在，并求其极限值。

## Section3.积分计算

【1】计算
$$
\int_0^1{\frac{\ln \left( 1+x \right)}{1+x^2}dx}
$$

【2】计算
$$
\int{\frac{dx}{\left( 1-x \right) ^2\sqrt{1-x^2}}}
$$

【3】计算
$$
\int{\frac{\sin 10x}{\sin x}dx}
$$

【4】计算
$$
\int{\frac{dx}{1+x^4}}
$$

【5】计算
$$
\int{\frac{dx}{\left( 1+x^4 \right) ^2}}
$$

【6】计算
$$
\int_0^{+\infty}{\frac{\ln x}{1+x^2}dx}x
$$

【7】计算
$$
\int_0^{\frac{\pi}{2}}{\frac{dx}{a^2\sin ^2x+b^2\cos ^2x}}
$$

【8】计算
$$
\int_0^{\frac{\pi}{2}}{\frac{xdx}{\left( 1+\sin x+\cos x \right) ^2}}
$$

## Section4.中值等式的证明

## Section5.微分不等式的证明

【1】设$f\left( x \right)$在$\left[ 0,+\infty \right)$上连续，在$\left( 0,+\infty \right)$内二阶可导，且$f''\left( x \right) <0$，并设$f\left( 0 \right) =0$，试证明对$\forall x_1>0,x_2>0$，恒有
$$
f\left( x_1+x_2 \right) <f\left( x_1 \right) +f\left( x_2 \right)
$$

【2】设$f\left( x \right)$在区间$\left( -\infty ,+\infty \right)$内二阶可导，且$f''\left( x \right) >0,\lim\limits_{x\rightarrow 0} \frac{f\left( x \right)}{x}=1$，试证明恒有$f\left( x \right) \geqslant x$且等号仅在$x=0$时成立。

【3】证明当$x>0,y>0$时，
$$
x\ln x+y\ln y\geqslant \left( x+y \right) \ln \frac{x+y}{2}
$$

## Section6.积分不等式的证明

【1】设$f\left( x \right)$在$\left[ a,b \right]$上具有二阶可导，且$f\left( a \right) =f\left( b \right) =0$，$M=\mathop {\max} \limits_{x\in \left[ a,b \right]}\left| f''\left( x \right) \right|$，证明
$$
\left| \int_a^b{f\left( x \right) dx} \right|\leqslant \frac{\left( b-a \right) ^3}{12}M
$$

【2】已知$f\left( x \right)$在$\left[ 0,2 \right]$上一阶可导，$f\left( 0 \right) =f\left( 2 \right) =1$，$\left| f'\left( x \right) \right|\leqslant 1$，证明
$$
1\leqslant \int_0^2{f\left( x \right) dx}\leqslant 3
$$
【3】函数$f\left( x \right)$在$\left[ 0,1 \right]$上二阶可导，$f\left( 0 \right) =f\left( 1 \right) =0$，$f\left( x \right) \ne 0\left( x\in \left( 0,1 \right) \right)$，证明
$$
\int_0^1{\left| \frac{f''\left( x \right)}{f\left( x \right)} \right|dx}\geqslant 4
$$

【4】函数$f\left( x \right)$在$\left[ 0,1 \right]$上一阶可导，$f\left( 0 \right) =f\left( 1 \right) =0$，证明
$$
\int_0^1{f^2\left( x \right) dx}\leqslant \frac{1}{4}\int_0^1{f'^2\left( x \right) dx}
$$

【5】证明
$$
0\leqslant \int_0^{\frac{\pi}{2}}{\sqrt{x}\cos xdx}\leqslant \sqrt{\frac{\pi ^3}{32}}
$$

【6】设$f\left( x \right)$在$\left[ a,b \right]$上连续且单调增加，证明
$$
\int_a^b{xf\left( x \right) dx}\geqslant \frac{a+b}{2}\int_a^b{f\left( x \right) dx}
$$

【7】设$f\left( x \right) \in \left[ 0,1 \right]$，$f\left( 0 \right) =0$，$0\leqslant f'\left( x \right) \leqslant 1$，证明
$$
\left( \int_0^1{f\left( x \right) dx} \right) ^2\geqslant \int_0^1{f^3\left( x \right) dx}
$$

【8】证明
$$
2\leqslant \int_{-1}^1{\sqrt{1+x^4}dx}\leqslant 2\sqrt{2}
$$

【9】证明
$$
\frac{1}{2}\leqslant \int_0^{\frac{1}{2}}{\frac{1}{\sqrt{1-x^n}}dx}\leqslant \frac{\pi}{6},\left( n>2 \right)
$$

【10】证明
$$
\frac{61}{330}\leqslant \int_0^1{x\sin x^3dx}\leqslant \frac{1}{5}
$$

【11】已知$f\left( x \right)$在$\left[ 0,1 \right]$上一阶可导，证明
$$
\left| f\left( x \right) \right|\leqslant \int_0^1{\left[ \left| f\left( x \right) \right|+\left| f'\left( x \right) \right| \right] dx}
$$

【12】证明
$$
\frac{2\pi}{9}\leqslant \int_{\frac{1}{\sqrt{3}}}^{\sqrt{3}}{x\text{arc}\tan xdx}\leqslant \frac{4\pi}{9}
$$

【13】设$\left( x \right)$在闭区间$\left[ 0,1 \right]$上连续，函数$f\left( x \right) \left( f\left( x \right) >0 \right)$单调减少，证明
$$
\frac{\int_0^1{xf^2\left( x \right) dx}}{\int_0^1{xf\left( x \right) dx}}\leqslant \frac{\int_0^1{f^2\left( x \right) dx}}{\int_0^1{f\left( x \right) dx}}
$$

【14】已知$f\left( x \right)$在闭区间$\left[ a,b \right]$上连续，$f\left( x \right) >0$，证明
$$
\int_a^b{f\left( x \right) dx}\cdot \int_a^b{\frac{1}{f\left( x \right)}dx}\geqslant \left( b-a \right) ^2
$$

【15】设$a>0$，$b>0$，$f\left( x \right) \geqslant 0$在$\left[ -a,b \right]$上连续，$\int_{-a}^b{xf\left( x \right) dx}=0$，证明
$$
\int_{-a}^b{x^2f\left( x \right) dx}\leqslant ab\int_{-a}^b{f\left( x \right) dx}
$$

【16】已知$f\left( x \right)$在$\left[ 0,1 \right]$上连续，$0<m\leqslant f\left( x \right) \leqslant M$，证明
$$
\int_0^1{f\left( x \right) dx}\cdot \int_0^1{\frac{1}{f\left( x \right)}dx}\leqslant \frac{\left( M+m \right) ^2}{4Mm}
$$
