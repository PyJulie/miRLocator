# miRLocator
# How To Build The Server
## Configuration

OS:  
* Ubuntu 14.04(not must but at least)  

Ubuntu package:  
* [ViennaRNA V2.0](http://www.tbi.univie.ac.at/software/)  
```
$sudo apt-add-repository ppa:j-4/vienna-rna
$sudo apt-get update
$sudo apt-get install vienna-rna
```
Python package:  
* [Scikit-learn](http://scikit-learn.org/stable/)  
* Scikit-neuralnetwork  
* Numpy  
* Scipy  
* Flask  
* Flask-WTF  

Most Python packages bove could be installed by "pip" directly.  

## Run
```
$git clone https://github.com/PyJulie/miRLocator.git
$cd miRLocator
$sudo python upload.py
```
