# DYNA-Q with [ReLAx](https://github.com/nslyubaykin/relax)
Example DYNA-Q implementation with [ReLAx](https://github.com/nslyubaykin/relax)

This repository contains an implementation of DYNA-Q algorithm for TD3 actor with ReLAx package.

The performance versus vanilla TD3 is measured by averaging learning curves over 4 experiments with random environment seeds.

The results are summarized in the following plot (1 point on x-axis corresponds to 10k envsteps totaling to 1m training steps):

![dyna_q_benchmark](https://github.com/nslyubaykin/relax_dyna_q_example/blob/master/dyna_q_benchmark.png)

The only difference in hyper-parameters settings between DYNA-Q-TD3 and vanilla TD3 is the presence of model based acceleration. We can see a considerable advantage of DYNA-Q by looking at the averaged curves.
