#sectoin2

## Node

Javascript runtime used to execute code outside of the browser

## Expess

Library that runs in the Node runtime. Has helpers to make dealing with HTTP traffic easier.

## Deploy to Heroku

1. Dynamic PORT Binding

Heroku tells us which port our app will use, so we need to make sure we listen to the port they tell us to

2. Specify Node Environment

We want to use a specific version of node , so we need to tell Heroku which version we want

3. Specify start script

Instruct Heroku what command to run to start our service running

4. Create .gitignore file

We don't want to include dependencies, Heroku will do that for us
