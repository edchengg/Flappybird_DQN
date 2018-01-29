# Flappy Bird AI

Date: 1/29/2018

## Project Description

[Flappy Bird](https://en.wikipedia.org/wiki/Flappy_bird) is a very popular video game. In this project, I advanced Lei Mao's work by adding a Deep Dueling Q Network into the program. The new algorithm is developed to accelerate the learnig process.

![](flappy_bird_AI.gif)


## Run AI in Flappy Bird

The AI needs to be trained before the game. To train the AI with dueling Q, run the command:
```shell
python FlappyBird_AI.py -m train -n dueling_Q
```

The AI has already been trained and stored as AI_model.h5 file if you do not want to do the training.

In case of a break during the training, one can resume the training by running the command:
```shell
python FlappyBird_AI.py -m resume
```

To allow the trained AI to play the game, run the command:
```shell
python FlappyBird_AI.py -m test
```


## Disclaimer

This work was developed based on the project published on GitHub by Lei Mao:

<https://github.com/leimao/Flappy_Bird_AI>
