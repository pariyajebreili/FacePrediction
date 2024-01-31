# FacePrediction
The goal of this project is to recognize faces in different lightings, and the images were all length and width equal. The length and width of all images were equal to 160x160. 10 different people were photographed and each person was photographed in 64 different lighting conditions. The database in this project was YaleB. Based on the lighting angle, the images were divided into 5 subcategories.
subset_numbers = {
    'I': [1, 7, 8, 9, 36, 37],
    'II': [2, 5, 10, 11, 12, 13, 15, 39, 40, 41, 42, 44],
    'III': [3, 6, 14, 16, 17, 19, 20, 43, 45, 46, 48, 49],
    'IV': [18, 21, 22, 23, 24, 25, 26, 47, 50, 51, 52, 53, 54, 55, 38],
    'V': [4, 27, 28, 29, 30, 31, 32, 33, 34, 35, 56, 57, 58, 59, 60, 61, 62, 63, 64, 65]
}

In this project, we had to choose two people and set aside the images that were in subset 2 as a test dataset and give the rest of the subsets as a training dataset to the neural network.
The purpose is to find the training losses plot over 100 epochs. The second one is to find the accuracy and F1 metrics.