# Report

This is my implementation of Neural ODE and establish its supremacy over the baseline LSTM. In this implementation, I had to make some choices.
1. I chose the damped pendulum dataset over PhysioNet ICU as this would help me understand the implementation of Neural ODE in a fundamental way.
2. I had tried earlier to Implement the Neural ODE without time as an input, considering that the next state would depend only on present state. But, the results proved me wrong. The actual implementation damped in t = 8 to 10 seconds only
3. I tried hours to over come the problem, but, had to choose the length, time as the input along with states.
4. I understood that the recurring errors in LSTMs compound when used against test as they imitate the train data completely.
5. While working with highly Noisy data, I came across this thing, that the apparent frequency is different from actual against both Neural ODE and LSTM.
6. I learnt basic understanding pf how PINNs work, how Neural ODEs work using trajectories.

