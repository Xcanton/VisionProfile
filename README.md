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
    _* Where_ $A$ _and_ $B$ _are two arbitrary convex shapes that_ $A, B \subseteq S \in R^n$
  - <b>_Generalized Intersection over Union (GIoU)_</b>
  - <b>_Distance Intersection over Union (DIoU)_</b>
  - <b>_Complete Intersection over Union (DIoU)_</b>

## :construction: Classic Network

[lenet_notebook_git]:https://github.com/Xcanton/LeNetLearn
<br>[`LeNet study notebook`][lenet_notebook_git]</br>
