
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b5/Kickstarter_logo.svg/1280px-Kickstarter_logo.svg.png" height="100">

# Campaign Success Predictor
Predictive modeling applying the entire data science lifecycle on basis of a fictious scenario: We are tasked by Kickstarter to come up with a model to predict in a first step whether a campaign is likely to be successful, given certain project parameters. In a second step (out-of-scope), Kickstarter would like to be able to provide a good goal recommendation for project creators (particularly as Kickstarter can influence certain parameters such as staff picks):

Given certain project parameters, is a campaign likely to succeed or fail (classification)?
What would be a reasonable goal recommendation for project creators (regression, out-of-scope)?
F1-Score was selected as the target metric to optimize prediction of state (successful/failed) on.


# Outcome







# Setup
* pyenv local 3.9.4
* python -m venv .venv
* source .venv/bin/activate
* pip install --upgrade pip
* pip install -r requirements.txt
