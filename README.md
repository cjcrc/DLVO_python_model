# DLVO_python_model
Python code in .py format (dlvo_kao_NaCl_CuCl_TinPM.py) for model run and figure generation of kaolinite-sand DLVO model with and without copper in Figure 7 of 'In situ quantification of colloidal kaolinite transport and attachment in porous media using positron emission tomography' (DOI) and python code in .py format for radiolabeling bar chart plot with data (barPlots_radiolabel.py)

Positron Emission Tomography data for high saline and low saline + increased flow rate runs are included as a .zip file (ottawaSand_kaolinite_PET_data.zip). 'raw_pet_load_coarsen_kaolin.py' is a python script that uses a .raw file from the PET zip folder to process and look at the data. 'makeCSV_for3DPET_lowSalineandHighFlowRate.py' is a python script that uses a .raw file from the PET zip folder and will make processed .csv files that can be used to make 3D plots. 'plot_3d.py' will use the .csv files that the previous script made and will generate 3D .png images. A sample of .csv output of 3D model generation is inlcuded in the folder 'lowSaline_highFlowRate_PET_for3D' - this includes data from the low saline portion and the high flow portion of the PET images. An example .png output file is included 'may2022_cu64_lowSaline_0' - this represents timestep 0.

UV-Vis breakthrough curve data is included as a .csv (uvVis_data.csv). A python script ('uvVis_btc_transportPorMed_04Apr2023.py') is included that will use the .csv uv-vis data and make the plot from the paper. Gamma count data with pore volume calucations are included as a .csv (gammaCounts.csv). All calibration curve data used in the linear regression for uv-vis absorbance to mol conversion are included as a .csv (calibrationCurves_abs_mol).
