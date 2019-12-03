# Peptide-Generation-Through-GAN
This is a project about generating a peptide library using Generative Model. 

  week1: learning
  
  https://github.com/jeffheaton/t81_558_deep_learning is good for GAN 
	0. what generative model we can use?
	1. example the GAN. or other G model.
	
  this is good one: https://towardsdatascience.com/gan-by-example-using-keras-on-tensorflow-backend-1a6d515a60d0
  <br>
  1. theory and background material. : update later<br>
  2. decide package : keras Auxiliary Classifier GAN (ACGAN) <br>
  3. problems : no
  3. next week plan 
  	
  
  week2: 
  
  1. preprocessing data.
  	dataset: https://hla-ligand-atlas.org/welcome 
  	encoding method: 
	
  2. building model 
  	building generator 
	how many classes in this model. maybe only 2
	
  questions:<br>
  	1. Can the accuracy be less than 50% when trainning the generator? What does it mean?<br>
	2. What is the process of backpropagation of generator trainning? How does it only update generator weights?<br>
		Prerequistic:https://medium.com/@karpathy/yes-you-should-understand-backprop-e2f06eab496b-good article
	3. Wasserstein Loss is better than Minimax Loss. https://developers.google.com/machine-learning/gan/loss <br>
		So maybe something can be done for the loss function. The purpose is to get the distance. (WGAN vs. TFGAN)
	4. 
	
	
  Sample Code:
  https://github.com/channel-learnings/Basic-GAN/blob/master/GAN%20on%20mnist.ipynb
  https://towardsdatascience.com/gan-by-example-using-keras-on-tensorflow-backend-1a6d515a60d0
  
  <br>
  week3:
  
 
  
  1. modifying model
  2. evaluating the performance
  	
  	need some background knowledge about peptide when evaluation
 We can use the following notebook to run our program. Then we can use their GPU.<br>
 https://colab.research.google.com/drive/1iiQRtdOwzkKEJ2MitEiBmzy-mc1RCV7m
 
 Code to upload the tsv file into colab and parsing tsv file
 https://colab.research.google.com/drive/1npJiC78Msa17JJ7EMijTuH4SqmU-ZKRQ#scrollTo=OAuJoVpgENDV
  
  week4:
  
  1. writing report and paper
  
  week5:
  
  1. presentation
  
