# Data analysis Hands on

Welcome to the repository of the Data Analysis session hands-on for the [MaNiTou school 2022](https://indico.in2p3.fr/event/25990/timetable/#20220707). This repository hosts the Notebooks on which we will work together. All the notebooks contain an introduction part and some challenges that you can face with the commands learnt in the introduction part. 

We advise to fact the tutorials in the following order:

* `Tutorial_1_statistical_inference`: A tutorial on Bayesian and frequenstis inference
* `Tutorial_2_handling_posterior_samples`: A tutorial on how to handle posterior samples for GW events, how to compute confidence intervals and reweight posteriors.
* `Tutorial_3_estimate_the_Hubble_constant`: A tutorial on how to estimate the Hubble constant for Bright and Dark standard sirens. We will also make use of galaxy catalogs.
* `EXTRA_playing_with_waveforms`: Extra material showing how you can use Pycbc to generate waveforms
* `EXTRA_GW_in_frequency_domain`: Extra material to see how to whiten data, and visualize spectrograms for GW time series.

# Running the tutorials



## Running on cloud platforms

we strongly adivse you to run the tutorials on Cloud Platforms. We propose two solutions

**MyBinder:** If you do not have a Google account, you load the repository by clickling on the MyBinder icon below. Once the repository is loaded, navigate in the `DA_handson` folder and start the notebooks that you want to try. Please, remember to uncomment the first lines to install the required packages.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/simone-mastrogiovanni/MaNiTou2022/HEAD)

**Google Colab:** If you have a Google account, you can use [Google Colab](https://research.google.com/colaboratory/). This is an online service offered by Google that already contains many python packages. In the header of each notebook, you will find a link to the Google Colab version. Note that some notebooks require the installation of extra packages, in that case you will need to uncomment few lines on the notebook header. To run the notebooks on Colab, simply click on the Colab link in the header of each notebook.

## Running in local

If you want to run the tutorials on your local computer you will need to install the required python packages. We suggest to follow the steps below

* Download and install with conda the igwn-py38 environment from [this page](https://computing.docs.ligo.org/conda/environments/igwn-py38/).

* Activate the conda environment with 

```
conda activate igwn-py38
```

* Clone this repository with 

```
git clone https://github.com/simone-mastrogiovanni/MaNiTou2022.git
```

* You are ready to go!
