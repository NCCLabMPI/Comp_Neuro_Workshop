---
layout: materials
title: Workshop Materials
---

This information can alteratively be accessed [via GitHub](https://github.com/carlosmig/comp_neuro_workshop)

# Required Resources

## Hardware:
- Only your personal computer.

## Software:
- An updated version of Python (Python > 3.0). If you don’t have Python already installed on your PC, we recommend installing Anaconda: [Download Anaconda](https://www.anaconda.com/)
- Jupyter Notebook: [Download Jupyter Notebook](https://jupyter.org/). It can also be installed with Anaconda.
- SPM12: [Download SPM12](https://www.fil.ion.ucl.ac.uk/spm/software/download/)
- MATLAB: A copy of MATLAB. SPM12 is designed to work with MATLAB versions R2007a (7.4) to R2023b (9.15), and will not work with earlier versions. It only requires core MATLAB to run (i.e. no toolboxes).
- JIDT for Python:
  - Download the latest version of JIDT from the [GitHub page](https://github.com/jlizier/jidt/wiki/Downloads)
  - Install Java. Follow the instructions [here](https://github.com/jlizier/jidt/wiki/Installation) (only the first instruction under 'Dependencies').
  - Within the code you're using, indicate where JAVA is installed. For example (Windows):

``` python
import os
#Set the JAVA_HOME environment variable
#Replace 'jdk_installation_directory' with the actual JDK installation directory
jdk_installation_directory = 'C:/Program Files/Java/jdk-21'
# Set JAVA_HOME for the current process
os.environ['JAVA_HOME'] = jdk_installation_directory
# To permanently set JAVA_HOME, you need to add it to the system environment variables

```

- Networkx: https://networkx.org/documentation/stable/install.html

- Brain Connectivity Toolbox for Python: https://pypi.org/project/bctpy/

- Numba: https://numba.readthedocs.io/en/stable/user/installing.html


---


# Recommended Literature

## Information theory and high-order interactions

### Basic bibliography:
- Timme, N. M., & Lapish, C. (2018). [A tutorial for information theory in neuroscience.](https://doi.org/10.1523/ENEURO.0052-18.2018) *eneuro, 5*(3).
- Cover, T. M., & Thomas, J. A. (2006). [Elements of Information Theory.](http://staff.ustc.edu.cn/~cgong821/Wiley.Interscience.Elements.of.Information.Theory.Jul.2006.eBook-DDU.pdf)
- Battiston, F., Amico, E., Barrat, A., Bianconi, G., Ferraz de Arruda, G., Franceschiello, B., ... & Petri, G. (2021). [The physics of higher-order interactions in complex systems.](https://doi.org/10.1038/s41567-021-01371-4) *Nature Physics, 17*(10).

### Further reading:
- Rosas et al. (2019). [Quantifying high-order interdependencies via multivariate extensions of the mutual information.](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.100.032305)
- Ince et al. (2017). [A statistical framework for neuroimaging data analysis based on mutual information estimated via a gaussian copula.](https://pubmed.ncbi.nlm.nih.gov/27860095/)
- Williams & Beer. [Nonnegative Decomposition of Multivariate Information.](https://arxiv.org/abs/1004.2515)
- Gatica et al. (2021). [High-Order Interdependencies in the Aging Brain.](https://www.liebertpub.com/doi/10.1089/brain.2020.0982)
- Herzog et al. (2022). [Genuine high-order interactions in brain networks and neurodegeneration.](https://www.sciencedirect.com/science/article/pii/S0969996122003102)
- Lizier (2014). [JIDT: an information-theoretic toolkit for studying the dynamics of complex systems.](https://www.frontiersin.org/articles/10.3389/frobt.2014.00011/full)

---

## Dynamic causal modeling

### Basic bibliography:
- Kiebel, S. J., Garrido, M. I., Moran, R. J., & Friston, K. J. (2008). [Dynamic causal modelling for EEG and MEG.](https://doi.org/10.1007/s11571-008-9038-0) *Cognitive neurodynamics, 2*.
- Marreiros, A. C., Stephan, K. E., & Friston, K. J. (2010). [Dynamic causal modeling.](http://var.scholarpedia.org/article/Dynamic_causal_modeling) *Scholarpedia, 5*(7).
- Friston, K. J. (2011). [Functional and effective connectivity: a review.](https://doi.org/10.1089/brain.2011.0008) *Brain connectivity, 1*(1).

### Further reading:
- Auksztulewicz, R., & Friston, K. (2015). [Attentional enhancement of auditory mismatch responses: a DCM/MEG study.](https://doi.org/10.1093/cercor/bhu323) *Cerebral cortex, 25*(11).
- Pinotsis, D. A., et al. (2017). [Linking canonical microcircuits and neuronal activity: Dynamic causal modelling of laminar recordings.](https://doi.org/10.1016/j.neuroimage.2016.11.041) *Neuroimage, 146*.
- Bönstrup, M., et al. (2016). [Dynamic causal modelling of EEG and fMRI to characterize network architectures in a simple motor task.](https://doi.org/10.1016/j.neuroimage.2015.08.052) *Neuroimage, 124*.
- Rubinov, M., & Sporns, O. (2010). [Complex network measures of brain connectivity: uses and interpretations.](https://doi.org/10.1016/j.neuroimage.2009.10.003) *Neuroimage, 52*(3).

---

## Whole-brain modeling

### Basic bibliography:
- Lynn, C. W., & Bassett, D. S. (2019). [The physics of brain network structure, function and control.](https://doi.org/10.1038/s42254-019-0040-8) *Nature Reviews Physics, 1*(5).
- Cofré, R., et al. (2020). [Whole-brain models to explore altered states of consciousness from the bottom up.](https://doi.org/10.3390/brainsci10090626) *Brain Sciences, 10*(9).
- Blohm, G., et al. (2020). [A how-to-model guide for neuroscience.](https://doi.org/10.1523/ENEURO.0352-19.2019) *Eneuro, 7*(1).

### Further reading:
- Deco, G., et al. (2018). [Whole-brain multimodal neuroimaging model using serotonin receptor maps explains non-linear functional effects of LSD.](https://doi.org/10.1016/j.cub.2018.07.083) *Current biology, 28*(19).
- Herzog, R., et al. (2023). [A whole-brain model of the neural entropy increase elicited by psychedelic drugs.](https://doi.org/10.1038/s41598-023-32649-7) *Scientific reports, 13*(1).
- Coronel‐Oliveros, C., et al. (2024). [Viscous dynamics associated with hypoexcitation and structural disintegration in neurodegeneration via generative whole‐brain modeling.](https://doi.org/10.1002/alz.13788) *Alzheimer's & Dementia*.
- Deco, G., et al. (2019). [Awakening: Predicting external stimulation to force transitions between different brain states.](https://doi.org/10.1073/pnas.1905534116) *Proceedings of the National Academy of Sciences, 116*(36).
