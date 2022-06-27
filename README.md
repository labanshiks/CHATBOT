# Chatbot Development and Deployment
I created a simple chatbot with Python and PyTorch then deployed it with HTML, CSS, JavaScript and Flask.

# Implementation of the Chatbot in PyTorch.

## Watch the Tutorial
[![Alt text](https://img.youtube.com/vi/RpWeNzfSUHw/hqdefault.jpg)](https://www.youtube.com/watch?v=RpWeNzfSUHw&list=PLqnslRFeH2UrFW4AUgn-eY37qOAWQpJyg)

## Usage
Download the dependancies listed in `requirements.txt`

Run
```console
python train.py
```
This will dump `data.pth` file. And then run
```console
python chat.py
```

## Customize
Have a look at [intents.json](intents.json). You can customize it according to your own use case.
Just define a new `tag`, possible `patterns`, and possible `responses` for the chat bot. You have to re-run the training whenever this file is modified


# How the deployment works:
-The frontend html and javascript files are run completely separate from the Flask App then.
- First run `app.py` to start the Flask app
- Go to the standalone-frontend folder and go live with the `base.html`.

## Note
-The two files should be running simultaneously!!
-Remember to work in a virtual environment.

