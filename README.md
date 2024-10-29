# Tactile Path Guidance via Weakly Supervised Visual Attention-presentation

Abstract—Tactile paving is a structure available on sidewalks
that supports visually impaired people in walking independently.
Maintaining this and other structures in the urban environment
is essential for pedestrians’ safety and well-being. Computational
solutions for their assessment, an essential part of urban infras-
tructure maintainability, require the availability of specific data,
which is costly and time-consuming to obtain. In this context,
this work proposes using the SAM2 segmentation model as a
basis to enhance saliency detection models. These saliency models
can then detect important urban features more accurately and
with lower costs, making them ideal for deploying on mobile
devices. This paper illustrates how this approach can improve
the identification of tactile paving to aid the mobility of visually
impaired users while also collecting summarized data about the
conditions of these structures.

---

Here you will find the scripts used in the experiments.

#### installing

We used python==3.10.15 and torch==2.1.0+cu121 in the environment.

Also, install requirements.txt.

TODO

- [x] pegar arquivos que estiverem no computador de trabalho
- [x] preparar dataset (tudo na estrutura do side seeing)
- [ ] dados de clicks
- [ ] script de segmentaćão
- [ ] gerar mapas de saliência a partir da segmentaćão


Videos:


ID | Duration (s) | Total frames
-|-|-
XJUNDIAI-HSV\#BLOCK01 | 241.94        | 7,259
XJUNDIAI-HSV\#ROUTE01 | 139.82        | 4,195
JUNDIAI-HSV\#ROUTE02 | 69.66         | 2,090
XSANTOS-HM\#BLOCK01   | 321.43        | 9,644
XNSAOPAULO_HC\#ROUTE02
All                  | 772.85        | 23,188


Passos:

gerar clicks

gerar segmentaćão a partir do SAM2

gerar pontos de interesse (curvas)

separar nas pastas correatamente da forma do dataset famoso
>>>>>>> 06a8cec (initial commit for full code refactoring)
