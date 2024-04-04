# Rescorla-Wagner-learning-model

## Overview

The Rescorla-Wagner model is a formal description of how animals and humans learn the association between different stimuli and outcomes, particularly in the context of Pavlovian or classical conditioning. The model posits that the strength of a stimulus-outcome association is updated incrementally as a result of the prediction error — the difference between expected and actual outcomes. Notable, however, is its failure to encompass the paradigm of secondary conditioning. This is key to sequential decision-making. Secondary conditioning depends on a new quantity, namely the time within each trial, since a positive association with the second stimulus is reliably established only if it precedes the first stimulus in the trials in which they are paired. Temporal Difference (TD) learning incorporates the aspect of time more explicitly than Rescorla Wagner. It shares the foundational concept of the delta rule (prediction error) with the Rescorla-Wagner model but extends it to account for the value of future rewards or outcomes over time. This is done through the estimation of future reward predictions at each time step within a trial or episode, making it possible to adjust predictions based on new information about how those rewards are temporally related to various stimuli.

## Structure

1. Introduction to the Rescorla-Wagner and TD learning Model
2. Visualization of the TD model as a plot
3. Experimentation with learning rates, reward value and distribution,  the time distance between stimulus and reward
4. Conclusion

## Conclusion

The Jupyter notebook is structured to both educate on the theoretical aspects of the Rescorla-Wagner and TD learning model and to provide 
hands-on demonstrations of its principles through simulation. The outputs of simulations are discussed in the accompanying markdown cells, 
providing a loop of hypothesis, experimentation, and conclusion that illustrates the model's predictive capabilities and limitations.
