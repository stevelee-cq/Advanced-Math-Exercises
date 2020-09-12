# 高等数学经典题收藏(持续更新)

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

【16】计算
$$
\lim_{n\rightarrow \infty} \ln \sqrt[n]{\left( 1+\frac{1}{n} \right) ^k\left( 1+\frac{2}{n} \right) ^k\cdots \left( 1+\frac{n}{n} \right) ^k}
$$

【17】计算
$$
\lim_{n\rightarrow \infty} \frac{1}{n^4}\prod_{i=1}^{2n}{\left( n^2+i^2 \right) ^{\frac{1}{n}}}
$$

【18】计算
$$
\lim_{n\rightarrow \infty} \frac{1!+2!+\cdots +n!}{n!}
$$

【19】设函数$f\left( x \right)$在$\left( -1,1 \right)$内有二阶连续导数，且$f''\left( x \right) \ne 0$，证明

（1）对于$\left( -1,1 \right)$内任意$x\ne 0$，存在唯一的$\theta \left( x \right) \in \left( 0,1 \right)$，使
$$
f\left( x \right) =f\left( 0 \right) +xf'\left( \theta \left( x \right) x \right)
$$

（2）
$$
\lim_{x\rightarrow 0} \theta \left( x \right) =\frac{1}{2}
$$

【20】计算
$$
\lim_{n\rightarrow \infty} n\left( \frac{1}{n^2+\pi}+\frac{1}{n^2+2\pi}+\cdots +\frac{1}{n^2+n\pi} \right)
$$

【21】计算
$$
\lim_{x\rightarrow 0^+} x\left[ \frac{1}{x} \right]
$$

【22】计算
$$
\lim_{x\rightarrow 0} \frac{\sin x-\tan x}{\left( \sqrt[3]{1+x^2}-1 \right) \left( \sqrt{1+\sin x}-1 \right)}
$$

## Section2.递推式极限

【1】设$a_1=1$，$a_{n+1}=a_n+\frac{1}{a_n}\left( n\in N_+ \right)$，证明
$$
\lim_{n\rightarrow \infty} \frac{a_n}{\sqrt{n}}=\sqrt{2}
$$

【2】设数列$\left\{ x_n \right\}$满足$x_1=2$，$x_{n+1}=2+\frac{1}{x_n}$，$n\in N_+$，证明数列$\left\{ x_n \right\}$收敛，并求其极限值。

【3】设数列$\left\{ x_n \right\}$满足$0<x_1<3$，$x_{n+1}=\sqrt{x_n\left( 3-x_n \right)}$，$n\in N_+$，证明数列$\left\{ x_n \right\}$极限存在并求其极限值。

【4】证明数列$\sqrt{2},\sqrt{2+\sqrt{2}},\sqrt{2+\sqrt{2+\sqrt{2}}},\cdots$极限存在，并求其极限值。

【5】设$a_1>0$，$\left\{ a_n \right\}$满足$a_{n+1}=\ln \left( 1+a_n \right)$，$n\in N_+$。

（1）证明数列$\left\{ a_n \right\}$极限存在，并求其极限值；

（2）计算
$$
\lim_{n\rightarrow \infty} \frac{a_na_{n+1}}{a_n-a_{n+1}}
$$

【6】设数列$\left\{ x_n \right\}$满足$x_{n+1}=\cos x_n$，$n\in N_+$，$x_1=\cos x$，证明该数列极限存在且其极限值为$\cos x-x=0$的根。

【7】

（1）证明方程$\tan x=x$在$\left( n\pi ,n\pi +\frac{\pi}{2} \right)$内存在实根$\xi _n$，$n\in N_+$；

（2）计算极限
$$
\lim_{n\rightarrow \infty} \left( \xi_{n+1}-\xi _n \right)
$$

【8】

（1）证明方程$e^x+x^{2n+1}=0$在$\left( -1,0 \right)$有唯一实根$x_n$，且$n\in N_+$；

（2）证明数列$\left\{ x_n \right\}$极限存在并求其值$a$；

（3）计算
$$
\lim_{n\rightarrow \infty} n\left( x_n-a \right)
$$

【9】设数列$\left\{ x_n \right\}$满足$x_0=a$，$x_1=b,x_{n+1}=\frac{1}{2}\left( x_n+x_{n-1} \right)$，$n\in N_+$，证明数列$\left\{ x_n \right\}$极限存在并求其极限。

【10】

（1）证明方程$x^n+x^{n-1}+\cdots +x=1\left( n>1,n\in Z \right)$在区间$\left( \frac{1}{2},1 \right)$内有且仅有一个实根；

（2）记（1）中的实根为$x_n$，证明数列$\left\{ x_n \right\}$极限存在并求其极限。

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

【1】设函数$f\left( x \right)$在$\left[ a,b \right]$上连续，在$\left( a,b \right)$内可导，证明至少存在一点$\xi \in \left( a,b \right)$，使得
$$
\frac{f\left( \xi \right) -f\left( a \right)}{b-\xi}=f'\left( \xi \right)
$$

