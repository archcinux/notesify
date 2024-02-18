---
Date: 13-02-2024 | 09:14
tags:
  - cours
Liens:
  - "[[acoustique]]"
---

---
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