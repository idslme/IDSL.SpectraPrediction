# IDSL.SpectraPrediction csv format

Required columns for input csv are:
- name
- adduct
- smiles

Optional information such as InChI (inchi), InChIKey (inchikey), formula (formula), molecule fingerprint (fingerprint) can be included in the input csv file in their respective column name in bracket and will be transfered to the result .msp file. These entries are not used during prediction and does not interfere with the result. 

Other columns can exist in the input csv file, but they will not be used or added to the prediction result. 

Order of columns in csv input file does not need to follow sample csv file, however, all required columns must exist in the input csv.