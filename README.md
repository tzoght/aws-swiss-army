# aws-swiss-army


## Getting Started
This is a collection of AWS examples and samples to make the life of developers a bit easier


### Using Jupyter collections
These samples use Jupyter so to get started you must have Jupyter installed (https://jupyter.org/install)
```
$ cd JupyterSamples
$ jupyter notepbook
```
Then navigate to the sample you like to run



### References
https://jupyter-docker-stacks.readthedocs.io/en/latest/using/running.html#

https://mybinder.org/

https://boto3.amazonaws.com/v1/documentation/api/latest/index.html

https://boto3.amazonaws.com/v1/documentation/api/latest/guide/configuration.html


### Tips

If you have Docker already installed
```
$docker run -v "$PWD":/home/jovyan/work -p 8888:8888 jupyter/scipy-notebook:2c80cf3537ca
```
