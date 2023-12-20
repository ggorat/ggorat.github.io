---
title: "Beginning with Computer Vision"
excerpt: "Creating a neural network from scratch, then using it with the MNIST data set to learn the basics of computer vision. <br/><img src='/images/MNIST.png'>"
collection: portfolio
---

This post will follow my thought process and learnings while creating a neural network and then running the MNIST data set through it. A few quick disclaimers: <br/>
1. The data set used is publicly available on Kaggle.com. <br/>
2. I decided to start this project after seeing a video on YouTube, by creator, Samson Zhang. Link to video [here](https://www.youtube.com/watch?v=w8yWXqWQYmU&list=LL&index=17&t=580s).<br/>
3. This is my first project centered around AI, and although I have a CS degree a lot of the extensions and features I used throughout this project I had little to no experience with such as Git, crazy I know but never needed it for class 🫠, matplotlib, numpy, or pandas.<br/>
4. All necessary files will be available on my [GitHub](https://github.com/ggorat/miNeuralNetwork).<br/>

To begin, I needed to understand the fundamentals and mathematical approach to designing a neural network. For this project, 3 layers were used... an intial input layer (layer 1), first hidden layer (layer 2), and an output layer (layer 3). Adding more layers to this such as a second hidden layer can increase the accuracy of the model, so that may be something I come back to in the future to try out, but for now, 3 layers it is. Okay, so I now understood the "layout" of the network but how does this correlate to anything I have seen AI do? Answer is: forward proposition, backwards proposition, and updating the weights and biases.<br/>
Continue here***Testing code blocks
https://github.com/ggorat/miNeuralNetwork/blob/2d552c9d5615f450471d7538a3f377e3617da531/miNN.py#L59-L64