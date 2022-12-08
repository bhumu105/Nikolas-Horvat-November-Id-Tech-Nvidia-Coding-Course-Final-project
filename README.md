# Nikolas-Horvat-November-Id-Tech-Nvidia-Coding-Course-Final-project
 Image Classification Network for Motorcycles and Cars

My project will detect wether an image is a car or motorcycle. It will detect wether it is a car or a motorcycle, by breaking it down throught pixels and vectors.

![Image of a Car](Cover_Image.jpg)

The Algorithm

My algorithm will use an imag.net classification system to identify wether an object is a car or motorcycle by breaking it down thorugh vectors and pixels. Something which is extremly crucial for when inputting hte code to run the program is that when you are creating a variable, you must create a variable Net that points to the Motorcycle_Car folder in this repository . 

 Running this project

1. Set up the Jetson-Inference Project
2. NET=Motorcycle_Car 
3. imagenet.py --model=$NET/resnet18.onnx --input_blob=input_0 --output_blob=output_0 --labels=$NET/labels.txt input_image.jpg output_image.jpg


[View a video explanation here](video link)
