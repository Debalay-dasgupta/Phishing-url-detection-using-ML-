# Phishing-url-detection-using-ML-
Socket based Chat Application with automatic phishing link detector module

Client Side

![image](https://user-images.githubusercontent.com/88347086/175934179-77f5eb59-36a7-4736-a308-9b953a9e31e9.png)

Server Side

![image](https://user-images.githubusercontent.com/88347086/175934262-0e7e6c09-3c3f-4432-a005-a2697b733439.png)

## Comparing Logistic Regression and MultinomialNB

MultinomialNB

![image](https://user-images.githubusercontent.com/88347086/175928356-b3dd76b0-a328-4725-ae34-430fdf7ebe68.png)

Logistic Regression

![image](https://user-images.githubusercontent.com/88347086/175928475-033b4f2e-9ef4-4c9a-ab4f-8ea102c2a611.png)

Dumping the LR model into a pkl file to be integrated in Chat Application

![image](https://user-images.githubusercontent.com/88347086/175928629-c7c35e5b-7db7-4ab2-a20b-16ade9a5766f.png)

## Ensemble Model

Top 2 models

1. Gradient Booster Classifier

![image](https://user-images.githubusercontent.com/88347086/175929377-ca5523e9-0f70-48cf-ab47-77c56501bf62.png)

2. Random Forest Classifier

![image](https://user-images.githubusercontent.com/88347086/175929624-e6e48fca-8a10-4ca2-95fb-bd4612d9f59f.png)



After comparision a combination of Gradient Boost Classifier and Random Forest Classifier is chosen

Expandable Random Gradient Stacked Voting Classifier

![image](https://user-images.githubusercontent.com/88347086/175929681-e3afa4f2-10c3-413e-8920-c78d545646ba.png)









