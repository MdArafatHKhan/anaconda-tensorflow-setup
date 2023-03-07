# Tensorflow environment for deep learning model building


## Install Anaconda

See your machine specification
```
lsb_release -a
```
This will give you some output like the following,
```
Distributor ID: Ubuntu
Description:    Ubuntu 20.04.4 LTS
Release:        20.04
Codename:       focal
```

Go to the <a href='https://www.anaconda.com/'>anaconda website</a> and download anaconda for linux.

This downloaded `Anaconda3-2022.10-Linux-x86_64.sh`. Go to the folder where you downloaded the anaconda and type the following,

```
chmod +x Anaconda3-2022.10-Linux-x86_64.sh
```
Now type the following to start installation
```
./Anaconda3-2022.10-Linux-x86_64.sh
```
Then follow the instructions until it finishes.

Once anaconda is installed close the terminal and reopen again. You should see the base environment.

There is a nice <a href='https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf'>cheet sheet</a> for using anaconda.

You may also want to update conda,
```
conda update conda
```

## Create conda environment
Create a new conda environment named `tf` with the following command.
```
conda create --name tf python
```
You can activate it with the following commands.
```
conda activate tf
```
## GPU Setup and tensorflow installation
Follow <a href='https://www.tensorflow.org/install/pip'>this link</a>.




















