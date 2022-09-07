# Udacity Deep Learning Nanodegree - Project 3: TV Script Generation
RNN TV script generation model with LSTM and Word2Vec components. Project 3 of Udacity's Deep Learning Nanodegree

Original repository: https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-tv-script-generation


### Introduction
In this project, you willll generate your own [Seinfeld](https://en.wikipedia.org/wiki/Seinfeld) TV scripts using RNNs.  You'll be using part of the [Seinfeld dataset](https://www.kaggle.com/thec03u5/seinfeld-chronicles#scripts.csv) of scripts from 9 seasons.  The Neural Network you'll build will generate a new ,"fake" TV script, based on patterns it recognizes in this training data.


### Results
Example: 
```
newman: cuttin' survey survey survey dine survey dine cuttin' survey dessicates gardenias survey survey survey dine dessicates gardenias dine dine.

jerry: oh!

jerry: so what are you doing?

george: i can't believe that.

kramer: oh, well, it's all a way.

newman: you don't have any money, george.

george: no!

jerry: well, it's just a lot of people to do.

elaine: oh, well, i think i can have the money back.

george:(to kramer) hey, hey.

george: i think i could be in the bathroom.

jerry:(to kramer) well, i was thinking, i was wondering, i was wondering.

george:(to jerry) i don't know..

elaine: oh, you don't understand? i don't want you infecting this?

jerry: yeah, yeah.

george:(to elaine and elaine) what is this?

george: what is this?

jerry: yeah?

kramer: well, you know what i said to him, the best part of the life is the only one i ever had. i was thinking i was going to get a pair of a few of my life, but i have to tell you what i think, you know, it's a good story.

jerry: oh, yeah, yeah, that's right.

jerry:(to george) hey, i gotta go.

kramer: oh, i can't get it.

elaine: what? what are you talking about?

george: i don't know. i was just curious.

george: you can't believe that i was gonna do it in my office.

kramer: oh...(to the intercom) oh... oh yeah, i don't want to see the guy.

george: i think that's the point, you know, you know i think that you don't have to do it, so i think you're not going to be here
```

As you can see, much of the generated script is utter nonsense when trying to determine context; however, much of the sentences (taken singularly) are grammatically correct and even have some manerisms of the characters.
