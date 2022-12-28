# Compression_NeuralNets
The Deep Neural Networks have achieved great success in image recognition, speech recognition, and  Natural Language processing tasks. Optimizing more accuracy results made DNN very large with parameters in the order of millions. So large deep neural nets are computationally expensive and memory intensive. So embedding these neural nets into low computation devices made them hard. This project describes the compression models like pruning, quantisation, and knowledge distillation for compressing large neural nets to small with less loss of compression accuracy when compared to the baseline accuracy of network models. 



1. Knowledge Distillation


As in the progress of the project we encountered that the model pruning doesn't fit the models with the higher architecture. Recent studies suggested to use the Knowledge distillation compression Technique to compress the large models even with the higher architecture. The knowledge distillation deals with the transfer of the knowledge from the teacher model(large NN) to the student model(smaller NN) so that the student can reach the level of the performance of the teacher model, also the knolwdge distillation aims to minimize the distillation loss i.e., cross entropy between the soft labels and hard lebels of the student model.

To get more relevent information here the most referred paper.

ref: https://arxiv.org/abs/2106.05237

#LICENSE - blob/main/LICENSE
