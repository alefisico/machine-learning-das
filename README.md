# CMS Machine Learning Data Analsyis School (DAS) Short Exercise

## Introduction

This is a modified version of this tutorial.

This is a set of tutorials for the CMS Machine Learning Data Analysis School (DAS) Short Exercise. They are intended to show you how to build machine learning models in python (`Keras`/`TensorFlow`) and use them in your `ROOT`-based analyses. We will build event-level classifiers for differentiating VBF Higgs and standard model background 4 muon events and jet-level classifiers for differentiating boosted W boson jets from QCD jets.

## Main notebooks in this tutorial

 1. [`1.1-datasets-uproot.ipynb`](1-datasets.ipynb): reading/writing datasets from `ROOT` files with `uproot`
 2. [`2-plotting-ROOT.ipynb`](2-plotting-ROOT.ipynb): plotting with `pyROOT`
 2. [`2-plotting-python.ipynb`](2-plotting-python.ipynb): plotting with  `matplotlib`
 3. [`3-dense.ipynb`](3-dense.ipynb): building, training, and evaluating a fully connected (dense) neural network in `Keras`
 4. [`4-preprocessing.ipynb`](4-preprocessing.ipynb): preprocessing CMS open data to build jet-images (optional)
 5. [`5-conv2d.ipynb`](5-conv2d.ipynb): building, training, and evaluating a 2D convolutional neural network in `Keras`

## Setup

For all the notebooks, you need to activate the kernel `python-analysis-env`, except the `2-plotting-ROOT.ipynb` which needs the kernel `root-analysis-env`.

## Links

The indico page is: [https://indico.cern.ch/e/cmsdas2022](https://indico.cern.ch/e/cmsdas2022)

The Mattermost for live support is: [https://mattermost.web.cern.ch/cmsdaslpc2022/channels/shortexml](https://mattermost.web.cern.ch/cmsdaslpc2022/channels/shortexml)

The twiki is: [https://twiki.cern.ch/twiki/bin/view/CMS/SWGuideCMSDataAnalysisSchoolLPC2022MachineLearningShortExercise](https://twiki.cern.ch/twiki/bin/view/CMS/SWGuideCMSDataAnalysisSchoolLPC2022MachineLearningShortExercise)
