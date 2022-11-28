## Study on Pedestrian Trajectory Prediction Method Based on Attention Mechanism and Spatial-Temporal Network

-  The original is in **CN**. 
-  It's a final thesis instead of conference paper, so the background part is long. 
-  Only interested in method implementation? Start reading from **P19** ~ 
> ### Abstract 
> 
>  <tab>Currently, mobile agents are integrating to people’s daily lives, one issue raised upon which is how do agents handle their interaction with surrounding pedestrians. Considering the dynamic working environment, pedestrian trajectory prediction might contribute to timely adjustment of agents control strategy, which could be an opportunity for smoother and more natural interaction. The major challenge in pedestrian trajectory prediction is the modeling complexity of human behavior. In recent years, most related works focused on modeling pedestrian trajectory by machine learning, and some state-of-the-art deep-learning algorithms have showed considerable performances.   
>  
> This paper discusses related studies of pedestrian trajectory prediction, discovering that the spatial-temporal networks hold a great potential in solving this issue. This work is based on Social-STGCNN model proposed in 2020, to which, an attention module is introduced to model the dynamic interaction between pedestrian. The new framework replaces the dense interaction matrix with sparse interaction matrix. Moreover, in the timing information extraction part, the Temporal Convolution Network is replaced by a Bidirectional Long Short-term Memory network. Finally, the two-dimensional Gaussian distribution of the predicted pedestrian trajectory outputs from the Time-Extrapolator Convolution Neural Network. The results of qualitative, quantitative analysis and ablation experiments on the open-source datasets show that the performance of the model has been improved by the new modules presented in this paper.  
> 
> ### Key Words 
> **pedestrian trajectory prediction; spatial-temporal convolution; self-attention mechanism; bidirectional long short-term memory; two-dimensional Gaussian distribution**
> ### Model Stucture Diagram
> ![image](https://github.com/Zhou-owl/arxiv-undergrad-thesis/blob/main/model%20structure.png)
