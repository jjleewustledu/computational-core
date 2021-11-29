:github_url: https://github.com/jjleewustledu/computational-core

Welcome to documentation for Computational Core
===============================================

**computational-core** describes software projects authored by John J. Lee and collaborators for the `Computational Core <https://sites.wustl.edu/nillabs/nil-core-services/>`_ of the `Neuroimaging Laboratories <https://sites.wustl.edu/nillabs/>`_ at `Washington University in St. Louis <https://wustl.edu/>`_.  These projects support research programs of the organizational units aforementioned.  

While the scope of projects is diverse, research themes most commonly involve:

- biophysical models of brain metabolism and function
- instrumentation and data specific for positron emission tomography 
- instrumentation and data specific for resting-state functional magnetic resonance imaging
- instrumentation and data specific for intracranial electroencephalography
- data archives based on `XNAT <https://www.xnat.org/>`_
- standardized data formats such as `4dfp <https://4dfp.readthedocs.io/en/latest/>`_, `NIfTI <https://nifti.nimh.nih.gov/nifti-2>`_, `CIFTI <https://www.nitrc.org/projects/cifti/>`_, and `BIDS <https://bids.neuroimaging.io/>`_
- inferential methodologies drawn from Bayesian statistics, expectation maximization, Markov chain Monte Carlo, graphical models, and deep learning
- reuse of mature pre-existing projects such as `FSL <https://fsl.fmrib.ox.ac.uk/fsl/fslwiki>`_, `FreeSurfer <https://surfer.nmr.mgh.harvard.edu/>`_, `Tensorflow <https://www.tensorflow.org/>`_, `Pytorch <https://pytorch.org/>`_, and `MONAI <https://monai.io/>`_.  

.. note::

   This project is under active development.


Contents
--------

#. package `mlfourd <https://mlfourd.readthedocs.io/en/latest/>`_
   * transparently supports 4dfp, NIfTI, CIFTI, FreeSurfer, iEEG and BIDS data formats
   * provides adapter patterns implementing client interfaces familiar for neuroscience tasks
   * uses state patterns instantiating lightweight objects optimized for categories of data and behavior
   
#. package `mlraichle <https://mlraichle.readthedocs.io/en/latest/>`_
   * provides biophysical models for oxygen and glucose metabolism
   * provides image-derived input functions
   * supports instrumentation related to the Siemens Biograph mMR
   
#. package `mlvg <https://mlvg.readthedocs.io/en/latest/>`_
   * supports instrumentation related to the Siemens Biograph Vision
   
#. package `mlarbelaez <https://mlarbelaez.readthedocs.io/en/latest/>`_
   * supports instrumentation related to the Siemens ECAT EXACT HR+
   
#. project `cc-graph-nets <https://cc-graph-nets.readthedocs.io/en/latest/>`_
   * implements Deep Minds' Graph Nets library for neuroimaging
   
#. project `cc-trax <https://cc-trax.readthedocs.io/en/latest/>`_
   * implements Google Brain's Trax and transformers for neuroimaging

#. project `cc-vision-transformer <https://cc-vision-transformer.readthedocs.io/en/latest/>`_
   * implements vision transformers and MLP-mixer architectures for neuroimaging
   

.. toctree::
   :caption: Feature highlights
   :maxdepth: 1
   
   whatsnew
   highlights.md

.. toctree::
   :caption: API Reference
   :maxdepth: 1

   api

.. toctree::
  :caption: Installation
  :maxdepth: 1

  installation
   
License
-------

computational-core is licensed under the Apache 2.0 License.


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
