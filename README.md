# stock-rl

## Roadmap
- [ ] Dataset

  - [x] make sure current data available (so this can use the same set of data from training to production)
  - [ ] Prepare training data
- [ ] RL
  - [ ] make the dataset like RL gym
  - [ ] what are the observation space/ action space?
  - [ ] what we need to account for if this is partially observable MDP?
- [ ] Model
  - [ ] Read from arxiv.org for guidance
  - [ ] experiment
  - [ ] metric: Sharpe ratio? maximising chances of earning over a percentage?
  - [ ] toy with different parameter?
- [ ] Training
  - [ ] Colab -> Azure ML?
- [ ] Deployment
  - [ ] azure pipeline?
  - [ ] azure logic app? so that they are just apis?
  - [ ] my db to cache data from yfiance? (rate limit per day)
  - [ ] What app so I can use it easily?