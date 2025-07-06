This is a relatively older project (from 2022) that I made for the WPI Frontiers Summer Program ECE course. It is on here for archive purposes

# DeCaptcha

The purpose of this project was to train and develop an Convolutional Neural Network (CNN) AI model to accurately solve [CAPTCHAs](https://en.wikipedia.org/wiki/CAPTCHA) (Completely Automated Public Turing test to tell Computers and Humans Apart)

Specifically, the main type of captcha that this model is designed to solve are reCaptcha V1s, which look something like the following.

![Image of a reCaptcha V1 with text smwm](https://upload.wikimedia.org/wikipedia/commons/6/69/Captcha.jpg)

The dataset used to train the images comes from [Wilhelmy, Rodrigo & Rosas, Horacio. (2013). Captcha Dataset.](https://www.researchgate.net/publication/248380891_captcha_dataset)

The latest model ended up with a 6% error rate, which I was satisfied with.

To test the program, follow `Decaptcha.ipynb`, disregarding the "debug" section at the top.
