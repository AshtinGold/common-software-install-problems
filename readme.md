# This page is curated to record issues and solutions to common software install problems encountered by the author.

About the author:  
The author is a passionate computer vision / robotics hobbyist. Therefore if you are in the same field you are likely to encounter the same issues.  
Note that this page writes down only very non-task speciifc installation problems.  
Problems pertaining to a single github project will likely not end up here.  

## Syntax
It is important to define every single term or syntax when writing an explanation blog post. Note that these are my preferred notations, and will be certainly different than other tutorials and blogs you read elsewhere.  
<>  this indicates a non-optional argument (word) that must be used. The variable contained within these brackets indicates a string which **you will name by yourself**, and the name which I give is suggestive of what it does, but is not the actual string of letters you (must) put down.   
<< >> this indicates an optional argument.  

## PyTorch
Q: Torch not compiled with CUDA enabled  
A: The  ''Torch not compiled with CUDA enabled'' error is likely to occur when the user does not have CUDA Toolkit installed in their Python environment.

Q: I installed PyTorch on Win11 with Cuda option, but when I verify my installation

## Git
Q: What are the essential commands that allow me to use git with github?  
A: The most basic commands are "add", "commit" and "push". This allows changes in your local directory to be updated in your (online) github repository. 

Q: How does forking work?  
A: 

## Conda (Anaconda)
Q: What are the essential commands in conda that allows me to get started?  
A: In my opinion, these commands are indispensible:  
1. conda create -n <your_env_name>  
2. conda list <<your_module>>  
3. conda env list  
4. conda env remove -n <your_env_name>  
The actual use of each command is easy to understand once you run them. They cost you marginally compute to run, so please run them yourself.

Q: How is 'conda install' different from 'pip install'?  
A: 
