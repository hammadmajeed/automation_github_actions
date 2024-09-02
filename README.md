create virtual environment using 
`python -m venv .venv`

source this environment
`source .venv/bin/activate`

install all the dependencies
`pip install -r requirements.txt`

Test the application
`pytest test.py`

Setup remote github repo (which is already created in the classroom)

Add remote 
`git remote add origin <REPO-URL>`

Define Branch to use 
`git branch -M main`

Push the local changes to the remote 
`git push --setup-stream origin main` 

Added a new mod operation for further merging into the main branch
