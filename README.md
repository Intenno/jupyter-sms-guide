# Twilio Programmable SMS and Voice Getting Started Guide

This repository contains three step-by-step Jupyter Notebook guides to getting started with Twilio. The  *Twilio Basic Setup Guide* will walk you through how to use your Twilio account credentials to purchase a number. The *Twilio Programmable SMS Guide* will walk you through how to send a message from your Twilio account number, and the *Twilio Programmable Voice Guide* will walk you through making a call from your Twilio account number.

## How To

In order to use these notebooks, you need to create a twilio account.
Then, clone this repository and create info.py file with your account info in the same directory. It should look like this:
```
accountSID = 'xxxxx'
authToken = 'xxxxx'
personalNum = '+11234567890'
```

Next, open a terminal window and navigate to the directory with the cloned repository. 

You will need to create a virtual environment with the following command:

```
virtualenv env
```

This will name your virtual environment "env", but you can name it what you please.

Next, activate your environment with this command:

```
source env/bin/activate
```
You will then need to install the requirements in the *requirements.txt* file by running:

```
pip3 install -r requirements.txt
```
Then you can open the notebooks by running:

```
jupyter notebook
```

Then you're all set. Enjoy sending messages.
