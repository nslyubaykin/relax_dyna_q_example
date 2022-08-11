# DYNA-Q with [ReLAx](https://github.com/nslyubaykin/relax)
Example DYNA-Q implementation with [ReLAx](https://github.com/nslyubaykin/relax)

This repository contains an implementation of DYNA-Q algorithm for TD3 actor with ReLAx package.

The performance versus vanilla TD3 is measured by averaging learning curves (for separate evaluation environment) over 4 experiments with random environment seeds.

The results are summarized in the following plot (1 point on x-axis corresponds to 10k envsteps, totaling to 1m training steps):

![dyna_q_benchmark](https://github.com/nslyubaykin/relax_dyna_q_example/blob/master/dyna_q_benchmark.png)

The only difference in hyper-parameters settings between DYNA-Q-TD3 and vanilla TD3 is the presence of model based acceleration. We can see a considerable advantage of DYNA-Q by looking at the averaged curves.

__Vanilla TD3__

https://user-images.githubusercontent.com/67604207/184104532-886adf3a-de90-49b6-a321-657062b8858b.mp4

__DYNA-Q TD3__

https://user-images.githubusercontent.com/67604207/184104597-6812f928-31c4-4769-b3b6-c068ed3a53f5.mp4
