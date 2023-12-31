# DITTO-Nocturne

This is work done as part of my tutorial at Oxford during the 2023 Michaelmas term. Specifically, I worked on applying the [DITTO](https://arxiv.org/abs/2302.03086) framework to the [Nocturne](https://github.com/facebookresearch/nocturne) RL environment. Check out the blog post [here](https://www.chrispondoc.com/tutorial-oxford/).

## Outline of Work

Throughout the four-ish weeks that I worked on the project, I was able to accomplish the following milestones. For all reports, check out the `reports/` folder:

1. Train a simple behavior cloning agent (BC) that was able to learn to drive within the Nocturne environment. I was also able to generate [rollouts](https://github.com/cpondoc/ditto-nocturne/blob/main/examples/test_rollout.py) using this agent.

2. Train a [world model](https://worldmodels.github.io/) on Nocturne, using expert state action pairs from Waymo. See `nocturne-wm.md`.

3. Train a BC agent on the latents of the Nocturne world model. See `bc-nocturne.md` and `visualizing-latents.md`.

4. Train an actor-critic (AC) policy using the Nocturne world model. See `finishing-validation.md`.

## Notes

The `notes` folder contains random fixes/issues I ran into during setting up each of DITTO and Nocturne. Some of the tips might be helpful, so might not be.

## Acknowledgments

Special thanks to [Branton Demoss](https://ori.ox.ac.uk/people/branton-demoss/), who advised my work over the term.
