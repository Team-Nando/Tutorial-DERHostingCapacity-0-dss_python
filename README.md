Last update: 22/06/2022

# Tutorial on DER Hosting Capacity - Part 1: Using dss_python

## Tutorial on DER Hosting Capacity

This Tutorial on Distributed Energy Resource (DER) Hosting Capacity will guide you, using interactive code via Jupyter Notebook and Python, through the different steps to run advanced, detailed time-series simulations to properly assess the technical impacts of DERs (such as solar photovoltaics) on realistic three-phase unbalanced distribution networks. Throuhought this tutorial we will be using OpenDSS (https://sourceforge.net/projects/electricdss/) - an open source distribution network analysis tool developed by the Electric Power Research Instutite (EPRI, https://www.epri.com/), USA. Thanks to our colleagues and friends at EPRI for this important contribution to the world!

This Tutorial is designed for power engineering students (undergraduate and postgraduate), power engineers, researchers, consultants, etc. It requires coding knowledge - of course!. But not too advanced. If you are a decent coder, you will manage ;-)

## Part 1: Using dss_python

Part 1 is about how to interact with the dss_python module, a built-in Python library to replace using OpenDSS via the COM interface. This makes simulations and the handling of data/results much faster as everything will be native to Python. The dss_python module is built as a drop-in replacement for the COM interface where 99% of the code does not need to be changed. More information about dss_python can be found in https://dss-extensions.org/. Thanks to our colleagues and friends at the University of Campinas (UNICAMP, https://www.unicamp.br/), Brazil for this contribution!

* Note: The use of dss_python implies you will be using (and, therefore, you will be limited to) the embedded models and control functions of OpenDSS for particular elements. For instance, you can use OpenDSS's Volt-Watt function for solar PV systems. But you will not be able to modify it to do simultaneous Volt-Watt and Volt-var. If you need to create specific functionalities in Python, then you will need to interact with OpenDSS via the COM interface (which can also be done using Python).

## New to OpenDSS, Distribution Networks and DER?

* If you are new to distribution network and DER modelling and want to learn more about OpenDSS before you get into advanced coding, we recommend you go through this training material: https://sites.google.com/view/luisfochoa/research-tools/opendss-training-material

## Pre-Requisites for Part 1

* OpenDSS, Python (Anaconda), and Jupyter Notebook (comes with Anaconda). GitHub Desktop is optional. For download links and more info: https://sites.google.com/view/luisfochoa/research-tools

* dss_python module. Run "python -m pip install dss_python" in the Anaconda Prompt.

## Run Part 1

* You can download the source code (the .zip file will do) from the releases section (https://github.com/Team-Nando-Training/Tutorial-DERHostingCapacity-1-dss_python/releases) or clone the entire repository to your local drive using GitHub Desktop. Unzip the file.

* Run Jupyter Notebook (it will open a tab on your browser). Upload "main.ipynb" and click on the uploaded file. In the new tab, go through the tutorial by running each cell accordingly (use the "play" button on the left).

## Credits

Michael Liu (michael.liu@unimelb.edu.au)

Nando Ochoa (luis.ochoa@unimelb.edu.au ; https://sites.google.com/view/luisfochoa)

## Acknowledgement

The content of this repository has been produced with direct and/or indirect inputs from multiple members (past and present) of Prof Nando Ochoa’s Research Team. So, special thanks to all of them (many of whom are now in different corners of the world).

* https://sites.google.com/view/luisfochoa/research/research-team
* https://sites.google.com/view/luisfochoa/research/past-team-members
