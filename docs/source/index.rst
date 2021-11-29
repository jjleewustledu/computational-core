:github_url: https://github.com/jjleewustledu/computational-core

.. computational-core documentation main file


Computational Core
==================

*computational-core* describes software projects authored by John J. Lee and collaborators for the `Computational Core <https://sites.wustl.edu/nillabs/nil-core-services/>`_ of the `Neuroimaging Laboratories <https://sites.wustl.edu/nillabs/>`_ at `Washington University in St. Louis <https://wustl.edu/>`_.  These projects support research programs of the organizational units aforementioned.  

While the scope of projects is diverse, research themes most commonly involve:

- biophysical models of brain metabolism and function
- instrumentation and data specific for positron emission tomography 
- instrumentation and data specific for resting-state functional magnetic resonance imaging
- instrumentation and data specific for intracranial electroencephalography
- data archives based on `XNAT <https://www.xnat.org/>`_
- standardized data formats such as `4dfp <https://4dfp.readthedocs.io/en/latest/>`_, `NIfTI <https://nifti.nimh.nih.gov/nifti-2>`_, `CIFTI <https://www.nitrc.org/projects/cifti/>`_, and `BIDS <https://bids.neuroimaging.io/>`_
- inferential methodologies drawn from Bayesian statistics, expectation maximization, Markov chain Monte Carlo, graphical models, and deep learning
- reuse of mature pre-existing projects such as `FSL <https://fsl.fmrib.ox.ac.uk/fsl/fslwiki>`_, `FreeSurfer <https://surfer.nmr.mgh.harvard.edu/>`_, `Tensorflow <https://www.tensorflow.org/>`_, `Pytorch <https://pytorch.org/>`_, and `MONAI <https://monai.io/>`_.  

*This project is under active development.*


Contents
--------

1. package `mlfourd <https://mlfourd.readthedocs.io/en/latest/>`_

   - transparently supports 4dfp, NIfTI, CIFTI, FreeSurfer, iEEG and BIDS data formats
   - provides adapter patterns implementing client interfaces familiar for neuroscience tasks
   - uses state patterns instantiating lightweight objects optimized for categories of data and behavior
   
2. package `mlraichle <https://mlraichle.readthedocs.io/en/latest/>`_

   - provides biophysical models for oxygen and glucose metabolism
   - provides image-derived input functions
   - supports instrumentation related to the Siemens Biograph mMR
   
3. package `mlvg <https://mlvg.readthedocs.io/en/latest/>`_

   - supports instrumentation related to the Siemens Biograph Vision
   
4. package `mlarbelaez <https://mlarbelaez.readthedocs.io/en/latest/>`_

   - supports instrumentation related to the Siemens ECAT EXACT HR+
   
5. project `cc-graph-nets <https://cc-graph-nets.readthedocs.io/en/latest/>`_

   - implements Deep Minds' Graph Nets library for neuroimaging
   
6. project `cc-trax <https://cc-trax.readthedocs.io/en/latest/>`_

   - implements Google Brain's Trax and transformers for neuroimaging

7. project `cc-vision-transformer <https://cc-vision-transformer.readthedocs.io/en/latest/>`_

   - implements vision transformers and MLP-mixer architectures for neuroimaging


.. toctree::
   :maxdepth: 1
   :caption: Feature highlights
   
   whatsnew
   highlights.md

.. toctree::
   :maxdepth: 1
   :caption: API Reference

   api

.. toctree::
  :maxdepth: 1
  :caption: Installation

  installation


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
