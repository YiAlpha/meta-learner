# Optimize Intervention Allocation in A/B Testing

This project is to gauge the individual treatment effect in randomized controlled trials (RCT) using Meta-Learner, a machine learning framework. And then provide advice for next round intervention allocation based on the pattern we found in individual effects. You can read my full description in [thesis.pdf](https://github.com/YiAlpha/meta-learner/blob/main/Thesis.pdf).

**Affiliation**: [Institute for Social and Economic Research and Policy](http://iserp.columbia.edu/), Columbia University.

**Keywords**: Randomized Controlled Trails (RCT), Meta-Leaner

**Software**:  

- Python : `econml`, `linearmodels`, `statsmodels` `sklearn`

**Reference**

- [Paper Introduction to Meta-Learner](https://arxiv.org/pdf/1706.03461.pdf)
- Computation about meta-learner: [EconML](https://github.com/microsoft/EconML)

**Data and Scope**

*Note: Data sets are not posted due to privacy and intellectual property concerns. Special thanks to Dr. Don Green grants me the access to the data files.*

- Exploratory analysis on three text-messaging voter mobilization experiments
  conducted before 2016 general election.

  |Experiment|  Treatment Group    |  Control Group    | Script |
  | ----------------- | ---- | ---- | ---- |
  |       One Arizona Campaign            |     200,442 |   50,187   |`code/One Arizona Experiment.ipynb`|
  |         NextGen Climate Campaign          |   94,257   |   94,229 |`code/NextGen Climate Experiment.ipynb`|
  |          Vote.org         |  905,396    |    301,920  |`code/Vote Org Experiment.ipynb`|
  |          Pooled      |  1,019,697   |    446,336   |`code/Pooled Analysis.ipynb`|


- Estimate individual treatment by regression with interaction term
- Estimate individual treatment by meta-learner approach

## Exploratory analysis  

![explora](images/exploratory.png)

## Regression

![regression](images/regression.png)

## Meta-Learner

![meta](images/meta.png)