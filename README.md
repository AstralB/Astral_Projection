# Astral_Projection
Fine-tuned networks to use with Deep Dream that produce interesting results.
---
I have been finetuning networks, mainly Googlenet and have had some interesting results. I thought it would be a good idea to upload the resulting image along with the files needed in case one wanted to finetune and, more or less, replicate the results.

Each of these folders contain the following:
    #the original and deepdreamed image
    #weights (.Caffemodel) used for the finetuning 
    #solver.prototxt
    #train_val.prototxt
    #deploy.protoxt
    #lmdb containing the imageset used
    #text file with information on the imageset
    #text file with the deepdream parameters used
    #subfolder containing results of the finetuning (just the loss at each of the iterations for now, will try to plot graphs in the future)
    
    
