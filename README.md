![alt text](https://kaggle2.blob.core.windows.net/competitions/kaggle/3362/media/woof_meow.jpg)

# Kaggle Dogs Vs. Cats CNN Project

The main goal of the project is to apply various CNN architecture and compare their performance on binary dog vs cat classification [here](https://www.kaggle.com/c/dogs-vs-cats).


## File Description

* cat_dog_cnn_main.ipynb -> This jupyter notebook contains all the content of the project


## Data and Evaluation Criteria

* Training set consists of 12,500 images of cats and dogs respectively (total 25,000 images) [here](https://www.kaggle.com/c/dogs-vs-cats/data).
* The evaluation is done based on accuracy [here](https://www.kaggle.com/c/dogs-vs-cats#evaluation).
* The leader scoreboard can be found [here](https://www.kaggle.com/c/dogs-vs-cats/leaderboard)


## Quick Summary

3 Models were tested in the project

1) Custom CNN for 28 x 28 image size (25,000 training data is split into 20,000 training and 5000 vadlidation images)

2) Transfer learning applied to VGG16 Model (Due to computation time, only 2000 training images and 800 validation images are used)

3) Transfer learning applied to Xception Model (Also due to computation time, only 2000 training and 800 validation images are used)


## Result

1) Custom CNN -> 78% validation accuracy (95th on Kaggle Leaderboard)

2) VGG16 Transfer Learning -> 87~88% validation accuracy (75th on Kaggle Leaderboard)

3) Xception Transfer Learning -> 99% validation accuracy (1st on Kaggle Leaderboard)


## Useful References

* [Kaggle Competition Description](https://www.kaggle.com/c/dogs-vs-cats)
* [Excellent Youtube tutorial on Keras](https://www.youtube.com/watch?v=LhEMXbjGV_4&t=378s) - Excellent series of MLP and CNN tutorial in Keras.
* [Simple CNN structure](https://pythonprogramming.net/tflearn-machine-learning-tutorial/) - Provided simple 28 x 28 CNN structure
* [Blog on Transfer Learning](https://medium.com/@galen.ballew/transferlearning-b65772083b47) - This blog provides a good overview of XGBoost approach to solve the problem. It also provided a good tip on how the ranking of the dog breed can help improve the accuracy.
* [Some issues with Kaggle ranking](http://openaccess.thecvf.com/content_cvpr_2017/papers/Chollet_Xception_Deep_Learning_CVPR_2017_paper.pdf) - Paper on Xception


## Acknowledgments

This project was carried out for learning purpose in Keras and CNN.
