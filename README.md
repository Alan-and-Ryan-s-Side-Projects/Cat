# Cat

YOU NEED TO WAIT AROUND 15 SECONDS BEFORE LOADING FILE.<br />


Is that a cat? Wonder no more, on Cat™ we let you know.<br />

Goal:<br />
Use the model to classify images uploaded to website as either 'dog' or 'cat'.<br />

First, used python to train a model that classifies cat and dog images.<br />
Used transfer learning from VGG16 CNN, then added 2 fully connected layers.<br />
Next, applied tensorflowjs_converter to convert tensorflow model to JSON model.<br />
I then uploaded this model to be hosted at https://github.com/Pofv/fileHost<br />
Finally, load the model, get an image to be uploaded and the model will classify the image.<br />

It appears that the main weakness of this model is that it tends to classify dogs with pointy ears as cats. That being said I've only trained the model for 1 epoch, which took a whopping 5 hours. I will eventually use data augmentation and improve the model. <br/>
