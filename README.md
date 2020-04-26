# Dog-Breed-Classifier
Given an image of a dog, algorithm identifies its breed using convolution neural networks in PyTorch

The code accepts any user-supplied image as input - it will be resized by `RandomResizedCrop` to 224 by 224 pixels image size. If a dog is detected in the image, it will provide an estimate of the dog's breed. If a human is detected, it will provide an estimate of the dog breed that is most resembling.
