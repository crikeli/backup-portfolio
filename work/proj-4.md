---
title: Deep Learning for Urban Aerial Views
---

##### Deep Learning is a field I am very interested in because of the potential of meaningful impact involved. I undertook this project and used TensorFlow to classify aerial views of images using [Transfer Learning](http://cs231n.github.io/transfer-learning/){:target="_blank"}, which is a subfield of Deep-Learning.

The purpose of the project was to understand the workings and power of Google's [Inception Model](https://research.googleblog.com/2016/03/train-your-own-image-classifier-with.html){:target="_blank"} whilst applying it to solve a real-world classification problem. Below, I discuss my methodology and results.

##### Step 1: Training the inception model on a dataset I prepared consisting on aerial pictures of 4 major US cities.

##### Seattle
![Deep Learning for Urban Aerial Views]({{ site.github.url }}/assets/img/work/proj-4/img10.jpg)

##### San-Francisco
![Deep Learning for Urban Aerial Views]({{ site.github.url }}/assets/img/work/proj-4/img9.jpg)

##### New-York
![Deep Learning for Urban Aerial Views]({{ site.github.url }}/assets/img/work/proj-4/img8.jpg)

##### Chicago
![Deep Learning for Urban Aerial Views]({{ site.github.url }}/assets/img/work/proj-4/img7.jpg)


##### Step 2: After training the model with novel images , I obtained a test data accuracy of 56.4%
![Deep Learning for Urban Aerial Views]({{ site.github.url }}/assets/img/work/proj-4/img1.jpg)

##### Upon feeding brand new test images of each city to the network, the network predicted the correct city 3 out of 4 times. (You cannot imagine my excitement!)

##### The network predicted Seattle incorrectly (~ 14.5% confidence)
![Deep Learning for Urban Aerial Views]({{ site.github.url }}/assets/img/work/proj-4/img3.jpg)

##### The network predicted San-Francisco correctly (~91% confidence)
![Deep Learning for Urban Aerial Views]({{ site.github.url }}/assets/img/work/proj-4/img4.jpg)

##### The network predicted New-York correctly (~88% confidence)
![Deep Learning for Urban Aerial Views]({{ site.github.url }}/assets/img/work/proj-4/img5.jpg)

##### The network predicted Chicago correctly (~93% confidence)
![Deep Learning for Urban Aerial Views]({{ site.github.url }}/assets/img/work/proj-4/img6.jpg)


##### Step 3: Retrieved raw results.
![Deep Learning for Urban Aerial Views]({{ site.github.url }}/assets/img/work/proj-4/img2.jpg)

<a href="https://github.com/crikeli/aerialView_Image_Classifier" class="icon-github" style="font-size:22px" target="_blank"> Code </a>
