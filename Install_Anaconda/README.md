

## Download and Install Anaconda Data Mining with Python

### Windows :

1. Download Anaconda from below link :

https://repo.anaconda.com/archive/Anaconda3-5.1.0-Windows-x86_64.exe

2. Follow the link for installation https://medium.com/@GalarnykMichael/install-python-on-windows-anaconda-c63c7c3d1444

(Please select 'Add anaconda to my Path variable option in step 2' so that you don't need to do step 4,5)

3. Type jupyter notebook in windows search box (or anaconda and then jupyter notebook under it) and click on it.


### Linux (Debian based) OS :

Please run below commands one by one on terminal:

1. cd ~
2. wget https://repo.anaconda.com/archive/Anaconda3-5.1.0-Linux-x86_64.sh
3. bash Anaconda3-5.1.0-Linux-x86_64.sh -b -p ~/anaconda
4. rm Anaconda3-5.1.0-Linux-x86_64.sh
5. echo 'export PATH="~/anaconda/bin:$PATH"' >> ~/.bashrc 
6. source .bashrc
7. conda update conda
8. jupyter notebook

### Mac OS :
Please run below commands one by one on terminal:

1. cd ~
2. curl https://repo.continuum.io/archive/Anaconda3-5.1.0-MacOSX-x86_64.sh -o anaconda3.sh
3. bash anaconda3.sh -b -p ~/anaconda3
4. rm anaconda3.sh
5. echo 'export PATH="~/anaconda3/bin:$PATH"' >> ~/.bash_profile 
6. source .bash_profile
7. conda update conda
8. jupyter notebook
