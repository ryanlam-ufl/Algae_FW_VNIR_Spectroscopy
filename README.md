# Algae & FW VNIR Spectroscopy
This repository contains Python code for building partial least squares regression (PLSR), principal component regression (PCR), random forest regression (RFR), support vector regression (SVR), and convolutional neural network (CNN) models correlating spectral scans of dry spirulina algae, chlorella algae, and post-consumer food waste to their lipid, protein, and carbohydrate content. 

# Proximate Analysis Reports
Each of the three Report .pdf contain the results of the proximate analyses conducted by Midwest Laboratories of the three biomass materials.

Note: The proximate analysis for the food waste report was performed on a mix of unadulterated, baseline food waste sample and lipid-spike baseline sample at 2%. Baseline biochemical composition of the food waste used in model development was calculated using mass fraction.


# Spectral .csv files 
Each of the three .csv files contains 175 compiled spectral scans of the unadulterated, baseline sample along with the macromolecule spike samples at 2, 5, 8, and 10% w/w
These three .csv files are used to build in the PLSR_PCR_Models.py file to build the 5-fold cross validation PLSR and PCR models, initially developed in a Google Colab Notebook, a hosted Jupyter Notebook.

Note: The ID of each spectral scan is identified under the heading, "Import and Organize Spirulina, Chlorella, and FW Data" in the PLSR_PCR_Models.py file.

# RFR_SVR_CNN_code.zip
This zip file contains both the spectra files and the Python code used to develop the RFR, SVR, and CNN models for each of the three biomass materials. 
