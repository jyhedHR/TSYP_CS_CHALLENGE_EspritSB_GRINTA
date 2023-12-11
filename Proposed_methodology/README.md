<p align="center">
  <a href="" rel="noopener">
 <img src="Optimization/images/tsyp.png" alt="Project logo"></a>
</p>
<h3 align="center">Section II : Enhancements and Performance Optimization</h3>

<div align="center">


</div>

---

<p align=""> Welcome to "Proposed Methodologies" notebook, a strategic guide shaping the future of deepfake and shallowfake detection. Discover three key optimizations: "Dataset Fine-Tuning" refines adaptability, "Hyperparameter Tuning" enhances accuracy, and "Architecture Modification" pushes detection boundaries.
    <br> 
</p>

## 📝 Table of Contents
#### <span style="color:#E3242B" > 1 - Data Visualization </span>
- [Data visualization](#data_visualization)
#### <span style="color:#E3242B" > 2 - Optimization </span>
- [Introduction](#introduction)
- [Optimization Strategies](#optimization)
- [Dataset](#dataset)
- [Data Preparation and Training](#data_prep)
- [Evaluation and Results](#evaluation)

## 🧐 Data visualization <a name = "data_visualization"></a>

Explore the inner workings of our deepfake detection model through captivating data visualizations. Interactive charts and graphs reveal hidden patterns and trends, offering a deeper understanding of its performance and decision-making process. This visual journey empowers us to refine our model and enhance its effectiveness.
<br>Details mentioned [here](https://github.com/jyhedHR/TSYP_CS_CHALLENGE_EspritSB_GRINTA/blob/main/Proposed_methodology/Data_Visualization/README.Md)

## 💡 Introduction <a name = "introduction"></a>

This notebook takes a closer look at three methods presented in the paper. It goes through each method step-by-step to better understand how it works. This will help us improve the results discussed in the paper.


## 🏁 Optimization Strategies <a name = "optimization"></a>
### <span style="color:#E3242B" > 1. Architecture Modification  </span>


In this approach, we suggest changing the foundational structure of our model by replacing the Resnet50 backbone. The rationale behind this is to explore alternative backbones that may better suit the specific needs of our task. While several pre-trained backbones may outperform Resnet50 in various scenarios, it's crucial to carefully consider the unique nature of our task. The decision to explore alternative backbones should balance potential benefits with practical constraints such as computational resources and training time.

### <span style="color:#E3242B" > 2. Hyperparameter Tuning   </span>

In the Hyperparameter Tuning approach, we propose re-training the model with new, more complex hyperparameters. However, it's essential to acknowledge potential challenges. The model developed in the research paper is likely hyperparameterized to achieve optimal parameters. Recreating and evaluating the model with alternative hyperparameter settings might be computationally expensive and could yield less favorable outcomes compared to the meticulously tuned version presented in the research paper.

### <span style="color:#E3242B" > 3. Dataset Fine-tuning    </span>

Upon scrutinizing the results, it is evident that our model performs well on the Deepfakes dataset but suboptimally on Shallowfakes datasets. To address this disparity and enhance the model's versatility, we propose undertaking a fine-tuning process using the Shallowfakes dataset. This strategic adjustment aims to optimize the model specifically for the challenges posed by shallowfake image manipulation detection.


## 🔧 Dataset <a name = "dataset"></a>

We use the open-source [CIFAKE dataset](https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images/data) available on Kaggle, containing REAL and FAKE classes. The REAL images are collected from Krizhevsky & Hinton's CIFAR-10 dataset, while the FAKE images are generated using Stable Diffusion version 1.4. The dataset comprises 100,000 training images (50k per class) and 20,000 testing images (10k per class).

## 🎈 Data Preparation and Training <a name="data_prep"></a>

In this step, we undertake data preparation tasks such as consolidating all images into a single folder and generating a paths.txt file for fine-tuning. The training process involves using the generated paths file. After finishing training, we proceed with evaluation.

## 🚀 Evaluation and Results <a name = "evaluation"></a>

In summary, our methodology has exhibited outstanding performance, notably outperforming others in both AUC and F1 score metrics. This success can be attributed to our meticulous fine-tuning strategy, leveraging a pre-trained model, and harnessing extensive data from the source domain. Our findings underscore the robustness of our approach across diverse datasets, validating its versatility and applicability.
