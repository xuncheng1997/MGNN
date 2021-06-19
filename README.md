# Learn from Concepts: Towards the Purified Memory for Few-shot Learning
 This repository is the official implementation of Learn from Concepts: [Towards the Purified Memory for Few-shot Learning]()
## Abstract
Human beings have a great generalization ability to recognize a novel category by only seeing a few number of samples. This is because humans possess the ability to learn from the concepts that already exist in our minds. However, many existing few-shot approaches fail in addressing such a fundamental problem, {\it i.e.,} how to utilize the knowledge learned in the past to improve the prediction for the new task. In this paper, we present a novel purified memory mechanism that simulates the recognition process of human beings. This new memory updating scheme enables the model to purify the information from semantic labels and progressively learn consistent, stable, and expressive concepts when episodes are trained one by one. On its basis, a Graph Augmentation Module (GAM) is introduced to aggregate these concepts and knowledge learned from new tasks via a graph neural network, making the prediction more accurate. Generally, our approach is model-agnostic and computing efficient with negligible memory cost. Extensive experiments performed on several benchmarks demonstrate the proposed method can consistently outperform a vast number of state-of-the-art few-shot learning methods.
## Requirements
CUDA Version: 10.1 <br>
Python : 3.7.4 <br>
To install dependencies: <br>
> sudo pip3 install -r requirements.txt

## Dataset
| Dataset        | Images      | Classes     | Train-val-test |
| -----------    | ----------- | ----------- | -------------  |
| miniImageNet   | 60000       |  100        |  64/16/20      |
| tieredImageNet | 779165      |  608        |  351/97/160    |
| CUB-200-2011   | 11788       |  200        |  100/50/50     |
| CIFAR-FS       | 60000       |  100        |  64/16/20      |