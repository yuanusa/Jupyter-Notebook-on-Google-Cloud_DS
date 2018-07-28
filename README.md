# Jupyter-Notebook-on-Google-Cloud_DS

datalab create --machine-type n1-standard-8 driven













Jupyter+GoogleCloud+DS

https://towardsdatascience.com/running-jupyter-notebook-in-google-cloud-platform-in-15-min-61e16da34d52


ssh-keygen -t rsa -f ~/.gc_rsa -C 
cd ~/.ssh
vi #sshkey.pub


wget http://repo.continuum.io/archive/Anaconda3-4.0.0-Linux-x86_64.sh



bash Anaconda3-4.0.0-Linux-x86_64.sh

source ~/.bashrc

pip install tensorflow

pip install keras

jupyter notebook --generate-config

ls ~/.jupyter/jupyter_notebook_config.py

jupyter notebook --generate-config





sudo apt-get update
sudo apt-get --assume-yes upgrade
sudo apt-get --assume-yes install software-properties-common
sudo apt-get --assume-yes install python-setuptools python-dev build-essential
#sudo easy_install pip
#sudo pip install jupyter
jupyter notebook --generate-config

sudo nano ~/.jupyter/jupyter_notebook_config.py

c = get_config()
c.NotebookApp.ip = '*'
c.NotebookApp.open_browser = False
c.NotebookApp.port = <Port Number>
