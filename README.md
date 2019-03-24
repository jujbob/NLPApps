# NLPApps

This is a repository for NLP applications with examples


## Dependencies

This is the list of packages that required to run the codes.

 * Anaconda
 * Python 3.7 interpreter
 * Pytorch 1.0.1
 
## Install dependencies

#### Install Anaconda
 * MacOS, Linux
 ```
   wget https://repo.anaconda.com/archive/Anaconda3-5.2.0-Linux-x86_64.sh
   sh Anaconda3-5.2.0-Linux-x86_64.sh
 ```
 
 * Windows
   - Please refer to https://docs.anaconda.com/anaconda/install/windows/

#### Create a virtual environment
Get to your console or command window and type belows:
  ```
   conda create -n NLPApps python=3.7 anaconda
   conda activate NLPApps
  ```

#### Install Pytorch
 * Windows, Linux
  ```
   conda install pytorch-cpu torchvision-cpu -c pytorch
  ```
 * MacOS
  ```
   conda install pytorch torchvision -c pytorch
  ```
  
#### Install Visdom
 * Windows, Linux
  ```
   pip install visdom
  ```

#### Download codes
 * Download
    - https://github.com/jujbob/NLPApps/archive/master.zip

 * Git clone
  ```
   git clone https://github.com/jujbob/NLPApps.git
  ```

#### Run Jupyter notebook
  ```
   jupyter notebook
  ```
  
#### Run Visdom for visualizing graphs
  ```
   conda activate NLPApps
   python -m visdom.server
  ```
    
#### How to convert .ipynb to .py
  ```
   jupyter nbconvert --to=python [file_name.ipynb]
  ```

## dataset
https://docs.google.com/spreadsheets/d/121lCucS8fYgmrOiT14-8_OxDa9bUfaPQRd9e8XEFJqk/edit?usp=sharing

## Survey
https://goo.gl/Mzp9ur

## Contact

If you have any questions or suggestions, please send an email jujbob@gmail.com

