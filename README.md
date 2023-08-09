# Fation_MNIST_CNN

### The project includes two models with different features ,
Obviously, there are two different outputs, which are mentioned below:

## First output :
![firstModel_trainAccuracy_validAccuracy](https://github.com/payamsaemij/Fation_MNIST_CNN/assets/109211741/32a33e60-eda8-490f-a9d1-2d3c02b77aec)
![firstModel_trainLoss_validLoss](https://github.com/payamsaemij/Fation_MNIST_CNN/assets/109211741/fb0a8e0b-4852-4be6-aed2-a794920daa42)

It is interesting that at first I thought the model was trained accurately, but when I drew the loss diagram and checked it later, I realized that the network was overfit.




-----
## Second model : 
![secondModel_trainAccuracy_validAccuracy](https://github.com/payamsaemij/Fation_MNIST_CNN/assets/109211741/0897de5e-9599-4f64-b187-8e8d335c0c33)
![secondModel_trainLoss_validLoss](https://github.com/payamsaemij/Fation_MNIST_CNN/assets/109211741/88e7e337-fc03-498c-832d-f460fac78352)

In the second model, by adding the dropout function, I was able to prevent the model from overfitting.
If we look carefully, we will notice that the accuracy of the second model is lower, but because the learning process did not have overfitting, it is a better model.

