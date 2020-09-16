# Cat

WARNING: FOR THE CURRENT VERSION OF THE WEBSITE, YOU NEED TO WAIT 15 SECONDS BEFORE LOADING FILE.

Is that a cat? Wonder no more, on Cat™ we let you know.

Goal:
Use the model to classify images uploaded to website as either 'dog' or 'cat'.

First, used python to train a model that classifies cat and dog images.

Used transfer learning from VGG16 CNN, then added 2 fully connected layers.

Next, applied tensorflowjs_converter to convert tensorflow model to JSON model.

I then uploaded this model to be hosted at https://github.com/Pofv/fileHost

Finally, load the model, get an image to be uploaded and the model will classify the image.

