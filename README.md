<p align="center">
  <img src="https://raw.githubusercontent.com/jjleewustledu/computational-core/main/docs/images/computational-core-logo-color.png" width="50%" alt='computational-core'>
</p>

**Computational Core**

[![License](https://img.shields.io/badge/license-Apache%202.0-green.svg)](https://opensource.org/licenses/Apache-2.0)
[![Documentation Status](https://readthedocs.org/projects/computational-core/badge/?version=latest)](https://computational-core.readthedocs.io/en/latest/?badge=latest)

computational-core describes software projects authored by John J. Lee and collaborators for the [Computational Core](https://sites.wustl.edu/nillabs/nil-core-services/) of the [Neuroimaging Laboratories](https://sites.wustl.edu/nillabs/) at [Washington University in St. Louis](https://wustl.edu/).  These projects support research programs of the organizational units aforementioned.  

While the scope of projects is diverse, research themes most commonly involve:
  - biophysical models of brain metabolism and function
  - instrumentation and data specific for positron emission tomography 
  - instrumentation and data specific for resting-state functional magnetic resonance imaging
  - instrumentation and data specific for intracranial electroencephalography
  - data archives based on [XNAT]((https://www.xnat.org/)
  - standardized data formats such as [4dfp](https://4dfp.readthedocs.io/en/latest/>), [NIfTI](https://nifti.nimh.nih.gov/nifti-2), [CIFTI](https://www.nitrc.org/projects/cifti/), and [BIDS](https://bids.neuroimaging.io/)
  - inferential methodologies drawn from Bayesian statistics, expectation maximization, Markov chain Monte Carlo, graphical models, and deep learning
  - reuse of mature pre-existing projects such as [FSL](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki), [FreeSurfer](https://surfer.nmr.mgh.harvard.edu/), [Tensorflow](https://www.tensorflow.org/), [Pytorch](https://pytorch.org), and [MONAI](https://monai.io/).  

> _This project is under active development._

## Contents

1. package [mlfourd](https://mlfourd.readthedocs.io/en/latest/)

    - transparently supports 4dfp, NIfTI, CIFTI, FreeSurfer, iEEG and BIDS data formats
    - provides adapter patterns implementing client interfaces familiar for neuroscience tasks
    - uses state patterns instantiating lightweight objects optimized for categories of data and behavior
   
2. package [mlraichle](https://mlraichle.readthedocs.io/en/latest/)

    - provides biophysical models for oxygen and glucose metabolism
    - provides image-derived input functions
    - supports instrumentation related to the Siemens Biograph mMR
   
3. package [mlvg](https://mlvg.readthedocs.io/en/latest/)

    - supports instrumentation related to the Siemens Biograph Vision
   
4. package [mlarbelaez](https://mlarbelaez.readthedocs.io/en/latest/)

    - supports instrumentation related to the Siemens ECAT EXACT HR+
   
5. project [cc-graph-nets](https://cc-graph-nets.readthedocs.io/en/latest/)

    - implements Deep Minds' Graph Nets library for neuroimaging
   
6. project [cc-trax](https://cc-trax.readthedocs.io/en/latest/)

    - implements Google Brain's Trax and transformers for neuroimaging

7. project [cc-vision-transformer](https://cc-vision-transformer.readthedocs.io/en/latest/)

    - implements vision transformers and MLP-mixer architectures for neuroimaging
   
