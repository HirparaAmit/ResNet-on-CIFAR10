# ResNet-on-CIFAR10

I made this project to improve the performance of CNN model on CIFAR10 dataset. I implemented complete ResNet9 architecture from scratch to understand the exact working of ResNet models.

I got 75% accuracy in CNN model, but when I tried ResNet9 architecture on CIFAR10 dataset I got 80% validation accuracy just after 6 epochs.

I also perform data normalization and data augmentation on dataset before take it as input.

After normalization, datset was look like this:

![image](https://user-images.githubusercontent.com/57864056/160348799-25d625e2-7511-47f2-9efd-d0ad1cef27f9.png)

In this project I also add one important thing is that move our model, data and training on GPU.

I trained this model just for 5 epochs and I got 80% validation accuarcy. This is the amazing thing.

At the end I tried to print graphs between "Accuracies vs. Epochs" and "Trainign and Validation Loss vs. Epochs".
