# Project Name : Transfer_learning_pneumonia


![](https://i.imgur.com/jZqpV51.png)


In this project, I've used [VGG16](https://www.pyimagesearch.com/2017/03/20/imagenet-vggnet-resnet-inception-xception-keras/#:~:text=VGG16%20and%20VGG19&text=The%20VGG%20network%20architecture%20was,each%20other%20in%20increasing%20depth.) architecture and used transfer learning to help ahieve a better accuracy. \
There were 5216 training images and 16 validation images in the dataset from Kaggle. Using this model I've achieved 88.6% accuracy without 
fine-tuning of the model. \
And after fine-tuning ,i.e., unfreezing the frozen layers of VGG16 architecture and using very low learning rate to train the model again which helped me achieve 90.3%.
## Technologies and libraries used:
1.) Numpy. \
2.) Keras. \
3.) Pandas. \
4.) Google Colab. 
* Link to data-set: [Kaggle Data-set](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) .
* Link to google colab notebook : [Transfer Learning Pneumonia](https://colab.research.google.com/drive/1GOaxaxbFfrW_2j2NWW1tAdiuUuvjg98O?usp=sharing) .