【2】设函数$f\left( x \right)$在$\left[ a,b \right]$上连续，在$\left( a,b \right)$内可导，且$f\left( a \right) =f\left( b \right) =1$，证明存在$\xi ,\eta \in \left( a,b \right)$，使得
$$
e^{\eta -\xi}\left[ f\left( \eta \right) +f'\left( \eta \right) \right] =1
$$

【3】设函数$f\left( x \right)$在$\left[ a,b \right]$上连续，在$\left( a,b \right)$内可导，$f'\left( x \right) \ne 0$，且$f\left( a \right) =0$，$f\left( b \right) =2$，证明在区间$\left( a,b \right)$内存在两个不同的点$\xi$、$\eta$使得
$$
f'\left( \eta \right) \left[ f\left( \xi \right) +\xi f'\left( \xi \right) \right] =f'\left( \xi \right) \left[ bf'\left( \eta \right) -1 \right]
$$

【4】设函数$f\left( x \right)$在$\left[ a,b \right]$上连续，在$\left( a,b \right)$内二阶可导，证明存在$\xi \in \left( a,b \right)$，使得
$$
f\left( b \right) -2f\left( \frac{a+b}{2} \right) +f\left( a \right) =\frac{\left( b-a \right) ^2}{4}f''\left( \xi \right)
$$

【5】设$f\left( x \right)$在$\left[ a,b \right]$上连续，$f\left( a \right) =f\left( b \right)$，证明在区间$\left[ a,b \right]$上存在$\xi$，使得
$$
f\left( \xi \right) =f\left( \xi +\frac{b-a}{2} \right)
$$

【6】设函数$f\left( x \right)$在$\left[ 0,1 \right]$上三阶可导，且$f\left( 0 \right) =-1$，$f\left( 1 \right) =0$，$f'\left( 0 \right) =0$，证明$\forall x\in \left( 0,1 \right)$，至少存在一点$\xi \in \left( 0,1 \right)$，使得
$$
f\left( x \right) =-1+x^2+\frac{x^2\left( x-1 \right)}{3!}f'''\left( \xi \right)
$$

【7】设函数$f\left( x \right)$在$\left[ 0,1 \right]$上三阶可导，且$f\left( 0 \right) =f\left( 1 \right) =0$，又$F\left( x \right) =x^3f\left( x \right)$，证明存在$\xi \in \left( 0,1 \right)$，使$F'''\left( \xi \right) =0$.

【8】设函数$f\left( x \right)$在$\left[ 0,3 \right]$上连续，在$\left( 0,3 \right)$内可导，且$f\left( 0 \right) +f\left( 1 \right) +f\left( 2 \right) =3$，$f\left( 3 \right) =1$，证明至少存在一点$\xi \in \left( 0,3 \right)$，使得$f'\left( \xi \right) =0$.

【9】设函数$f\left( x \right)$在$\left[ 0,1 \right]$上连续，$f\left( 0 \right) =f\left( 1 \right)$，证明对于任意自然数$n$，存在$\xi \in \left[ 0,1 \right)$，使得
$$
f\left( \xi +\frac{1}{n} \right) =f\left( \xi \right)
$$

【10】设函数$f\left( x \right)$在$\left[ a,b \right]$上可导，$\mu$为介于$f'\left( a \right)$与$f'\left( b \right)$之间的实数，则存在$\xi \in \left( a,b \right)$，使
$$
f'\left( \xi \right) =\mu
$$

【11】函数$f\left( x \right)$在$\left[ a,b \right]$上二阶连续可导，证明存在$\xi \in \left( a,b \right)$，使得
$$
\int_a^b{f\left( x \right) dx}=\frac{1}{2}\left[ f\left( a \right) +f\left( b \right) \right] \left( b-a \right) -\frac{1}{12}f''\left( \xi \right) \left( b-a \right) ^3
$$

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

【4】设函数$f\left( x \right)$二阶可导，满足$f\left( 0 \right) =1$，$f'\left( 0 \right) =0$，且对任意的$x\geqslant 0$，有$f''\left( x \right) -5f'\left( x \right) +6f\left( x \right) \geqslant 0$，证明对任意的$x\geqslant 0$，有
$$
f\left( x \right) \geqslant 3e^{2x}-2e^{3x}
$$

【5】设函数$f\left( x \right)$在$\left[ a,b \right]$上二阶可导，$f'\left( a \right) =f'\left( b \right) =0$，证明存在$\xi \in \left( a,b \right)$使得
$$
\left| f''\left( \xi \right) \right|\geqslant \frac{4}{\left( b-a \right) ^2}\left| f\left( b \right) -f\left( a \right) \right|
$$

【6】证明当$x>0$时，有
$$
\left( x^2-1 \right) \ln x\geqslant \left( x-1 \right) ^2
$$

【7】设$0<\left| x \right|\leqslant \frac{\pi}{2}$，证明
$$
\left( \frac{\sin x}{x} \right) ^3>\cos x
$$

【8】设函数$f\left( x \right)$在$\left[ a,b \right]$上二阶可导，$f\left( a \right) =f\left( b \right) =0$，证明
$$
\mathop {\max} \limits_{x\in \left[ a,b \right]}\left| f\left( x \right) \right|\leqslant \frac{1}{8}\left( b-a \right) ^2\cdot \mathop {\max} \limits_{x\in \left[ a,b \right]}\left| f''\left( x \right) \right|
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
