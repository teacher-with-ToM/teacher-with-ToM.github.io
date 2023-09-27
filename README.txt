# Utility-based Adaptive Teaching Strategies using Bayesian Theory of Mind

## General frameworl

This repository contains the code used in the paper under review 'Utility-based Adaptive Teaching Strategies using Bayesian Theory of Mind'.

In this paper, we introduce machine teachers equipped with a Bayesian Theory of Mind (ToM) model of the learner. The teacher is able to fits its ToM model to an observed learner and adapt the demonstration to the learner's goal and sensory capacity.

![General framework](./images/setup_internal_state.png)

**Figure:** This illustration represents our general framework, which consists of two environments:

**(A)** In the first environment, the learner (in green) behaves while the teacher (in pruple) observes the learner's behavior.

**(B)** In the second environment, the learner benefits from a demonstration chosen by the teacher from a set of available demonstrations. The learner's goal and sensory capability can vary, affecting the usefulness of a demonstration. ToM-teachers use the learner's observations to model its internal state as probability distributions over its goal and receptive field size. Based on this model, the teacher can calculate the expected utilities of the available demonstrations and choose the most beneficial one.

**(C)** The teachers are evaluated based on the utility measured from the demonstration they select for the learner they have observed.



## Reproducibility

The 'notebooks' folder contains three Jupyter notebooks that can be used to reproduce the results of the paper:

- **'experiments_Bayesian.ipynb'**: This notebook presents the environments, various learners, and ToM-teachers, as well as a complete interaction in two different environments.

- **'stat_utility.ipynb'**: In this notebook, you will find the statistical tests used to compute the main results of the paper. The outputs of the statistical tests are saved in the 'outputs' folder. To generate the figures of the main paper and Appendix (F), simply run the cells in the 'Display results' section of the notebook.

- **'stat_ToM.ipynb'**: This notebook contains the statistical tests used to generate the results presented in Appendix D. To generate the figures of the paper, run the cells in the 'Display results' section of the notebook.


Credits:
	The template of this webpage was taken from Massively by HTML5 UP
		html5up.net | @ajlkn
		Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)

		AJ
		aj@lkn.io | @ajlkn
