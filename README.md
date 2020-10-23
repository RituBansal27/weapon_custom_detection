# Object detection by using coco dataset!
In this project, I used Yolov3 deep learning Algorithm with darknet framework to identify the objects in an image or in video.
!git clone https://github.com/AlexeyAB/darknet this link provides you everything.
I used google colab to do the processing , else you can use your local system for the same by installing Opencv with your GPU. Install Cmake and visual studio to help you out!
Firstly,I begun with the coco data set containing the 80 classes and all though its a trained set so you can use it directly to on tour system and can detect objects in video/image.
for that also you need to download weights there is link in notebook itself 
!wget https://pjreddie.com/media/files/yolov3.weights

# weapon detection!
Now, I created my own custom detection which detects the weapons in an image/video.
I took dataset from open image dataset v6+ and by using OID_v4 Toolkit conert the annotaion of the images into labels.
https://drive.google.com/file/d/1LJJVvKhm28Rbkj9xFYxaVSmTq-b1nNTk/view?usp=sharing 
This is zipped file of the data set with labels. you can directly use it.
Make changes in Yolov3_config file, create obj.data , obj.names.
And download pretrained convolutional layer weights
!wget http://pjreddie.com/media/files/darknet53.conv.74

