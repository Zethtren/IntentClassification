# As requested the necessary content is included in the IntentClassification.ipynb 


I will fill the rest of this page out after training and packaging the result.

Plans for this include improving the training on the model.

Re-training it against the entire dataset including OOS files. Neural networks thrive on large datasets.

After retraing I will wrap this in a Docker container using Flask and push it to my docker hub. 

The final Dockerized product will accept a string as a RestAPI request and post a JSON object back with the prediction for easy integration into a web-app.