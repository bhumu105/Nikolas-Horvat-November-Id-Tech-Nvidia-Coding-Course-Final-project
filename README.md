# Nikolas-Horvat-November-Id-Tech-Nvidia-Coding-Course-Final-project
 Image Classification Network for Motorcycles and Cars

My project detects different images of cars and motorcycles and detects whether they are either a car or a motorcycle. 

![Image of a Car](Cover_Image.jpg)

## The Algorithm

Add an explanation of the algorithm and how it works. Make sure to include details about how the code works, what it depends on, and any other relevant info. Add images or other descriptions for your project here. 

## Running this project

1. Set up the Jetson-Inference Project
2. NET=Motorcycle_Car #(Create a variable NET that points to the Motorcycle_Car folder in this repository)
3. imagenet.py --model=$NET/resnet18.onnx --input_blob=input_0 --output_blob=output_0 --labels=$NET/labels.txt input_image.jpg output_image.jpg


[View a video explanation here](video link)
