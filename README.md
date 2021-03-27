# The correlated dice

This jupyter notebook aims to showcase a concise and memorable model system exhibiting temporal correlation in the obtained time series.
In this model a dice is more probable to yield the same result as before than to yield a different result.

For the Markov chain at hand, we compute a numerical estimate of the auto correlation function as well as numerical auto correlation function from the given transition probabilities.

You can execute the notebook using binder 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jonaslandsgesell/correlated_dice/master?filepath=correlated%20dice.ipynb)
However, you need to set "%matplotlib inline" disabling interactive plots.

Formatting of the notebook is enforced after running "pre-commit install" which will start black_nbconvert on every commit.
