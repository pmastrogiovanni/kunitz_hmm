# Kunitz hmm project

The Kunitz/BPTI family of proteins, with their capability to inhibit the serin proteases, have demonstrated to be important in many biological processes, such as angiogenesis and coagulation.
The goal of the project was to build a tool that could recognize the domain, in order to better understand its role and its involvement in other interactions.

Hidden Markov Models are probabilistic models extensively used in the biological field, especially for the prediction of protein sequences. Because of their reliability in predicting consecutive residues, they were chosen as tool for the analysis of the Kunitz domain.

The HMM was trained using the HMMER software on a protein dataset containing the domain.
The model was able to classify correctly most of the data, with a MCC and Accuracy of 99%.

This repository contains the dataset and the and the full pipeline for the project. The code with detailed explanation can be found on the Jupyter notebook, while the report it's inside the PDF file.
