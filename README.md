# Creating a Custom Rasa Conversational AI Chatbot for Drupal Websites

## Presented Remotely at Drupal Camp Asheville
## July 9, 2022 

This repository contains the slide deck used for the presentation, the necessary files for creating a Rasa Conversational Drupal Chatbot, and the files for a custom Component AI Chatbot Module.

## Rasa Conversational AI Chatbot
### Installing Rasa
These instructions for installing Rasa are for Ubuntu - for Windows or Mac, go to the [Rasa Learning Center - Installation](https://learning.rasa.com/installation/)

```
$ sudo apt update
Install python3
$ sudo apt install python3-dev python3
$ sudo apt install python3-venv
$ mkdir Rasa
$ cd Rasa
Create virtual environment
$ python3 -m venv ./venv
Activate venv environment
$ source ./venv/bin/activate
Install Rasa and Upgrade pip
(venv)$ python -m pip install --upgrade pip rasa
# downgrade protobut to 3.20.* to avoid error
(venv)$ python -m pip install protobuf==3.20.*
```

### Creating Drupal Knowledge Base


### Training 


### Running 


## Drupal
### Custom AI Chatbot Component Module

### Connecting Drupal to Rasa