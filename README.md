# Facial-Expresssion-Recognition

### Architecture of VGG16 was used to train model on FER Dataset.
### Pretrained model MobileNet was also given in which through trasfer learning, model was trained on FER dataset. 
### Real time facial emotion recognition can be done by running Test.py which uses model trained on FER.

## STEPS

1) Download fer2013.csv file from kaggle and extract images from csv file.
2) Create two seperate directory for training and validation with each emotion having pariticular directory.
3) To train model as per your choice , tweak code of TrainingVGG16Classifier.py.
4) Run Test.py , which will used already trained model by me to predict emotion in real time.

## Some Captures

![happy](https://user-images.githubusercontent.com/31628501/88474898-96a1c300-cf48-11ea-8bcd-1f244fe5b777.JPG)

![neutral](https://user-images.githubusercontent.com/31628501/88474901-999cb380-cf48-11ea-89e8-f0777358b3b4.JPG)

![surprise](https://user-images.githubusercontent.com/31628501/88474903-9bff0d80-cf48-11ea-998e-32dc68cd6bb1.JPG)
