## Computational Neuroscience Basics

This site summarizes numerous small projects which illustrate basic concepts in computational neuroscience. The projects start from the basic Integrate and Fire Model used to model neurons and build up to the Perceptron for binary classification and Temporal Difference Learning to illustrate classical conditioning. Click on the headings to explore each project in more detail.


### [Integrate and Fire Model](https://github.com/Ilsa07/Integrate-and-Fire-Model)
This project illustrates the simplified Integrate and Fire neuron model, which describes neurons as RC circuits. In this model incoming current increases the voltage of the neuron, and if the current is big enough and maintained for long enough, the neuron will reach its threshold voltage and will spike. After a spike, the volatage of the neuron is resetted to its resting voltage. This model does not contain adoption, which means that after a spike it is "as fresh as a daisy", it is not harder for it to spike again.  

### [Ring Network](https://github.com/Ilsa07/Ring-Network)




### [Bienenstock Cooper Munro (BCM) Learning Rule](https://github.com/Ilsa07/BCM-Learning-Rule)
The BCM learning rule explain how learning works on the neuron level. This project illustrates how a neruon becomes selective, learns to respond to only one type of stimulus, to input stimulus by randomly inputting one of two patterns to the neuron and implementing the rule. The BCM learning rule implements a sliding threshold simulating synaptic plasticity in the brain.


### [Spike Timing Dependent Plasticity (STDP)](https://github.com/Ilsa07/Spike-Timing-Dependent-Plasticity)
This project simulates STDP, which is a model of how weights between neurons change depending on the timing of the pre and post-synaptic spikes. In this modedl, if a pre-synaptic spike occurs before a post-synaptic one the weight that connects the two increases, and if it is the other way around it decreases. STDP explains how the brain can predict sequences and how we can respond to earlier stimulus.


### [Perceptron](https://github.com/Ilsa07/Perceptron)
This project illustrates the capeabilities of the perceptron, which can be used for binary classification. A perceptron is only capeable of learning linearly separable datasets, which is illustrated in the project.


### [Temporal Difference Learning](https://github.com/Ilsa07/TD-Learning-Conditioning)
This project recreates the famous Pavlov's Dog Experiment via Temporal Difference Learning, which is a classical conditioning example. In each trial a stimulus in the form of a bell is presented at t=5 seconds and a reward, corresponding to some tasty food, is given at the end of the experiment at t=20 seconds. After several trials, the model learns to associate the stimulus with the reward, just as the dog was expecting food after he heard the bell.


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
