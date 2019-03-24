# image
##### The new activation function is {e^x-1}/{1+x^2}
The function is more complex than the swish function and hence can allow the learning of more complex relationships having more points of inflection. The function provides a faster and greater decrease in loss as is shown in the comparision graphs. However
the loss change is not uniform owing to the point that the graph of this function has many more changes in gradients and in non monotonous with a more deeper local minima making the implementation prone to irregular changes in loss. This function would re





I used the activation function as x^2/(1+e^-x)
###### The Graph of the function has been attached
I tried working with relu but the difficulty with relu is that it’s derivative is equal to zero for half of the values of the number line. This problem has been tried to be rectified using leaky relu or SELU . The function I used has a non-monotonic attribute that actually creates the difference. With self-gating, it requires just a scalar input whereas in multi-gating scenario, it would require multiple two-scalar input. It has been inspired by the use of Sigmoid function in LSTM (‘self-gated’ means that the gate is actually the ‘sigmoid’ of activation itself).The function i chose is non linear and non-monotonic which makes it’s various combinations non linear and able to learn non linear and complex relations. This function able to train deeper networks as what can be done by relu. Since sigmoid and tanh are monotonic they have the problem of vanishing gradients when the network gets too deep. This means that the function I used is supposed to be able to learn more complex and varied relationships but has to face the problem of the need to train more and the requirement for deeper networks to justify the advantage of having no linearity. This effectively increases the computation and compute power require but is able to learn more complex relations. I had also tried using other functions like identity, sigmoid, tanh and relu but this function used gave the best results of them all. I also observed that because of non linearity  This activation function is computationally heavy but can learn more complex relationships in a deeper network.
