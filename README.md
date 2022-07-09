# DYNA-Q with [ReLAx](https://github.com/nslyubaykin/relax)
Example DYNA-Q implementation with [ReLAx](https://github.com/nslyubaykin/relax)

This repository contains an implementation of DYNA-Q algorithm for TD3 actor with ReLAx package.

The performance versus vanilla TD3 is measured by averaging the learning curve over 4 experiments with random environment seeds.

The results are summarised in the following plot:

![dyna_q_benchmark](https://github.com/nslyubaykin/relax_dyna_q_example/blob/master/walker2d_benchmark.png)

The only difference in hyperparameters settings between DYNA-Q-TD3 and vanilla TD3 is the presence of model based acceleration. We can see a considerable advantage of DYNA-Q by looking at the averaged curves.
