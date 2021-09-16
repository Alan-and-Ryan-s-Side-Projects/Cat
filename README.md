# Cat

YOU NEED TO WAIT AROUND 15 SECONDS BEFORE LOADING FILE.<br />


Is that a cat? Wonder no more, on Cat™ we let you know.<br />

Goal:<br />
Use the model to classify images uploaded to website as either 'dog' or 'cat'.<br />

Used python to train EfficientNet B0 that classifies cat and dog images.<br />
The weights of B0 have already been trained on imageNet, two layers of custom fully connected layers were added. <br />
Next, applied tensorflowjs_converter to convert tensorflow model to a tfjs model.<br />
Finally, loaded the model, when an image is uploaded the model will automatically classify the image.<br />
