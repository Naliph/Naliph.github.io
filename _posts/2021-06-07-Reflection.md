---
layout: post
title: PIC16B Project Reflection
---



This is a reflection for the main group project for PIC16B course: **Colorization of Black and White Images - [Alice Pham](https://naliph.github.io/), [Duc Vu](https://tducvu.github.io/)**

![demo.gif](/images/demo.gif)


# Project Overview:
`Colorization` has a variety of applications in recreational and historical contexts. It transforms how we see and perceive photos which provide immense value in helping us visualize and convey stories, emotions, and history. This project was implemented with deep learning models to train and colorize grayscale images. Overall, our project was prepared and trained on approximately 10,000 images; specifically, using a convolutional neural network combined with a classifier deployed through `TensorFlow` and `Keras`. For more details of the project, check out our [project's github](https://github.com/tducvu/PIC16B-project).


## Reflection
* We **achieve in our project** a local interactive app that hosted the model to colorize Black & White images. Users can download the repository and follow the instruction to open the app. We incorporated 2 methods to test the app: use their picture of any size, or use our tester images. 


* **Aspects that I am especially proud** of in this project is that even though with limited resources regarding data and computational power, we still managed to perform a quite satisfying colorized image output. We had countless trials and errors and sleepless nights to keep train and refine the model (sometimes, we wait for hours just for an error of not enough ram or weird colorization at the end). The second is that although we use the help from other researchers and published articles, the amount of research and times we spend to understand, refined, and tune the model to get some acceptable results is INTENSIVE.

* **Things that we suggest doing to further improve the project** is that to train the model again on a much stronger GPU and larger ram capacity computer, and to learn about optimizing the model for deploying the local app (we cannot achieve this last step due to complication of too long runtime and large application size); as mentioned, the long runtime is a huge problem, not only for the deploying, for a normal computer like us, it took more than a couple of minutes to finish colorize 1 picture, hence, we suggest more research to minimize the execution time.

* Our achievement is not as we expected in the initial proposal. We were being ambitious and suggest training on 500,000 to 1,000,000 images with an unbiased, designated colorization model. However, along the way, we learned about computing power, time, and resources to fulfill our initial proposal is insanely impossible for us at this time. Aside from that, the colorization results are not as accurate and colorful as we expected them to be, although it shows some good colorization for distinct features like face or object, for multi-color scenery, the model does very randomly. But with just this much knowledge and resources, I would say both of us are very proud of what we achieved in the final project.


* Throughout this project, I **learned** to perform convolutional neural network in combine with a classifier to colorize grayscale images (learn by the most painful way possible, trials and errors for hours and hours); to use web scraping to download images from websites (although we did not implement this in the project due to its complications regarding sizes, time, and CPU); to use GitHub collaborator; and to create a custom static web app (although Heroku deployment is not very successful, we managed to output a good looking interface [here](https://colorizing-pic16b.herokuapp.com/), which is also how our streamlit local app look like). 


* Honestly, I'm a biochemistry student whose original wish is to find myself in a laboratory and do some crazy chemistry experiment. However, this course overall (and PIC16A) and this project has open my scope and interest to incorporate data science into my Biochemistry/life science passion. I probably won't focus my interest on Computer vision, but the data analytics part and all the deep learning knowledge fun stuff. I don't know how specific I should be about my future since I am currently searching for a data analytics position within the pharmaceutical/life science industries (Hope to gain some deeper practical experiences regarding data science, then move on to grad school, whether if it's Data Science or Biochem depends on how I feel when actually work on it). 

