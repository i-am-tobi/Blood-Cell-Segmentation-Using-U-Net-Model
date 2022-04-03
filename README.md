# Blood-Cell-Segmentation-Using-U-Net-Model
Blood cell segmentation is one of the most important research areas in computer vision in the current scenario.Mannually segmenting different blood cell images 
ia very tidious job and this can cause human related errors. So, automating the blood cell segmentation process is a veryimportant task.
In this project I have used the state of the art U-Net model for segmenting different blood cell images and counting malicious cell causes Myeodysplastic syndrom.
The pipeline of segmenting cells is shown below.

Reading The Image -------> Implementing Some Morphological Operation -------> Creating The Mask of That Particular Image -------> Training The Model With The Actual Image and It's Particular Mask -------> 
Test The Model for a Test Image -------> Storing The Predicted Mask -------> Operating Morphological Operation on The Mask -------> Collect The appropiate Co-ordinates From The Mask -------> Aplly The Co-ordinates to the Real Image ------->
Draw Bounding Box to THe Real Image -------> Storing The Segmented Image.
![1](https://user-images.githubusercontent.com/87241726/161416099-d54cfda7-892c-4325-be66-bbd30c49f267.png)
![2](https://user-images.githubusercontent.com/87241726/161416108-7441ea8e-47bf-40b4-b5fa-3659e2cd5499.png)
![3](https://user-images.githubusercontent.com/87241726/161416112-5fafe480-6720-4832-b0a1-60bbc39276c3.png)
![4](https://user-images.githubusercontent.com/87241726/161416166-d674229c-c79f-4839-996a-ea73e74f2d2f.png)
![5](https://user-images.githubusercontent.com/87241726/161416170-5f8c3c21-fb13-4a41-84ab-30bfff8bd6f5.png)

