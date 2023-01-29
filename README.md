# VisionProfile
  &ensp;&ensp;&ensp;&ensp;After preparing for research proposal in 2022, I found out that many papers only offer PyTorch models for reference. Meanwhile, me myself also sufferred from version control issues of tensorflow. So I defect to the enemy, PyTorch. </br>
  &ensp;&ensp;&ensp;&ensp;Since this transformation is a tough job, I plan to achieve something simultaneously. Why not replicate the previous learning path in computer vision area. This profile records efferts that I did during this transformation, and part of the painful past exploring deep learning self-motivatedly. Thanks for not helping USTB. </br>

## :mortar_board: Fundamental Knowledge Base

[torch_git]:https://github.com/Xcanton/TorchLearn
<br>[`torch study notebook`][torch_git]</br>

## :city_sunset: Performance Metrics
- <b>General Metrics</b>
  - <b>_Confusion Matrix_</b>
    - _True Positive (TP)_
    - _False Positive (FP)_
    - _False Negative (FN)_
    - _True Negative (TN)_
  - <b>_Accuracy_</b>
    $$Accuracy = \frac {TP + TN}{TP + TN + FP + FN}$$
  - <b>_Precision_</b>
    $$Precision = \frac {TP}{TP + FP}$$
  - <b>_Recall_</b>
    $$Recall = \frac {TP}{TP + FN}$$
  - <b>_F-Score_</b>
    $$F_\beta Score = (1 + \beta^2) * \frac {Precision \times Recall}{\beta^2 \times Precision + Recall}$$
    _*_ $\beta^2$ _is the importance weight of Precision. When_ $\beta^2$ _belongs to_ $(-1, 1)$ _means the <b>Precision</b> is more important than the <b>Recall</b> rate._
    
- <b>Semantic segmentation Metrics</b>
  - <b>_Pixel Accuracy (PA)_</b>
  - <b>_Class Pixel Accuracy (CPA)_</b>
  - <b>_Mean Pixel Accuracy (MPA)_</b>
- <b>Intersection over Union (IoU)</b>
  - <b>_IoU_</b>
    $$IoU = \frac {|A \cap B|}{|A \cup B|}$$
    _* where_ $A$ _and_ $B$ _are two arbitrary convex shapes that_ $A, B \subseteq S \in R^n$
  - <b>_Generalized Intersection over Union (GIoU)_</b> [ :link: ][GIoU_Paper]
    $$GIoU = IoU - \frac {|C - A \cup B|}{|C|}$$
    _* for_ $A$ _and_ $B$_, find the smallest enclosing convex object_ $C$_, where_ $C \subseteq S \in R^n$
  - <b>_Distance Intersection over Union (DIoU)_</b> [ :link: ][CIoU&DIoU_Paper]
    $$DIoU = IoU - \frac {\rho^2(b, b^gt)}{c^2}$$
    _* where_ $b$ _and_ $b^gt$ _denote the central points of_ $A$ _and_ $B$_,_ $\rho^2(\cdot)$ _is the <b>Euclidean distance</b>, and_ $c$ _is the diagonal length of the smallest enclosing box covering the two boxes._
  - <b>_Complete Intersection over Union (DIoU)_</b> [ :link: ][CIoU&DIoU_Paper]

[GIoU_Paper]:https://arxiv.org/pdf/1902.09630.pdf
[CIoU&DIoU_Paper]:https://arxiv.org/pdf/1911.08287.pdf
## :construction: Classic Network

[lenet_notebook_git]:https://github.com/Xcanton/LeNetLearn
<br>[`LeNet study notebook`][lenet_notebook_git]</br>
