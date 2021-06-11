# Data Analysis Functions

Python library to analyze and make Barn Owl sound localization data accessible to the public. Functions to easily analyze and search the data from txt files without having prior knowledge of how the data is organized. The functions can create basic tuning curve graphs as well as grab the data from the txt files for further analysis. Must have txt files stored locally on computer for code to work. 


The data comes from extracellular recordings of isolated LLDa neurons in four anesthetized adult female barn owls. These recordings were made with tungsten electrodes. The data consist of spike counts in response to sound stimuli with fixed ITD and fixed frequencies for tones. Methods to collect data are described further in the Journal of Neurophysiology, Varability Reduction in Interaural Time Difference Tuning in the Bar Owl by Brian J. Fischer and Masakazu Konishi.


Dropbox Data Link: https://www.dropbox.com/sh/y3hpo7c86qopg0j/AABKuTlur0AFjrNfs9JfaG7Ea?dl=0


Reference
Fischer, B. J., & Konishi, M. (2008). Variability Reduction in Interaural Time Difference Tuning in the Barn Owl. Journal of Neurophysiology, 100(2), 708-715. doi:10.1152/jn.90358.2008


# Step by Step Instructions:

1. Go to dropbox folder via dropbox link, https://www.dropbox.com/sh/y3hpo7c86qopg0j/AABKuTlur0AFjrNfs9JfaG7Ea?dl=0, to download the data. Store this on a known  location on your computer.
2. Download both "Tutorial Notebook" and "functions" notebooks.
3. Set the location variable in the notebook titled "Tutorial Notebook" to the location of where the data is stored on your computer.
4. Use the dataframe printed in the Tutorial Notebook to find neurons you might be interested in.
5. Locate the names of the neurons that you want to do further analysis on. This is found in the "Name" collumn of the dataframe. The name is a string in the format of a three digit owl name, two digit trial number, and the data of the experiment.
6. Browse the three analysis functions, filename_search, tuningCurveName, and getData. (Documnetation for these functions is found in the Tutorial Notebook.
