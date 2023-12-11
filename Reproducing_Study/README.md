<p align="center">
  <a href="" rel="noopener">
 <img src="Training/images/tsyp.png" alt="Project logo"></a>
</p>
<h3 align="center">Section I : Usecase Replication</h3>

<div align="center">


</div>

---

<p align=""> This series of notebooks takes us on a journey through the fascinating world of deepfake detection. We begin by faithfully <b> reproducing the results of a cutting-edge research study </b> , establishing a solid foundation for our further explorations. Next, we tackles the crucial task of <b>organizing and cleansing massive datasets</b>, ensuring optimal training conditions for our model. Finally, we delves into the realm of <b>evaluation</b>, meticulously assessing the model's performance on diverse datasets to identify its strengths, weaknesses, and potential biases. This comprehensive process provides valuable insights into the model's capabilities and limitations, laying the groundwork for future improvements and refinements.
    <br> 
</p>

## 📝 Table of Contents
- [Data Preparation](#data_preparation)
- [Training](#training)
- [Evaluation](#evaluation)


## 🧐 Data Preparation <a name = "data_preparation"></a>

Our deepfake detection journey began with a formidable obstacle–preparing a massive dataset of deepfake and shallowfake images and real images. We tackled this challenge by strategically leveraging existing resources, optimizing data transfer, utilizing efficient processing tools, and implementing data augmentation.<br> These efforts ensured efficient data preparation despite its size, laying a solid foundation for our subsequent model training and demonstrating our ability to handle large-scale data challenges in the field of deepfake detection.<br>
Details mentioned [here](https://github.com/jyhedHR/TSYP_CS_CHALLENGE_EspritSB_GRINTA/blob/main/Reproducing_Study/Data_Preparation/README.Md)
## 💡 Training <a name = "training"></a>

Our training journey began on Colab Pro, leveraging the powerful A100 instance. As the model's demands grew, we migrated to a leased GPU cluster from <span style="color:yellow" >  Vast.ai </span> to ensure efficient training and exploration of model enhancements.<br> We faithfully replicated the original study's training configuration and fine-tuned hyperparameters like learning rate and batch size for optimal performance. While resource limitations led to an early stop, we successfully saved the model at its current state.<br> This valuable progress information will be instrumental in future training and refinement efforts. We are actively preparing to evaluate the model's performance on Colab.<br>
Details mentioned [here](https://github.com/jyhedHR/TSYP_CS_CHALLENGE_EspritSB_GRINTA/blob/main/Reproducing_Study/Training/README.Md)

## 🚀 Evaluation <a name = "evaluation"></a>

We extend our analysis beyond deepfakes to include shallowfakes, employing diverse datasets and relevant metrics to achieve a nuanced understanding of the model's performance on different types of manipulated media. Our rigorous evaluation process uncovers the model's strengths and weaknesses for both deepfakes and shallowfakes, identifying potential biases and their impact.<br> The resulting insights pave the way for targeted improvements and further development aimed at creating a more robust and effective deepfake detection solution.<br>
Details mentioned [here](https://github.com/jyhedHR/TSYP_CS_CHALLENGE_EspritSB_GRINTA/blob/main/Reproducing_Study/Evaluation/README.md)


