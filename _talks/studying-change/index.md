---
title: "Représenter l'évolution spatio-temporelle de réseaux"
description: "Cartographier des réseaux d'acteurs divers nécessite de spatialiser un vaste ensemble d'informations dans une faible surface graphique. Ce processus souvent fastidieux peut être simplifié par l'usage de représentations dynamiques permettant d'observer l'évolution de trajectoires dans le temps et l'espace. À travers différents exemples, nous présenterons différents moyens de collecter et visualiser l'évolution spatio-temporelle de réseaux divers (mots, lieux, personnes et organisations)."
date: 2017-10-07
layout: slides
hide: true
---

<div markdown="0">
Lyon, 12 & 17 Octobre 2017.

Clément Renaud / http://clementrenaud.com
---
class: center, middle

# Représenter l'évolution spatio-temporelle de réseaux
### Clément Renaud  
[http://clementrenaud.com](bonjour@clementrenaud.com)

Lyon, Oct 2017

---
class: inverse
background-image: url(img/supercargo-img1.png)


.footnote[
# Why study change ?

[Peter Moossgard](http://cargoclub.tumblr.com/), 2016
]
---
# Is ontology over-rated?

### Questions of definitions

How does ontology support the evolution of definitions over time ?

Transversal reflections for scientific disciplines : the effect of time

.col-one-half[
### Learning from China

Most of the time, things are not what they appear to be

Everything change all the time

Illusion of permanence :
- ignorance for decay?
- changes are seen as 'the same, but better'?

]

.col-one-half[
![](./img/PreHeavenBaGua+text.gif)
]

---
name:representation
class: inverse
background-image:url(../MemeWriting/img/perspective.png)

# Recording changes
### Common spaces of representation

.small.footnote[Jan Vredeman de Vries – *Traité « Perspective »* (1604) <br>  source: [Denis Favennec](http://math.univ-lyon1.fr/irem/spip.php?article232) ]


---

# Observing Change

![](./img/Minard.png)

###  how to visualize changes ? esp. changes in complex structures ? how to record changes ?


---

class: center, middle

## Some Examples
(2010-2017)

---
class: middle
## Example 1: Design of a Internet memes data visualisation toolkit


.right-column[
![](./img/Figure2-memes_cyle.jpg)
**The case of the Chinese social network Sina Weibo**
We develop a data mining and visualisation toolkit to study how the information is shared on online social network services. This software allows to observe relationships between conversational, semantical, temporal and geographical dimensions of online communication acts.Internet memes are short messages that spread quickly through the Web.
]

.left-column[
![](./img/caonima.jpg)
![](./img/hexie.jpg)
![](./img/chapitre2-img3.jpg)
![](./img/chapitre2-img4.jpg)
]

---
## Custom visualization software
[http://clementrenaud.com/phD](http://clementrenaud.com/phD) - [(code)](http://github.com/clemsos/mitras)

![](./img/ui-screenshot.png)

---
## Spatio-temporal conversations

![](./img/phD-memes.gif)
---

## Example 2: Historical cartography of university in Europe


[http://clementrenaud.com/carto-univ](http://clementrenaud.com/carto-univ) - [(code)](http://github.com/clemsos/carto-univ)

![](./img/screencapture-carto-univ.png)

This was a small attempt to visualize how universities spread around Europe. We worked on it with Eric Guichard at [AIL](http://barthes.enssib.fr/AIL), based on data compiled by Camille Ducrot. There is several major flaws in this map : the first one being borders... Obviously, looking at Europe with border data from the 16th century does not make any sense.

---

## Example 3: Topogram

[http://topogram.io](https://topogram.io) - [(code)](http://github.com/topogram/topogram) - ongoing project...

Topogram is an open-source software to visualize changes in networks over time and space. It relies on web technologies to provide a web experience.


![](./img/Topogram-Network.png)


---

## Example 4: Makerspaces in China

Studying interactions between a global movement and policy-making locally
[http://mapmakers.space](https://mapmakers.space)


![](./img/makermap.jpg)

---
class: center, middle

## Discussions / Conclusion

---


.left-column[
# Networks as events

### Networks are not "facts"
A sum of trajectories

### Multiple layers to explore
Words, social networks, physical movements, etc.

### Lots of work !
Theoretical, empirical, tools, etc.

(see js lib [graph-events](https://github.com/clemsos/graph-events))

]

.right-column[
![](img/bird-migration-us.gif)
]


---
class: middle,center

## Thank you !

clement.renaud@gmail.com

@clemsos
