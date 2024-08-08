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
    - [ ] [Google serach](https://www.google.com/search?q=stock+price+reinforcement+learning+site%3Aarxiv.org&lr=&sca_esv=32e484f6156eb8e3&sca_upv=1&as_qdr=all&sxsrf=ADLYWIL-hasdETNN_Oz13vRkO_5aJRfppQ%3A1723124007938&ei=J8m0ZvHyOIun2roP0uvuoQc&ved=0ahUKEwixopaTweWHAxWLk1YBHdK1O3QQ4dUDCBA&uact=5&oq=stock+price+reinforcement+learning+site%3Aarxiv.org&gs_lp=Egxnd3Mtd2l6LXNlcnAiMXN0b2NrIHByaWNlIHJlaW5mb3JjZW1lbnQgbGVhcm5pbmcgc2l0ZTphcnhpdi5vcmdIpW5QozFYsG1wAXgAkAEAmAGZAqABviuqAQcwLjEwLjE2uAEDyAEA-AEBmAIAoAIAmAMAiAYBkgcAoAeSCQ&sclient=gws-wiz-serp)
  - [ ] experiment
  - [ ] metric: Sharpe ratio? maximising chances of earning over a percentage?
  - [ ] toy with different parameter?
- [ ] Training
  - [ ] Colab -> Azure ML?
    - [ ] [Tutorial](https://learn.microsoft.com/en-us/azure/machine-learning/tutorial-explore-data?view=azureml-api-2)
- [ ] Deployment
  - [ ] azure pipeline?
  - [ ] azure logic app? so that they are just apis?
  - [ ] my db to cache data from yfiance? (rate limit per day)
  - [ ] What app so I can use it easily?