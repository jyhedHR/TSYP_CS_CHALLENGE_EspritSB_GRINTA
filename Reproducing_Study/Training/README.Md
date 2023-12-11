<p align="center">
  <a href="" rel="noopener">
 <img src="images/tsyp.png" alt="Project logo"></a>
</p>
<h3 align="center"> <b> Overcoming Hardware Challenges in Deepfake and shallowfake Detection Training
 </b>
</h3>

<div align="center">


</div>

---

This notebook details our initial attempt to replicate a deepfake image manipulation study. We overcame hardware limitations by utilizing Colab Pro and later, a leased GPU cluster. <br> Although training stopped early due to resource constraints, we successfully saved the model for evaluation. We are actively exploring performance improvement strategies and look forward to sharing updates on our progress!

## 📝 Table of Contents

- [Introduction](#introduction)
- [Training](#training)


## Introduction <a name = "introduction"></a>

We strive to be transparent and informative, sharing our experiences and insights to contribute to the broader understanding of deepfake detection and image manipulation localization. <br> We encourage you to explore the contents of this document and join us in advancing this critical field of research.

## Training <a name = "training"></a>

<span style="color:#E3242B" > Hardware Challenges and Solutions : </span><br>
Replicating the original study's findings posed a significant challenge due to the disparity in hardware resources. The original research employed a powerful GPU cluster, far exceeding the capabilities of our local environment. To address this limitation, we implemented a multi-pronged approach:

- Colab Pro: We initially utilized Colab Pro, gaining access to a robust A100 instance. This provided a significant boost, allowing us to modify the code for single-GPU execution and initiate the training process.

- Leased GPU Cluster: As the model's computational demands grew, we transitioned to a leased GPU cluster from vast.ai. This powerful resource provided the necessary horsepower to significantly accelerate training and explore avenues for model enhancement.

<span style="color:#E3242B" > Training Process and Early Stopping : </span><br>
After meticulously setting up the environment, including the Jupyter server and terminal access, we initiated the training process. While we successfully trained the model for a significant portion of the initial phase, reaching approximately 200 epochs, the process stopped prematurely due to resource limitations.

<span style="color:#E3242B" > Saved Model and Evaluation : </span><br>
Despite the early termination, we salvaged the saved model from the generated checkpoints. This preserved the model's state at its current progress, paving the way for future evaluation. We are currently preparing to assess the model's performance on Colab to identify areas for improvement.


