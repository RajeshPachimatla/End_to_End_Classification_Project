# End_to_End_Classification_Project

This project is about Image classification and identifying indian celebrity image using a trained model. A wed page is developed where one can drop the image and see the result. A Support vector machine (SVM) model has been developed and deployed in a webpage of html/css/javascript which can do image classification.

DataFrame of the project as follows:

Creat a Dataset folder with differents images, here I selected five Indian celebrities from differen fields like Deepkia Padukone (Actress), KL Rahul (cricketer), Mahesh Babu (actor), A R Rehman (Music director), Shriya Ghoshal (Singer). 
Data science concepts such data cleaning, image cropping and gridsearch CV has been performed and build a SVM model
After the model is build, it was exported to a pickle file and used a python flask server which can consume this pickle file and do image classification.
This python flask server will expose http ednpoints for various requests and ui returns in html/css/javascript
Following the screen shot of the webpage which I run on the localserver

![CelebrityClassification_deployed](https://github.com/RajeshPachimatla/End_to_End_Classification_Project/assets/138550334/c8839fed-6639-4ce0-9789-dca37dc9baca)
