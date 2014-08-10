For development setup, I first clone the repo like so:

git clone git@gethub.com:linguistech/flask-proj.git

This builds the basic directory structure. I then build a virtualenv around that like so:

virtualenv flask-proj

Now I can cd into my project directory and activate the virtualenv. The comands I use are as follows:

cd flask-proj
source ./bin/activate

With the virtualenv activated, I can now install my requirements with the following command:

pip install -r requirements.txt

As an aside, I create the requirements.txt file with the following command:

pip freeze > requirements.txt

The virtualenv directories to put in your .gitignore file are:

bin
include
lib

