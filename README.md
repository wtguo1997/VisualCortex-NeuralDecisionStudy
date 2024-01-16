# Visual Stimuli and Perceptual Decision-Making: A Study of Neuron Firing Patterns in the Visual Cortex

This repository contains an R Markdown project, exploring the relationship between visual stimuli and perceptual decision-making through the analysis of neuron firing patterns in the visual cortex. The project utilizes R packages like `dplyr`, `ggplot2`, `plotly`, `gapminder`, and `ggpubr` to process and visualize data. The study aims to provide insights into how visual inputs are processed by neurons in the visual cortex and how this influences decision-making processes.

In this project, we analyze a subset of data (5 in 39 sessions) from [Steinmetz et al. (2019)](https://www.nature.com/articles/s41586-019-1787-x) on the neural activity of mice during visual decision-making tasks. We used data from five sessions of two mice to study the spike trains of neurons in the visual cortex during stimuli onset to 0.4 seconds post-onset. The analysis employs a mixed two-way ANOVA to reveal the effects of contrast level on neural activity, providing insights into the neural mechanisms of visual perception and decision-making in mice. In addition, we can give predictions on the decision feedback outcomes from visual stimuli, and neuron mean firing rates based on a classification model. The study contributes to our understanding of how the visual cortex processes visual stimuli as well as decision-making.

In this work, we highlight the impact of visual behavior to study how stimuli activate the neurons by revisiting a fraction of data from Steinmetz’s experiment. Therefore, we try to answer the below questions:

1. What are the patterns and relationships within the data in interest?
2. In what way of neuron firing do the neurons in the visual cortex react to the visual stimuli presented on the left and right?
3. Can we use a classification model to predict the feedback decision from the visual stimulus pattern and neuron firing rate at the first 0.4 seconds?

For a detailed report on this statistical study, please refer to the `html` file.
