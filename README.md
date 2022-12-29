
 
# Brain Tumor Segmentation & Classification Using Machine  Learning (SVM)
### Abstract:
Object  detection  plays  a  major  role  in  many  areas  like  medical  imaging,  aerial surveillance, optimal manipulation and analysis, surgical microscopes, etc.The objective of this project is to develop a model for brain tumor detection and classification i.e., to classify whether the tumor is cancerous [Benign/Malignant] or non-cancerous using SVM algorithm. Earlier many have detected using ANN which works on Empirical Risk Minimization.We are using a Support Vector Machine algorithm that works on structural risk minimization to classify the images. The SVM algorithm is applied to medical images for the tumor extraction, and a model is developed for the tumor classification function. This thesis presents a prototype for SVM-based object detection, which classifies the images and evaluates whether the classified image is cancerous or non-cancerous.
###    Introduction:
##### Brain Tumor:
A  brain  tumor  is  a  mass  or  growth  of  abnormal  cells  in  your  brain. 
Many different types of brain tumors exist. Some brain tumors are noncancerous (benign), and some brain tumors are cancerous (malignant). Brain tumors can begin in your brain (primary brain tumors), or cancer can begin in other parts of your body and spread to your brain as secondary (metastatic) brain tumors. How  quickly  a  brain tumor grows can vary greatly. The growth rate as well as the location of a brain tumor determines how it will affect the function of your nervous system. Brain tumor treatment options depend on the type of brain tumor you have, as well as its size and location.
### Related Works:
Segmentation and classification of brain tumors have been carried out in various studies and the most common methods used in these articles are based on classification, morphological operations. clustering algorithms, thresholding, and for segmentation, Fuzzy c-means has been utilized and for feature extraction, a gray level length matrix is used, and MRI brain images are labeled using the SVM technique  with  separate  kernels.  The  accuracy  results  in  performances  of  SVM classification for  kernel  functions  including  Linear, Quadratic,  and  Polynomial. K-means and  the  Histogram  Normalization are  segmentation  operations. De-noising methods such as the median filter, wiener filter, averaging filter, spatial filter, adaptive filter, and Gaussian filter are used to eliminate noise from the MRI input image during preprocessing. The  resultant will  then  be  normalized  before  being  fed  into  a  classifier  for classification. After segmentation, the tumor is identified using the k-means algorithm. The magnetic resonance image is carried out using the NB classifier and SVM classifier to achieve more accuracy in estimation and classification. Naive Bayes was used for the classifier, while the best accuracy of the SVM classifier. In comparison to other classifiers, the SVM classifier performs well. Since the tumor area is not exact and reliable, the suggested approach has certain drawbacks on the boundary. SVM is used for classification. Here, the input images must go through a series of steps before being focused on the region of interest (ROI). 
The SVM is used for classification in this system. It is possible to attain a degree of precision. The best way to segment and identify a tumor in brain MRI images is to use CNN-based image segmentation, pre-processing procedures, and data augmentation. Bias field improvement, intensity, and regular image patches are all part of it. To research deep structures, this device is based on convolution layers 3×3 with kernels. A strategy is planned in a method and classified the MRI brain tumor where the input is 3-D MR images. This method created high-quality results for accuracy, sensitivity, and specificity. For a multiclass brain tumor, a procedure based on segmentation and feature extraction for images was conferred. A total of 428 MR images were used in this study. The ANN and PCA-ANN methods are used in classification to increase precision. The explained how to solve the image visibility and clearance issue with the fewest possible configuration parameters on the input image. They did this by dividing the medical specialty procedure into two groups of automated procedures. Inset one, they focus on image quality and segmentation of the object of interest, which is a tumor, by forming an edge diagram. In the second package, they performed data analysis by measuring the parameters derived from the diagnosis.The multi-modal hybrid fusion and convolution neural network recognition system was combined in this experiment. The use of the 2D CNN and 3D CNN multimodal extension by having brain lesion with various characteristics in 3D was used in [12] this article. By solving the 2D CNN for various modal details at raw input faults to boost convergence speed, a real normalization layer was added to the convolution and pooling layers to remove the issue of overfitting. Resulting in the improvement of the loss function, so weighted loss function is added in the lesion area to develop the feature learning. The image segmentation method uses the FCM clustering algorithm through a rough set theory. The authors construct the feature values obtained from the FCM segmentation outcome and the image is  separated into small  areas  based on the attribute. Biased values are obtained with value decrease and used for the calculated variation between the region and comparison of the region. Later was realized through similarity variation degree [13]. This final value of equivalence degree is used to evaluate the segmentation of images and combine regions. The method has the limits up to single MRI images of brain and CT, artificially generate images. From the above-mentioned  survey,  it  has  been  justified  that  some  techniques  are  designed  for segmentation and classification, some are simply for feature extraction, and some are 
only for classification .

