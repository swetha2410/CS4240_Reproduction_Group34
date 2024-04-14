# CS4240_Reproduction_Group34
This repository is an attempt to reproduce the paper Prototypical Networks for Few shot Learning in PyTorch written by Jake Snell and Kevin Swersky and Richard S. Zemel. The initial code can be be found following this link: [https://github.com/orobix/Prototypical-Networks-for-Few-shot-Learning-PyTorch/?tab=readme-ov-file](https://github.com/orobix/Prototypical-Networks-for-Few-shot-Learning-PyTorch/?tab=readme-ov-file). The paper can be found using the following link: [https://arxiv.org/abs/1703.05175](https://arxiv.org/abs/1703.05175). We have included the reproduction blog documenting our reproduction process. One of the biggest issues in classification is often the lack of training data to properly classify unseen data, prototypical networks are a way to circumvent this issue.  This is called prototypical networks, they learn a metric space in which classification can be performed by computing distances to prototype representations of each class. In the re-implementation of this paper, 5-way accuracy and 20-way accuracy was used in addition to 1 shot and 5 shot learning. 
 In this paper we use two different datasets: Omniglot and Mini Imagenet. 

 To train and test the model we have provided a [kaggle](https://www.kaggle.com/code/swethabalram2410/prototypical-networks-for-few-shot-learning/output) notebook. The scripts to download the Omniglot dataset is provided in omniglot_dataset.py file. 

# Authors
 - Aratrika Das
 - Kenzo Boudier
 - Swetha Balaram
 - Yash Mundhra
