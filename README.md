# IDSL.SpectraPrediction

Predicting MS/MS spectra for chemical compounds using machine learning (ML) methods.

For a given list of Name, SMILES and ESI Adduct, we can predict the MS/MS spectra using machine learning. Additional columns will be added into the spectra metadata block. 
Those spectra will be uploaded and shared via the Zenodo.org repository. 

An example of predicted spectra for Metabolon's data dictionary (Open-Access Publications https://zenodo.org/records/10974865 ) is made available at ([Zenodo link](https://zenodo.org/records/13756168)). 

Submit a chemical list to the issues section ( https://github.com/idslme/IDSL.SpectraPrediction/issues ). Example input format is available here https://github.com/idslme/IDSL.SpectraPrediction/blob/main/IDSL_spectra_prediction_input_format_august_2024.csv . Our team will simulate the spectra and reply back with the Zenodo.org accession. 

MS/MS Spectra are predicted using the MS-PRED and ICEBERG framework ( https://github.com/samgoldman97/ms-pred/tree/main ) 

## Citations

- ️️️️  ❄️ ICEBER️️G ❄️: [Inferring CID by Estimating Breakage Events and Reconstructing their Graphs](http://arxiv.org/abs/2304.13136)
-   Goldman, Samuel, Janet Li, and Connor W. Coley. "Generating molecular fragmentation graphs with autoregressive neural networks." Analytical Chemistry 96.8 (2024): 3419-3428.


