# Ant_Bees_classification_Pytorch

## create an environment
First open the terminal and then create a new environment

-------------->>>>>      "$ conda create --name abc python=3"

then activate the new environment -abc

-------------->>>>>      " source activate abc"

 and then type 

------------->>>>>       "conda env list"

check your current environmet that is  asterik is shown before your environment like that

(abc) ankit@ankitG-PC:~$ conda env list

   ### Conda Environments:

abc                   *  /home/ankit/anaconda3/envs/abc

ankit                    /home/ankit/anaconda3/envs/ankit

root                     /home/ankit/anaconda3

and if want to deactivate the environment :

---------------->>>>>    " source deactivate abc"


and 
##  Connect your Specific environment with jupyter kernel and click enter like that:

(abc) ankit@ankitG-PC:~$ python -m ipykernel install --user --name abc --display-name "Python (abc)"

Installed kernelspec abc in /home/ankit/.local/share/jupyter/kernels/abc

and run command in terminal: jupyter notebook ( : if installed)


and install also torch  visiting on pytorch.org 

and select your desired system config

and select if you graphic then add cuda otherwise select none

and copy the command and run on terminal

AFTER THIS OPEN JUPYTER AND SELECT PYTHON ON NEW ENVIRONMENT
AND WRITE THIS PROGRAM


https://pytorch.org/tutorials/beginner/transfer_learning_tutorial.html

https://towardsdatascience.com/transfer-learning-using-pytorch-4c3475f4495       (FOR UNDERSTANDING TUTORIAL ON MEDIUM)



## Important Webpages:

https://cs231n.github.io/transfer-learning/

https://mc.ai/applying-transfer-learning-on-resnet-using-pytorch/

https://pytorch.org/docs/0.3.1/

https://en.wikipedia.org/wiki/PyTorch

https://www.quora.com/topic/PyTorch
