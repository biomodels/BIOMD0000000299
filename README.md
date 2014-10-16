# BIOMD0000000299: Leloup1999_CircadianRhythms_Neurospora

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000299.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000299.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000299 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Limit cycle models for circadian rhythms based on transcriptional regulation in Drosophila and Neurospora.**   
Leloup JC, Gonze D, Goldbeter A. _J Biol Rhythms._ 1999 Dec;14(6):433-48.
[10643740](http://www.ncbi.nlm.nih.gov/pubmed/10643740) ,  
**Abstract:**   
We examine theoretical models for circadian oscillations based on
transcriptional regulation in Drosophila and Neurospora. For Drosophila, the
molecular model is based on the negative feedback exerted on the expression of
the per and tim genes by the complex formed between the PER and TIM proteins.
For Neurospora, similarly, the model relies on the feedback exerted on the
expression of the frq gene by its protein product FRQ. In both models,
sustained rhythmic variations in protein and mRNA levels occur in continuous
darkness, in the form of limit cycle oscillations. The effect of light on
circadian rhythms is taken into account in the models by considering that it
triggers degradation of the TIM protein in Drosophila, and frq transcription
in Neurospora. When incorporating the control exerted by light at the
molecular level, we show that the models can account for the entrainment of
circadian rhythms by light-dark cycles and for the damping of the oscillations
in constant light, though such damping occurs more readily in the Drosophila
model. The models account for the phase shifts induced by light pulses and
allow the construction of phase response curves. These compare well with
experimental results obtained in Drosophila. The model for Drosophila shows
that when applied at the appropriate phase, light pulses of appropriate
duration and magnitude can permanently or transiently suppress circadian
rhythmicity. We investigate the effects of the magnitude of light-induced
changes on oscillatory behavior. Finally, we discuss the common and
distinctive features of circadian oscillations in the two organisms.

This particular version of the model has been translated from equations 4a-4c
(Neurospora).

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Leloup JC, Gonze D, Goldbeter A. (1999) -
version02**
](http://www.cellml.org/models/leloup_gonze_goldbeter_1999_version02)  
The original CellML model was created by:  
**Lloyd, Catherine, May**   
c.lloyd@aukland.ac.nz  
The University of Auckland  
The Bioengineering Institute  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2010 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


