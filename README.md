## Wang Bioinformatics Lab Data Science Template

Here we are able to launch a notebook inside of docker with all the dependencies you would want. 

### Customizing Docker for you

1. Update dependencies - change the requirements.txt
1. Update your password - create an .env file with LOGINPASSWORD=YOUR_PASSWORD or else it will not be available
1. Update the port for the server - change port 9000 to something around 9000, but not 9000 in docker-compose.yml or docker-compose-coder.yml
1. Change the name of the container - change wanglab-jupyter in docker-compose.yml or docker-compose-coder.yml

### Launching the Jupyter Notebook

make jupyter-compose

### Launching Coder

make coder-compose

### Layout

All your code for notebooks will go in src. 

All the data you'll want to work with will go into data.

Additional documentation will go into docs. 

### Best Practices

Commit and save changes often and push to github. 

### Launching in MyBinder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Wang-Bioinformatics-Lab/CMMC-GNPS-Integration-Notebook/HEAD?labpath=src%2Fjupyternotebook.ipynb)
