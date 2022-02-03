# How to create a Slack Bot with Bolt, Flask, and Heroku

I built a Slack bot to track Wordle scores using Flask, with a Google Firebase database, and hosted it for free on Heroku.

Here, in part 1, you'll learn how to set up a Flask project from scratch, use the Slack Bolt framework to set up a Slack Bot, track all your changes with git, and use ngrok to develop locally.

## Tutorial Overview


## Tutorial Start

- Set up a flask project

## Creating a new Flask project

### Initialize a new project directory

I created a new folder and named it `slack-bot`.

```
mkdir slack-bot
cd slack-bot
```
Next, let's initialize a git repository in our project to keep track of changes. **This will be required when hosting our project on heroku.**
```
git init
```

### Use a Python virtual environment
Activating a python virtual environment is *not* required, but **highly recommended** in order to keep all your installed libraries isolated so they don't cause conflicts wwith other libraries.
```
python3 -m venv venv
source venv/bin/activate
```
### Now we can use `pip` to install `Flask`
```
pip3 install Flask
```


- Set up a new app on Slack
- Use ngrok to enable local development