# ConCare: Personalized Clinical Feature Embedding via Capturing the Healthcare Context

The source code for *ConCare: Personalized Clinical Feature Embedding via Capturing the Healthcare Context*

Thanks for your interest in our work. More details about the experiment, case study and visualization system will be released before AAAI2020.

Our paper can be find [here](https://www.researchgate.net/publication/337481368_ConCare_Personalized_Clinical_Feature_Embedding_via_Capturing_the_Healthcare_Context). 

## Requirements

* Install python, pytorch. We use Python 3.7.3, Pytorch 1.1.
* If you plan to use GPU computation, install CUDA

## Data preparation
We do not provide the MIMIC-III data itself. You must acquire the data yourself from https://mimic.physionet.org/. Specifically, download the CSVs. To run decompensation prediction task on MIMIC-III bechmark dataset, you should first build benchmark dataset according to https://github.com/YerevaNN/mimic3-benchmarks/.

After building the **in-hospital mortality** dataset, please save the files in ```in-hospital-mortality``` directory to ```data/``` directory.

## Run ConCare

All the hyper-parameters and steps are included in the `.ipynb` file, you can run it directly.
