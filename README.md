# Tutorial on DER Hosting Capacity - Part 0: Using dss_python

## Tutorial on DER Hosting Capacity

This Tutorial on Distributed Energy Resource (DER) Hosting Capacity will guide you, using interactive code via Jupyter Notebook and Python, through the different steps to run advanced, detailed time-series simulations to properly assess the technical impacts of DERs (such as solar photovoltaics) on realistic three-phase unbalanced distribution networks. Throuhought this tutorial we will be using OpenDSS (https://sourceforge.net/projects/electricdss/) - an open source distribution network analysis tool developed by the Electric Power Research Instutite (EPRI, https://www.epri.com/), USA. Thanks to our colleagues and friends at EPRI for this important contribution to the world!

This Tutorial is designed for power engineering students (undergraduate and postgraduate), power engineers, researchers, consultants, etc. It requires coding knowledge - of course!. But not too advanced. If you are a decent coder, you will manage ;-)

## Part 0: Using dss_python

Part 0 is about how to interact with the dss_python module, a built-in Python library to replace using OpenDSS via the COM interface. This makes simulations and the handling of data/results much faster as everything will be native to Python. The dss_python module is built as a drop-in replacement for the COM interface where 99% of the code does not need to be changed. More information about dss_python can be found in https://dss-extensions.org/. Thanks to our colleagues and friends at the University of Campinas (UNICAMP, https://www.unicamp.br/), Brazil for this contribution!

* Note: The use of dss_python implies you will be using (and, therefore, you will be limited to) the latest version of dss_python which might not necessarily be the latest version of OpenDSS. This could affect, for instance, certain embedded models and control functions. So, keep an eye on the latest versions and their differences. For most types of studies, the available version of dss_python will be more than enough.

## New to OpenDSS, Distribution Networks and DER?

* If you are new to distribution network and DER modelling and want to learn more about OpenDSS before you get into advanced coding, we recommend you go through our **OpenDSS For Beginners** training material: https://sites.google.com/view/luisfochoa/research-tools/opendss-training-material

## Pre-Requisites for Part 0

* OpenDSS, Python (Anaconda), and Jupyter Notebook (comes with Anaconda). GitHub Desktop is optional. For download links and more info: https://sites.google.com/view/luisfochoa/research-tools. *Remember to always install using full admin rights*.

* dss_python module. Run "python -m pip install dss_python" in the Anaconda Prompt.

## Run Part 0

* You can download the source code (the .zip file will do) using the green `<> CODE` button at the top or clone the entire repository to your local drive using GitHub Desktop. If you downloaded the code, unzip the file.

* Run Jupyter Notebook (it will open a tab on your browser). Upload "main.ipynb" and click on the uploaded file. In the new tab, go through the tutorial by running each cell accordingly (use the "play" button on the left).

## Credits

Michael Liu (michael.liu@unimelb.edu.au)

Nando Ochoa (luis.ochoa@unimelb.edu.au ; https://sites.google.com/view/luisfochoa)

## Acknowledgement

The content of this repository has been produced with direct and/or indirect inputs from multiple members (past and present) of Prof Nando Ochoa’s Research Team. So, special thanks to all of them (many of whom are now in different corners of the world).

* https://sites.google.com/view/luisfochoa/research/research-team
* https://sites.google.com/view/luisfochoa/research/past-team-members

## Licenses

Since this repository uses dss_python which is based on OpenDSS, both licenses have been included. This repository uses the BSD 3-Clause "New" or "Revised" license. Check all corresponding files (`LICENSE-OpenDSS`, `LICENSE-dss_python`, `LICENSE`).
