# Corrigé : Mécanique 

## Exercice 8 : Chute libre avec vitesse initiale vers le haut

- système {Balle}
- Référentiel Terretre supposé galiléen (car la durée de l'expérience est très courte)
- Repère : c.f. diagramme (vers le bas positif)
- DBF (ci-contre) : qu'une seule force présente $\vec{F_g} = m\vec{g}$

<img src="https://hackmd.io/_uploads/BkS1CX3RA.png" width="200" align="right">

D'après le PFD : 
$$\sum{\vec{F_{ext}}} = m\vec{a}$$ $$\vec{a} = \vec{g} $$ $$a = g$$ $$v = gt-v_0 $$ $$x = \frac{gt^2}{2} - v_0t$$
Notre équation horaires est donc : $x = \frac{gt^2}{2} - v_0t$

1. on veut trouver $t_s$ tel que $x(t_s) = h$. 
$$x(t_s) = h = \frac{gt_s^2}{2} - v_0t_s$$ 
que l'on va mettre sous sa forme canonique : 
$$\frac{gt_s^2}{2} - v_0t_s - h = à$$
On peut trouver les racines : 
$$t_s= \frac{v_0 \pm \sqrt{v_0^2 + 2gh}}{g}$$
Mais la solution qui a du sens physique est la solution positive, c'est à dire :  $t_s= \frac{v_0 + \sqrt{v_0^2 + 2gh}}{g}$
Avec l'application numérique : $t_s= \frac{5,0 + \sqrt{5,0^2 + 2(10)(2,0)}}{10} = 1,3\; s$ 
Une balle donc lancée vers le haut avec une vitesse initiale de $2,0\; m/s$ touche le sol au bout de $1,3\; s$. 

2. On veut trouver l'expression de $v = f(x)$. On va donc trouver d'abord $t=f(x)$ que l'on substitue par la suite dans $v=f(t)$. 
$$x = \frac{gt^2}{2} - v_0t \Leftrightarrow \frac{gt^2}{2} - v_0t - x = 0$$
dont la solution ( positive en $t$) est : $$t = \frac{v_0 + \sqrt{v_0^2 + 2gx}}{g}$$
que l'on substitu dans $v=f(t)$ : 
$$v(x) = g \left(\frac{v_0 + \sqrt{v_0^2 + 2gx}}{g} \right) - v_0$$ 
et nous obtenons : $v(x) = \sqrt{v_0^2 + 2gx}$
3. On chercher l'expression qui donne $h = f(v_s)$ . On a donc : 
$$v(h) = \sqrt{v_0^2 + 2gh} \;\;\Leftrightarrow\;\; h = \frac{v_s^2 - v_0^2}{2g}$$ 
4. Application numérique : $v_s = 8,1\; m/s$
5. Application numérique : 
Dans le cas où l'on veut $v_s = 10,0\; m/s$ $$h_0 = \frac{10^2 - 5,0^2}{2(10)} = 3,8 \; m $$
Dans le cas où l'on veut $v_s = 4,0\; m/s$ $$h_0 = \frac{4,0^2 - 5,0^2}{2(10)} = -0,45 \; m $$
Cette deuxixème valeur n'a pas de sens physique, ce qui veut dire qu'avec une $v_0=5,0$ vers le haut il est impossible d'arriver au sol à $4,0$, depuis n'importe quelle hauteur (ce qui est logique). 

## Exercice 9 : Sphère en haut d'une pente : 
