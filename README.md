# Pre-trained_image_classification
Using pre-trained models to detect images.
Since our objective is to only train the custom classifier, we freeze the layers of VGG16

Why do we freeze the layers ?

Layer freezing means layer weights of a trained model are not changed when they are reused in a subsequent downstream task - they remain frozen. Essentially when backprop is done during training these layers weights are untouched.

link: https://www.quora.com/What-is-layer-freezing-in-transfer-learning
