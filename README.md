# Caption_Aided_Image_Classifier_for_Unusual_Images

Google Colab code
Data required by this code can be found at https://colab.research.google.com/drive/1TbR6xdfBJ36xnVmV4MizzECIZaNQ4AnI

Background
Although scene understanding systems have made a huge progress in recent years and can do very well on common images, the “unusual” images, which may contain uncommon scenes and combinations of objects often break a lot of scene understanding systems. 
The goal of this study is to implement a classifier to sort out “unusual” images from the majority “usual” ones. As its name implies, “unusual” images are very rare in the widely used datasets such as Microsoft’s COCO (Common Objects in Context) and Stanford’s ImageNet. Therefore, picking out “unusual” images by humans will cost a large amount of time and money, not mentioning potential bias caused by different human labelers. Training a binary classifier could help us to significantly enhance the accuracy and efficiency in selecting out “unusual” images. With the help of a high accuracy classifier, we can even create a dataset contains only unusual images. With the help of it, researchers can better understand the properties of “unusual” images and develop more advanced scene understanding systems to tackle the problem.

In this report I will present:
  1.	An introduction of the dataset created by student Sai Krishna Bollam
  2.	An image classifier trained on the dataset and its performance
  3.	A text classifier trained on captions corresponding to images in the dataset
  4.	How the two classifiers are combined to perform ensemble classification
  5.	Evaluation and analysis of the results
