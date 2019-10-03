## APTOS-2019-Blindness-Detection([Kaggle Competition](https://www.kaggle.com/c/aptos2019-blindness-detection))

This was a competition hosted on Kaggle in July-August 2019. Here, In this competition the aim was to build a machine learning model to speed up disease detection. The images were collected in rural areas to help identify diabetic retinopathy automatically. 

In this competition, we had 3662 images in 5 classes for training and the data was highly imbalanced. The images looks like this. ![dataset_images](https://user-images.githubusercontent.com/35501699/66106048-98298580-e5da-11e9-8631-8a79a92a8c2b.png)
The dataset can be downloaded from [here](https://www.kaggle.com/c/aptos2019-blindness-detection/data).

We started with very simple models like from resnet50 and in starting we didn't used much of preprocessing. And we got a public score of around 68%
and private score around 87%. And after with a lot of preprocessing which includes ben's cropping, circular crop, brightness, contrast, converting to grayscale we got private score of around 89% . We have also used test time augmentation(TTA).

And our final rank was 471 out of 2943. We learnt a lot during this competition like how to deal with medical images, what kind of preprocessing techniques to use, how to use differnt CNN architectures and when to use them.

This was a team effort of Team_Beacon including 5 members.([Surbhi](https://www.kaggle.com/surbhibhardwaj), [Aditya](https://www.kaggle.com/adityakumar01), [Rohit](https://www.kaggle.com/rohitgr), [Ranjodh](https://www.kaggle.com/ransingh), [Rahul](https://www.kaggle.com/rahul722j))
