![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Welcome,

This is the Code Institute student template for deploying your third portfolio project, the Python command-line project. The last update to this file was: **May 14, 2024**

## Reminders

- Your code must be placed in the `run.py` file
- Your dependencies must be placed in the `requirements.txt` file
- Do not edit any of the other files or your code may not deploy properly

## Creating the Heroku app

When you create the app, you will need to add two buildpacks from the _Settings_ tab. The ordering is as follows:

1. `heroku/python`
2. `heroku/nodejs`

You must then create a _Config Var_ called `PORT`. Set this to `8000`

If you have credentials, such as in the Love Sandwiches project, you must create another _Config Var_ called `CREDS` and paste the JSON into the value field.

Connect your GitHub repository and deploy as normal.

## Constraints

The deployment terminal is set to 80 columns by 24 rows. That means that each line of text needs to be 80 characters or less otherwise it will be wrapped onto a second line.


felipenastloyola@Felipes-MacBook-Air love-sandwiches % git clone https://github.com/fenasti/love_sandwiches.git
Cloning into 'love_sandwiches'...
remote: Enumerating objects: 15, done.
remote: Counting objects: 100% (15/15), done.
remote: Compressing objects: 100% (11/11), done.
remote: Total 15 (delta 0), reused 10 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (15/15), 5.21 KiB | 2.60 MiB/s, done.
felipenastloyola@Felipes-MacBook-Air love-sandwiches % python3 --version
Python 3.9.6
felipenastloyola@Felipes-MacBook-Air love-sandwiches % python --version
zsh: command not found: python
felipenastloyola@Felipes-MacBook-Air love-sandwiches % python3 --version
Python 3.9.6
felipenastloyola@Felipes-MacBook-Air love-sandwiches % python3.12 --version
Python 3.12.10
felipenastloyola@Felipes-MacBook-Air love-sandwiches % python3.12 -m venv venv
felipenastloyola@Felipes-MacBook-Air love-sandwiches % source venv/bin/activate
((venv) ) felipenastloyola@Felipes-MacBook-Air love-sandwiches % python --version
Python 3.12.10


felipenastloyola@Felipes-MacBook-Air love-sandwiches % python3.12 --version
Python 3.12.10
felipenastloyola@Felipes-MacBook-Air love-sandwiches % python3.12 -m venv venv
felipenastloyola@Felipes-MacBook-Air love-sandwiches % source venv/bin/activate
((venv) ) felipenastloyola@Felipes-MacBook-Air love-sandwiches % python --version
Python 3.12.10
((venv) ) felipenastloyola@Felipes-MacBook-Air love-sandwiches % rm -rf /Users/felipenastloyola/love-sandwiches/venv 
((venv) ) felipenastloyola@Felipes-MacBook-Air love-sandwiches % python3.12 -m venv venv
((venv) ) felipenastloyola@Felipes-MacBook-Air love-sandwiches % python3 --version
Python 3.12.10
((venv) ) felipenastloyola@Felipes-MacBook-Air love-sandwiches % source venv/bin/activate
((venv) ) felipenastloyola@Felipes-MacBook-Air love-sandwiches % pwd
/Users/felipenastloyola/love-sandwiches


