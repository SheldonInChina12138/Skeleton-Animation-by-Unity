# GPU instanced Skeleton Animation by Unity

![image](https://user-images.githubusercontent.com/81029635/179180579-61f16e5e-0668-47a0-a80f-1015fc3ee97b.png)

1.收集模型中所有SkinnedMeshRenderer的骨骼信息；
2.Mesh中骨骼权重相关信息集成到新的Mesh中；
3.生成一张记载着骨骼动画信息的图，以便在顶点着色器中读取；
4.顶点着色器中每个顶点通过骨骼动画信息和权重，实时计算出自己的位移等信息。

1. Collect skeletal information of all the Skinnedmeshrenderers in the model;
2. Information about bone weights in the Mesh is integrated into the new Mesh;
3. Generate a graph with the information of bone-animation for reading in vertex shader;
4. In vertex shader, each vertex can calculate its displacement and other information in real time through bone-animation information and weights.
