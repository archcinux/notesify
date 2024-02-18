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

---
# Références
1. 