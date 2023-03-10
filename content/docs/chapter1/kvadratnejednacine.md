---
title: Kvadratne jednačine.
date: '2023-03-01T00:00:00Z'
type: book # Do not modify.
---

Jednačine oblika $$ax^2+bx+c=0,\ a,b,c\\in\\mathbb{R},\ a\\neq 0$$ nazivamo kvadratnim jednačinama po nepoznatoj $x$. U ovisnosti o vrijednosti _diskriminante_ $$D=b^2-4ac$$ rješenja jednačine mogu biti:

- realna i različita ($D>0$)
- relana i dvostruka ($D=0$)
- konjugirano-kompleksna ($D<0$)

Kvadratna jednačina uvijek ima dva rješenja, $x_1$ i $x_2$, koja možemo odrediti koristeći formulu: $$x_{1,2}=\\frac{-b\\pm \\sqrt{D}}{2a}.$$

**Zadatak 1.** Riješi kvadratne jednačine:

a. $5x^2-6x+1=0$.

b. $4x^2+4x+1=0$.

c. $x^2-2x+5=0$.
{{< figure library="true" src="clubs.png">}}

a. Pri rješavanju bilo koje jednačine, prva stvar koju moramo odrediti jeste domena. Kako je kvadratna funkcija definisana za sve $x\\in \\mathbb{R}$ to je $D_f=\\mathbb{R}$. Vidimo da je $a=5,\ b=-6$ i $c=1$. Kako je diskriminanta $$D=b^2-4ac=(-6)^2-4\cdot 5\cdot 1=36-20=16>0$$
to dana jednačina ima realna i različita rješenja. Dakle,
$$x_{1,2}=\\frac{-(-6)\\pm \\sqrt{16}}{2\cdot 5}=\\frac{6\pm 4}{10},$$
tj. $$x_1=\\frac{6+4}{10}=\\frac{10}{10}=1$$ i $$x_2=\\frac{6-4}{10}=\\frac{2}{10}=\\frac{1}{5}.$$
Rješenja dane jednačine su $x_1=1$ i $x_2=\\frac{1}{5}$.

b. $D_f=\\mathbb{R}$. Imamo da je $a=4,\ b=4$ i $c=1$ te $D=4^2-4\cdot 4\cdot 1=0$. Dakle, jednačina ima jedno dvostruko realno rješenje $$x_1=x_2=-\\frac{b}{2a}=-\\frac{4}{8}=-\\frac{1}{2}.$$

c. $D_f=\\mathbb{R}$. Imamo da je $a=1,\ b=-2$ i $c=5$ te $$D=(-2)^2-4\cdot 1\cdot 5=-16<0,$$ tj. jednačina ima konjugirano-kompleksna rješenja:
$$x_{1,2}=\\frac{-(-2)\\pm \\sqrt{-16}}{2\cdot 1}=\\frac{2\\pm 4i}{2}=1\\pm 2i.$$
Dakle, $x_1=1+2i$ i $x_2=1-2i$ su rješenja dane jednačine.
