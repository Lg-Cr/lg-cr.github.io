+++
date = '2026-04-28T23:12:23+08:00'
draft = false
title = 'Square Resistance Value'
tags = ['Solutions', 'Maths', 'Continued Fraction Theory', 'Construction']
+++

很清奇的构造题，以前似乎从来没见过逼近这一块的构造，而且这还是逼近无理数，我说实话开始有点懵。

这个题你如果事先知道连分数理论的话应该是相当简单的。

首先串联是电阻相加，并联是电阻的倒数相加再倒数。

然后一个很厉害的放缩就是你考虑每次在原电路上串联或者并联一个电阻。然后这个时候你发现他会让分子加上分母或者分母加上分子。

这就是 Stern-Brocot 树啊，然后你发现把整个连分数理论套上去基本上就做完了，你直接在 Stern-Brocot 树上二分，然后很容易通过连分数理论证明精度是足够的。

这个题其实就是科技题吧，学会科技就好做了。

[Continued Fraction Theory](/posts/Continued-Fraction-Theory)