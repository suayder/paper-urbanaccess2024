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


Video dataset (not public available):


ID | Duration (s) | Total frames
-|-|-
XJUNDIAI-HSV\#BLOCK01 | 241.94        | 7,259
XJUNDIAI-HSV\#ROUTE01 | 139.82        | 4,195
JUNDIAI-HSV\#ROUTE02 | 69.66         | 2,090
XSANTOS-HM\#BLOCK01   | 321.43        | 9,644
XNSAOPAULO_HC\#ROUTE02
All                  | 772.85        | 23,188


Passos:

generate clicks

generate segmentation from SAM2 model

generate points of interest (in case of this paper, curves)
