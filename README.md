# FashionMNIST
Building a CNN model to classify images of FashionMNIST dataset from PyTorch.
Also comparing the performance of CNN model with baseline models
- Model 0: Linear classifier
- Model 1: Model with Non-Linearity

Model 2: CNN model

## Dataset
### Class names
['T-shirt/top',
 'Trouser',
 'Pullover',
 'Dress',
 'Coat',
 'Sandal',
 'Shirt',
 'Sneaker',
 'Bag',
 'Ankle boot']
 ### Dataset Spilt
 (60000, 10000)
 ### Random Images
 ![image](https://github.com/MNaumanShahid/FashionMNIST/assets/133298903/95533c5e-4f1b-4941-bccb-27bab9d8f5ae)

 ## Comparision of Models
 	        model_name              model_loss	   model_acc	   training_time
     0	FashionMNISTModelV0	0.476639	  83.426518	34.251007
     1	FashionMNISTModelV1	0.685001	  75.019968	29.551062
     2	FashionMNISTModelV2	0.321629	  88.498403	61.724334

![image](https://github.com/MNaumanShahid/FashionMNIST/assets/133298903/7f8f2594-6a65-4ef1-a4c3-d8852f9a273c)

## Random predictions
![image](https://github.com/MNaumanShahid/FashionMNIST/assets/133298903/c4503aab-90f1-42ad-a103-edc44ebed6f8)

## Confusion Matrix
![image](https://github.com/MNaumanShahid/FashionMNIST/assets/133298903/f3e29be3-2792-4fb4-944c-f0661e7c197d)
