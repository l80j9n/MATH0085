java c
Asset Pricing in Continuous Time 
MSc Examination 
2021
Problem 1. Let    (Ω   ,   F, {Ft   }t≥0,   P)   be   some   probability   space   and   {Wt   }t≥0      and {W(ˆ)t   }t≥0    be   two   (P, {Ft   }t≥0)-Brownian   motions, where   EP   [(Wt      −   Ws   )(W(ˆ)t    −   W(ˆ)s   )]   = ρ(t   − s)   for   some   ρ   ∈   (0,   1).
(a)    [8   points]    [SS]      Let   {Yt   }t≥0    and   {Zt   }t≥0    be   Ito   processes   governed   by

If      St         =    sin(t)   +   Yt2      +   exp(Zt   )    for      all      t      ≥    0,      governed      by      the      stochastic diﬀerential   equation    dSt         =   Kt   dt + Lt   dWt    + Nt   dW(ˆ)t   ,   what   are   Kt   ,   Lt       and Nt      in   terms   of   Yt   ,   Zt   ,   at   ,   bt   ,   ct      and   dt      for   all   t   ≥ 0?
(b)      [8   points]   [S]From above, if Xt    = YtZt      for   all   t   ≥ 0   such   that    dXt      = µt   dt   +   σt   dMt   ,   where   {Mt   }t≥0    is   a    (P, {Ft   }t≥0)-Brownian   motion,   what   are   µt      and   σt    in   terms   of   Yt   ,   Zt   ,   at   ,   bt   ,   ct      and   dt      for   all   t   ≥   0?
(c)      [9   points]   [SS]
Deﬁne   {Pt   }0≤t<τ by Pt = sin(Wt )/ cos(Wt ), where τ =   inf{t ≥ 0      :      |Wt   |      = 2/1π}. Show that the following holds: 

Problem 2. 
(a)      [8   points]   [SS]
Let (Ω   ,   F, {Ft   }t≥0,   P) be some probability space and {Wt   }t≥0   be a (P, {Ft   }t≥0)-   Brownian   motion.   For   a   ﬁnite   Q   > 0,   let   {Ft   }t≥0   ,   {Gt   }t≥0    and   {Ht   }t≥0    be

for   all t   ≥ 0, respectively.    For each   above, prove   whether   it   is   a   (P, {Ft   }t≥0)-   martingale   or   not.
(b)      [8   points]   [S]Let      {Bt   }t≥0         given   by   Bt         =   ert         model   the   money-market   account   for   some   ﬁnite   r   ≥ 0   and   let   {Zt   }t≥0    be   governed   by    dZt    =   −λtZt   dWt    where   {λt   }t≥0   is   the   market   price   of   risk.      What   is   the   stochastic   diﬀerential   equation   of   {πt   }t≥0         given   by   πt       =      Zt   /Bt?         Also,      prove   that      {πt   }t≥0         is      a      (P, {Ft   }t≥0)-   supermartingale.
(c)      [9   points]   [U]
Let Q   ≠   0 be some ﬁnite constantan   {Et   }0≤t<τ be governed by the following:
Provide   an   explicit   solution   to   the   stochastic   integral   above   –   that   is,   what   is   the   function   f      if   the   solution   is   Et       =   f   (t,   Wt   ).    Based   on   this   solution,   what   s代 写MATH0085 Asset Pricing in Continuous Time MSc Examination 2021Java
代做程序编程语言hould   be   the   deﬁnition   of τ   in   terms   of   Wt    and   Q?Problem 3. Let   (Ω   ,   F, {Ft   }t≥0,   P)   be   some   probability   space   and   {Wt   }t≥0    be   a   (P, {Ft   }t≥0)-Brownian   motion.    Let   {Bt   }t≥0    governed   by    dBt      =   rBt   dt   model   the   money-market   account, where   B0    =   1   and r   > 0   is ﬁnite.    Let   {Xt   }t≥0      model   asset   price   dynamics   where    dXt       =   μXt   dt + σXt   dWt for   some   ﬁnite   constants   μ    ∈   R   and   σ   > 0   with   X0      =   x.
(a)      [8   points]   [S]
Prove   that   {Zt   }t≥0    deﬁned   by

is   a   (P, {Ft   }t≥0)-martingale   if λ = (μ −   r)/σ   .   (b)      [8   points]   [SS]
Deﬁne   the   risk-neutral   probability   measure   Q   as   follows:

For      some Q > 0 and K ≥ 0, derive the following option price: V0    = e-rTEQ [(XT(α)   − K)+].    (Hint:   These   are   called   power   options)
(c)      [9   points]   [SS]
Now   deﬁne   the   probability   measure   U   as   follows:

Show   that   for   any   0   ≤ s   ≤ t   ≤ T   ,   the   following   holds:
Problem 4. Let   (Ω   ,   F, {Ft   }t≥0,   Q)   be   a   probability   space   where   Q   is   the   risk-   neutral   probability   measure   and   {Wt   }t≥0 is   a   (Q, {Ft   }t≥0)-Brownian   motion. For   interest   rate   r   >   0   and   volatility   σ   >   0   (both   ﬁnite),   let   {Xt   }t≥0    be   governed   by   dXt    = rXt   dt + σXt   dWt.
(a)    [9    points]    [U]          If g(x) is a non-negative convex function for      x      ≥    0    with g(0)    =    0, prove that      {St   }t≥0    given      by      St         =    e-rtg(Xt   )    is      a      (Q, {Ft   }t≥0)-   submartingale.      (Hint:   Since   g   is   convex, g ((1 − Q)x1      + Qx2   )   ≤ (1−Q)g(x1   )+   Qg(x2   )   for   0   ≤ Q   ≤ 1   and   0   ≤ x1      ≤ x2   .    Set   x1    =   0   and   x2      =   x)
(b)      [8   points]   [S]
Deﬁne   the   stochastic   integral   process   {Mt   }t≥0    as   follows:

Compute   the   expected   value   EQ [Mt   ]   and   the   variance   VarQ [Mt   ].
(c)      [8   points]   [SS]
Let   {W(ˆ)t   }t≥0    be another   (Q,   {Ft   }t≥0)-Brownian motion which is   independent of   {Wt   }t≥0   .    Deﬁne   Yt         =   QWt/α2          for   some   Q   >   0   and   Y(ˆ)t    =   tW(ˆ)1/t      for   t   ≥   0, with   Y0      =   Y(ˆ)0      =   0.    If   Rt      =   Yt   /Y(ˆ)t whenever   Y(ˆ)t  0,   what   is   the   distribution Q(R1      ∈   dr)?







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
