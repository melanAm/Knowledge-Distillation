# Knowledge-Distillation

This code is based on the paper:

[Distilling the Knowledge in a Neural Network](https://arxiv.org/pdf/1503.02531)

by Geoffrey Hinton, Oriol Vinyals, Jeff Dean

Knowledge distillation is a method to transfer the knowledge of an already trained, large model (known as the teacher) to a smaller and simpler model (known as the student). The process incorporates predictions of the teacher model into the training stage of the student model in order for the student to learn how to mimic the teacher. The goal is to bridge the gap between the performance of large models and the efficiency of small models.               
