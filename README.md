# Tutorial on DER Hosting Capacity - Part 0: Using dss_python

## Tutorial on DER Hosting Capacity

This multi-part Tutorial on Distributed Energy Resource (DER) Hosting Capacity will guide you, using interactive code via Jupyter Notebook and Python, through the different steps to run advanced, detailed time-series simulations to properly assess the technical impacts of DERs (such as solar photovoltaics ☀️🏡) on realistic three-phase unbalanced distribution networks.

This Tutorial is designed for power engineering students (undergraduate and postgraduate), power engineers, researchers, consultants, etc. It requires some knowledge of coding (of course! 🤓) but not too advanced. If you are a decent coder, you will manage 😉.

## Part 0: Using dss_python

The objectives of this tutorial are:
1. To familiarise with **advanced tools useful to run distribution network studies involving DERs**. You will be using the programming language Python and the advanced distribution network analysis tool [OpenDSS](https://www.epri.com/pages/sa/opendss) via the [dss_python](https://github.com/dss-extensions/dss_python) module. And, to guide you, all will be done using a notebook on [Jupyter Notebook](https://jupyter.org/).

2. To interact with the **dss_python module** and show how it replaces using OpenDSS via the COM interface. This module makes simulations and the handling of data/results much faster as everything will be native to Python.

### New to OpenDSS, Distribution Networks and DERs?

- If you are new to distribution network and DER modelling and want to learn more about OpenDSS before you get into advanced coding, we recommend you go through our **OpenDSS For Beginners** training material: https://sites.google.com/view/luisfochoa/research-tools/opendss-training-material

### Pre-Requisites for Part 0

- OpenDSS. Download link https://sourceforge.net/projects/electricdss/.
- Python (Anaconda) and Jupyter Notebook (comes with Anaconda). Download links and more info: https://www.anaconda.com/download. Note that you must install the Anaconda that is compatible with your operating system (e.g., Windows, Mac). Also note that this repository is meant to be used by individuals (who can get free access to Anaconda).
- dss_python module. To install, run `pip install dss_python` in the Anaconda Prompt.
- To guarantee that you have all the necessary packages you can also run the `requirements.txt` file using `pip install -r requirements.txt` in the Anaconda prompt.
- *Remember to always install using full admin rights*.
- More info about these software packages: https://sites.google.com/view/luisfochoa/research-tools.

## Run Part 0

Make sure you have installed Anaconda, the dss_python module, etc. as specified above. Otherwise, you will not be able to go through the tutorial.

1. Download all the files using the green **`<> Code`** button at the top right.
   - You will get a ZIP file with a folder that contains all the files.
   - Unzip the file an place the folder somewhere in your computer/laptop.
3. To open the Jupyter notebook file (extension **`ipynb`**) you need to:
   - Open Anaconda Navigator
   - Click on Launch Jupyter notebook (it will open in your browser)
   - Upload the unzipped folder (with all the corresponding files) to Jupyter Notebook (the location is up to you)
   - Go inside the folder and open the **`ipynb`** file

All the tutorial instructions will be in the **`ipynb`** file.

Enjoy! 🤓


## Credits

Michael Liu (michael.liu@unimelb.edu.au)  
Eshan Karunarathne (akarunarathn@student.unimelb.edu.au)  
Arthur Goncalves Givisiez (a.goncalvesgivisiez@unimelb.edu.au)  
Nando Ochoa (luis.ochoa@unimelb.edu.au ; https://sites.google.com/view/luisfochoa)

## Acknowledgement

The content of this repository has been produced with direct and/or indirect inputs from multiple members (past and present) of Prof Nando Ochoa’s Research Team. So, special thanks to all of them (many of whom are now in different corners of the world).

* https://sites.google.com/view/luisfochoa/research/research-team
* https://sites.google.com/view/luisfochoa/research/past-team-members

## Licenses

Since this repository uses dss_python which is based on OpenDSS, both licenses have been included. This repository uses the BSD 3-Clause "New" or "Revised" license. Check all corresponding files (`LICENSE-OpenDSS`, `LICENSE-dss_python`, `LICENSE`).
