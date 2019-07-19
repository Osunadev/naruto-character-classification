
# Naruto Character Classification

> This is my final project for the **Artificial Intelligence** course at
> **UABC**.  The topic to be addressed in this final project was a free criterion, that is why I chose a Deep Learning topic.

This project is about implementing Transfer Learning based on a pretrained model **(MobileNet_v1_1.0_224_quantized)** that classifies about 900 images; trained with ImageNet **(a big Image dataset that contains about 16 million images**).

I collected myself about 30 images per naturo character, and only chose 10 different characters due to a time constraint to submit the project.

I used as a template the <a href='https://codelabs.developers.google.com/codelabs/recognize-flowers-with-tensorflow-on-android/#0'>Tensorflow Lite Android Codelab</a>, based on that, I could modify the code and adapt it to my 10 labels to classify **(images)**.

After I created the TensorFlowLite (.tff) model and the text file with the labels, I used the <a href='https://github.com/tensorflow/examples/tree/master/lite/examples/image_classification/android/app/src/main/java/org/tensorflow/lite/examples/classification'>Android example app</a> to use TensorFlowLite models, and I made a little adjustments on it.