###    Problem Statement:
A brain tumor is a collection, or mass, of abnormal cells in your brain. Your skull, 
which encloses your brain, is very rigid. Any growth inside such a restricted space can 
cause problems. Brain tumors can be cancerous (malignant) or noncancerous (benign). When benign or malignant tumors grow, they can cause the pressure inside your skull to increase. This can cause brain damage, and it can be life-threatening. Brain tumors are categorized as primary or secondary. A primary brain tumor originates in your brain. Many primary brain tumors are benign. A secondary brain tumor, also known as a metastatic brain tumor, occurs when cancer cells spread to your brain from another organ, such as your lung or breast. Only about 5 to 10 percent of all cancers are genetically  inherited,  or  hereditary.  It’s  rare  for  a  brain  tumor  to  be  genetically inherited. Talk to your doctor if several people in your family have been diagnosed with a brain tumor. Your doctor can recommend a genetic counselor for you. Risk for most types of brain tumors increases with age. Brain tumors in general are more common among Caucasians. However, African American  people  are  more  likely  to  get  meningiomas.  Being  exposed  to  certain chemicals, such as those you might find in a work environment, can increase your risk for brain cancer. The National Institute for Occupational Safety and Health Trusted Source keeps a list of potential cancer causing chemicals found in workplaces. People who have been exposed to ionizing radiation have an increased risk of brain tumors. You can be exposed to ionizing radiation through high-radiation cancer therapies. You can also be exposed to radiation from nuclear fallout. The nuclear power plant incidents in Fukushima and Chernobyl are examples of how people can be exposed to ionizing 
radiation.

▣ Clinical decisions regarding the treatment of brain neoplasms rely, in part, on MRI at various stages of the treatment process. Radiological diagnosis is based on the multi-parametric  imaging  profile  (CT,  conventional  MRI,  advanced  MRI).  Tumor characterization is difficult, because neoplastic tissue is often heterogeneous in spatial 
and imaging profiles [1], and for some imaging techniques often overlaps with normal 
tissue  (especially  the  infiltrating  part)  [2][3].  Gliomas  might  show  mixed 
characteristics, for example demonstrating both low- and high-grade features. The 
reference  standard  for  characterizing  brain  neoplasms  is  currently  based  on 
histopathologic  analysis  following  surgical  biopsy  or  resection,  but  this  also  has 
limitations including sampling error and variability in interpretation [1][4].
###   Suggested Solution:
A new classification approach was developed to improve the noninvasive diagnosis of 
brain tumors. Within this approach, information is extracted from magnetic resonance imaging and spectroscopy data, from which the relative location and distribution of selected tumor classes in feature space can be calculated.This relative location and distribution are used to select the best information extraction procedure, to identify overlapping tumor classes, and to calculate probabilities of class membership. These probabilities are very important, since they provide information about  the  reliability  of  classification  and  might  provide  information  about  the heterogeneity of the tissue.
Classification boundaries were calculated by setting thresholds for each investigated tumor class, which enabled the classification of new objects. Results on histopathologically determined tumors are excellent, demonstrated by spatial maps showing a high probability for the correctly identified tumor class and, moreover, low probabilities for other tumor classes.
The objective of this project is to develop a model for brain tumors detection and classification i.e., to classify whether the tumor is cancerous [Benign/Malignant] or non-cancerous using SVM algorithm. Earlier many have detected using ANN which 
works on Empirical Risk Minimization.

### Data set:

This brain tumor dataset containing 3064 T1-weighted contrast-enhanced images 
from 233 patients with three kinds of brain tumor: meningioma (708 slices), glioma 
(1426 slices), and pituitary tumor (930 slices).

https://figshare.com/articles/dataset/brain_tumor_dataset/1512427?file=7953679

### Tools:

* ![MATLAB][image_ref_607rhn7h]   
    MATLAB 
 

### Team:
1.  Mohamed Ahmed Mohamed El said Abdelrazq Eleraqi
2.  Mohamed Ashraf Ibrahim Elmatboly
3.  Maher Mohamed Abdelrahman Mohamed
4.  Mohamed Ali Hamed Ahmed
5.  Mariam Ahmed Ahmed Mohamed El said
6.  Mustafa Waled Mohamed Elsgeny
7.  Nada Mohamed Abdalla Awad



[image_ref_607rhn7h]: data:image/jpeg;base64,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
    
