## Semantic Edge Detection 

**Description**: For this project, the goal was to allow the robot to detect the most significant object in a cluttered environment. We use a Bi-Directional Cascade Network trained on various datasets (BSDS500, NYUDv2) to create a edge detector network. 

The author of this network makes use of a Scale Enhancement Module (SEM) which utilizes dilated convolution to generate multi-scale features, instead of using deeper CNNs or explicitly fusing multi-scale edge maps. 

**Results**:
![](../images/edges.png)

[Link to original paper](https://arxiv.org/abs/1902.10903)
