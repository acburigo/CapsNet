# CapsNet
This is a [pytorch](http://pytorch.org/) implementation of CapsNet, described in the paper [Dynamic Routing Between Capsules](https://arxiv.org/abs/1710.09829) - by [Sara Sabour](https://arxiv.org/find/cs/1/au:+Sabour_S/0/1/0/all/0/1), [Nicholas Frosst](https://arxiv.org/find/cs/1/au:+Frosst_N/0/1/0/all/0/1) and [Geoffrey E Hinton](https://arxiv.org/find/cs/1/au:+Hinton_G/0/1/0/all/0/1).

## MNIST
### Accuracy
Although the paper reports an accuracy of *99.75%*, this implementation currently reaches an accuracy of around **99.6%**.

### Execution Speed
111 seconds per epoch on a single Titan Xp GPU.

### Number of Parameters
Model has 8141840 parameters.
