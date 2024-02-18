24-09-2023 14:54
Libellé: #moc
Liens : [[BTS MAV]] 

---
# Physique

# Acoustique
## Reverb Time (RT)
norme RT60
## Fréquence propre d’une salle parallélépipède.
$$f=\frac{c}{2} \sqrt {{\frac{p²}{L²}}+{\frac{q²}{W²}}+{\frac{r²}{H²}}}$$
exemple avec $L=6.8$ m; $W=5.7$ m ; $H=3.3$ m. 

## Dénombrement des fréquences propres.
$$nf=\frac{4\pi}{3}V(\frac{f}{c})^3+(\frac{\pi}{4})S(\frac{f}{c})²+\frac{Lt}8(\frac{f}{c})$$
V = L*W*H
S = surface totale des parois de la salle $2*(LW+WH+HL)$
Lt = longueur totale des arêtes de la salle $4*(L+W+H)$
### Application

salle de 2 x 3 x 2.5m
n(1000) = 1861 / 1872 
n(100) = 5.21

V = 15 m ; S = 37 m ; Lt = 60 m

salle de 10 x 20 x 8
n(1000) = 
n(100) = 235.89

V = 1600 m ; S = 880 m ; Lt = 152 m

éviter phénomène de coincidence

écho à partir de 50 ms
## Formule RT
$$TR=0.16\cdot \frac{V}{A}$$
La durée de réverbération $TR$ est donnée par la relation de Sabine en fonction du volume $V$ de la pièce et de la surface équivalente d’absorption $A$.

On connaît l’expression de la surface équivalente d’absorption A : 
$$A=\alpha \cdot S$$
et $V$ le volume en $m³$ :
$$V=S\cdot h$$
### Application : pour la surface de la moquette seulement et non toute la surface.
h = 2.5 m ; surface du sol = 20 $m²$ ; $\alpha$ moquette = 0.25
A = 5 $m²$ ; $V$ = 50 $m³$ ; $TR=0.16 \cdot \frac{50}{5}$ = 1.6 $s$.

## Loi d’Eyring
$$T=0.16\cdot \frac{V}{{-S\cdot ln(-\alpha)}}$$

# acoustique architecturale phy
## Intensité réverbérée
En chaque point du local, l’intensité sonore globale I est la somme de deux intensités sonores :
- L’intensité $I_{d}$ , rayonnée directement par la source de directivité Q : $$I_{d}=\frac{Q \cdot P}{4\pi \cdot d²}$$
	- intensité relative au “champ direct”
- L’intensité sonore réverbérée qui elle ne dépend pas de la distance d ; on montre qu’elle est à peu près égale à : $$I_{r}=\frac {4 \cdot P(S-A)}{SA}=\frac{4P}{R_{L}}$$
	- P : puissance de la source 
	- S : surface totale des parois du local en m² 
	- A : surface d’absorption équivalente du local en m² Sabine.
## Surface d’absorption équivalente 
Le terme $A=\alpha_{1}S_1+\alpha_{2}S_{2}+\alpha_{3}S_{3}+...$ a la dimension d’une surface ; on l’appelle “surface d’absorption équivalente” du local ; en effet, la surface A serait la surface parfaitement absorbante (coefficient d’absorption égal à 1) qui a globalement la même absorption que le local de surface $S=S_{1}+S_{2}+S_{3}...$
$$
\begin{align*}
A \cdot 1 &= \alpha_{1}S_{1}+\alpha_{2}S_{2}+\alpha_{3}S_{3}+...\\
A&=\sum\limits_{i} \alpha_{i}S_{i}
\end{align*}
$$

- A est en parfois en “m² par Sabine”

## Temps de réverbération
C’est le temps nécessaire pour que l’intensité diminue de 60 $dB$ après extinction de la source, il se note Tr ou RT60 et s’exprime en secondes.
$$Tr=0.16 \cdot \frac{V}{A}$$
- V : volume du local considéré en m².
- A : aire d’absorption équivalente du local considéré.

|  | Salle de concert | Pièce vide | Pièce meublée  |  |
| ---- | ---- | ---- | ---- | ---- |
| Tr | 0.8 à 1.5 |  |  |  |

## Indice d’affaiblissement de la paroi
La capacité isolante d’une paroi s’exprime à l’aide d’un indice d’affaiblissement acoustique noté $R$ (sans dimension) $$R=10 \cdot log(\frac{1}{\tau})$$
- $\tau$ : taux de transmission de la paroi coefficient sans unité.

| intérieur | mur | extérieur |
| ---- | ---- | ---- |
| $L_{int}$ | $R$ | $L_{ext}$ |
- $R = L_{int} - L_{ext}$
- $L_{ext} = L_{int} - R$
- $L_{int} = R + L_{ext}$

---
# Références
1. 