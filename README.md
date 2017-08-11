# Emotion-Music
MCMC hackathon 2017

We will use convolutional neural network to detect emotion using any live webcam, but this hackathon, we just demo on external webcam. [TRAIN USING THIS DATASET](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)

## Old dataset, we not used it anymore
![alt text](bar-emotion.png)
```text
anger: 76
happy: 76
jealous: 84
sad: 55
```
![alt text](bar-person.png)
```text
Husein: 157
Julius: 181
Ugen: 149
unknown: 192

```

## training session
![alt text](plotemotion.png)
Pretty much overfitted, 60% achieve during validation
![alt text](plotperson.png)
fine enough for hackathon!

## model architecture
![alt text](model.png)

0.5. Unzip *.zip from data/, dataperson/ in the same directories. You can add new pictures or remove some.
1. You able to capture new face using capture.py
2. You need to train person detection using train_person.py
3. You able to train the emotion using train_emotion.py
4. to test on live any camera, use live.py
