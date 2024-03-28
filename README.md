## GSOC-24 DeepLense Common Task - Substructure Classification



Individual ROC             |  Average ROC
:-------------------------:|:-------------------------:
![ROC plot showing individual ROC curves for all three classes](https://github.com/AarjavSatia/GSOC-24_DeepLense_Common_Task/blob/main/Images_ROC/MultiROC_1.png?raw=true)  | ![ROC plot showing an average ROC curve for all three classes](https://github.com/AarjavSatia/GSOC-24_DeepLense_Common_Task/blob/main/Images_ROC/MultiROC_2.png?raw=true)

### Model Features:

<p>1) The main idea is to build upon previous papers /cite{}, cite{} that have performed classification on strong lensing images that is why Resnet34 model pretrained on ImageNet dataset has been used for classification as it simple, lightweight and effective.</p>
<p>3) Among the 7500 validation images 90% are used during training as validation and 10% are used to conduct different tests to evaluate the model.</p>
<p>4) Model performs well and gets an accuracy of 92.67% on the test data and attains an average AUC score of 0.9852.
With class individual AUC score being 0.991 for no substructure, 0.985 for sphere and 0.979 for vort. </p>



### Further Modifications and Ideas:
<p>1) Given a larger dataset, transformer based models like ViT and Swin-Transformers can be tried out.</p>
<p>2) Attetnion modules can be encorporated to the base Resnet models which would give the model global awareness from    attention module and high inductive bias from CNN.</p>


