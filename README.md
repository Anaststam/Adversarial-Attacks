# Adversarial-Attacks

### Project for the course Machine Learning for Graphs and Sequential Data(IN2323) at Technical University of Munich.

Several machine learning models, including neural networks, consistently misclassify adversarial examples—inputs formed by applying small but intentionally worst-case perturbations to examples from the dataset, such that the perturbed input results in the model outputting an incorrect answer with high confidence.

In this project, first we train a basic convolutional neural network on MNIST and craft adversarial examples via gradient descent ($L_2$-bounded attacks and $L_\infty$-bounded attacks)

Afterwards, we perform adversarial training on the convolutional neural network. Next, we train a smooth classifier via the principle of randomized smoothing and finally we compare the robustness of the classifiers we created via randomized smoothing.

Bibliography:
* https://arxiv.org/pdf/1412.6572.pdf
