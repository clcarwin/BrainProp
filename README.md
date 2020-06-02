# BrainProp
_A biologically plausible learning rule that can train deep neural networks on image-classification tasks (MNIST, CIFAR10, CIFAR100, Tiny ImageNet)._ 


# My Paper Title

This repository is the official implementation of "BrainProp: How the brain can implement reward-based error backpropagation" (https://arxiv.org/abs/{...}). 

> 📋Optional: include a graphic explaining your approach/main result, bibtex entry, link to demos, blog posts and tutorials


## Requirements

Python 3.6.6
pip 20.1.1
CUDA 10.1.243
cuDNN 7.6.5.32

To install the required libraries and modules:

```setup
pip install -r Requirements.txt
```

Datasets: MNIST, CIFAR10 and CIFAR100 are available through keras. Tiny Imagenet needs to be extracted and prepared. 


## Training

To train the model(s) in the paper, run this command:

```train
python train.py --input-data <path_to_data> --alpha 10 --beta 20
```

> 📋Describe how to train the models, with example commands on how to train the models in your paper, including the full training procedure and appropriate hyperparameters.


## Evaluation

To evaluate my model on ImageNet, run:

```eval
python eval.py --model-file mymodel.pth --benchmark imagenet
```

> 📋Describe how to evaluate the trained models on benchmarks reported in the paper, give commands that produce the results (section below).


## Pre-trained Models

You can download pretrained models here:

- [My awesome model](https://drive.google.com/mymodel.pth) trained on ImageNet using parameters x,y,z. 

> 📋Give a link to where/how the pretrained models can be downloaded and how they were trained (if applicable).  Alternatively you can have an additional column in your results table with a link to the models.


## Results

Our model achieves the following performance on :


### [Image Classification on ImageNet](https://paperswithcode.com/sota/image-classification-on-imagenet)

| Model name         | Top 1 Accuracy  | Top 5 Accuracy |
| ------------------ |---------------- | -------------- |
| My awesome model   |     85%         |      95%       |

> 📋Include a table of results from your paper, and link back to the leaderboard for clarity and context. If your main result is a figure, include that figure and link to the command or notebook to reproduce it. 


## Contributing

> 📋Pick a licence and describe how to contribute to your code repository. 
