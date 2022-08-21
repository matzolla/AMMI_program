
## Foundation of DeepLearning
- One advantage of the RELU activation function max(0,z) with z=$w^{T}$x+b is that we can always perform gd since whenever the unit is active a disadvantage we can't learnwith a zero derivative (no updates) to overcome this we introduced leaky relu for example.

- The sigmoid and tanh functions looks alike `tanh(x)=2sigma(2x)-1` and `sigma(x)=1/1+exp(-x)`. One disadvantage of the sigmoid function is that `its derivative can be too large when the value of x is either too small or too big and only very sensitive to small regions in their domain.`
- The tanh function on the other hand can be considered as a linear function if we assume x to be very small. `y_hat=tanh(w^{T}(U^{T}tanh(W^{T}@x)))`.
