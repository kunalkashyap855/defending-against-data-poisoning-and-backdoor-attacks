# ECE-GY 9163 Machine Learning for Cyber Security Project: defending-against-data-poisoning-and-backdoor-attacks

We will use a combination of various methods - STRIP: A Defence Against Trojan Attacks on Deep Neural Networks and Fine-Pruning: Defending Against Backdooring Attacks on Deep Neural Networks. The combination of these methods helps us provide a proper structure in which we can defend our model against targeted and untargeted trojan attacks. 
<br>  
Fine Pruning is a combination of two methods : Pruning and Fine Tuning. Pruning: In pruning, we identify the neurons with the least activations on the valid dataset, i.e. the neurons that remain dormant on clean data. The underlying idea being that these neurons may be fired on backdoored input. We will define a threshold for the weights to be pruned. 
<br>  
When Fine Tuning, we will retrain our DNN with clean inputs instead of training our network from scratch. We hope to train using the same pre-trained weights of the DNN with a lower running rate.

## Submitted by:
- Kunal Kashyap (kk4564)
- Mukta Maheshwari (mm11070)
- Neelanchal Gahalot (ng2436)
