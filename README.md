# Transfer Learning to Recognize Letters via the Webcam
INSTRUCTIONS:

1. Open up [the demo](https://johnhmejia.github.io/lettertranslate/)

2. Wait for the mobilenet model to load; if it doesn't within a minute or so, make sure you're using chrome and have a webcam.

3. Add examples of letters by clicking and holding on the buttons that say "Add Sample". An image of your most recent sample should show on the button.

4. Once you have enough examples (100 of each should do), click train model.

5. Wait for the model to finish training; then press start! The program should highlight the letter it thinks you're signing.



[Learn more](https://acehernandez.github.io/2xxtemplate/)



This example shows you how to predict letters from a webcam using transfer learning.

This example is deploying a pretrained [MobileNet](https://github.com/tensorflow/tfjs-examples/tree/master/mobilenet) model and training another model using an internal mobilenet activation to predict different letters from the webcam defined by the user.

[See this example live!](https://johnhmejia.github.io/lettertranslate/)

This is a Pure Javascript implementation of: https://github.com/tensorflow/tfjs-examples/tree/master/webcam-transfer-learning. Thank you [TensorFlow.js](https://js.tensorflow.org) for your flexible and intuitive APIs.





[Check out more about me](https://johnhmejia.github.io/)
