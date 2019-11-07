# TensorFlow Lite image classification on retrained mobilenet model

This is a modified version of the example iOS Tensorflow application taken from:
https://github.com/tensorflow/examples/tree/master/lite/examples/image_classification/ios


The app uses the phones back camera to continuously classify what it sees based on the provided model.


Model Used: mobilenet_v2_100_224 - Currently retrained to output three labels: ['car', 'not_car', 'odometer']

Requires 'TensorFlowLiteSwift'
