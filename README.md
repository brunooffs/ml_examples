# ml_examples
Machine learning and AI experiments

Install Jupyter Notebook: https://jupyter.org/install


In order to run this experiment you should have python3 installed and the version should be 3.6 < 3.11, 
if you are using a different version you should consider installing pyenv: https://github.com/pyenv/pyenv 

For this example i'm using python 3.10 , for example if you don't have a proper version installed run the following on your terminal: 

$ pyenv install 3.10 
$ pyenv global 3.10 
$ eval "$(pyenv init --path)" 

Check if the correct version is installed: 

$ python3 --version


Instructions: 

Create a virtual environment using venv: https://docs.python.org/3/library/venv.html on on your terminal run: 

$ python -m venv my_env 
$ source my_env/bin/activate 

Once your <venv> is activated make sure it's running the correct python version: 
(my_env)$ pyenv global 3.10 

Install all the requirements from the requirements.txt:
(my_env)$ pip3 install -r requirements.txt 

Run jupyter notebook: 

(my_env)$ jupyter notebook
