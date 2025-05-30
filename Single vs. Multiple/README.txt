README.txt


**Overview**
The files final_chr_singletrip_data.xlsx and final_chr_multitrip_data.xlsx are derived from Updated_Weather_CH Robinson.xlsx. They were split according to whether a shipment is a single-stop (single trip) or a multi-stop (multiple trip).

- Updated_Weather_CH Robinson.xlsx: Original dataset containing weather and shipment information.
- final_chr_singletrip_data.xlsx: Contains data where each shipment has only one stop.
- final_chr_multitrip_data.xlsx: Contains data where each shipment has multiple stops.


**How to Use**
Download all three Excel files:

- Updated_Weather_CH Robinson.xlsx
- final_chr_singletrip_data.xlsx
- final_chr_multitrip_data.xlsx

Place these files on your local computer. Choose any folder location that suits your workflow.

Open the notebook (e.g., Single_vs_Multiple.ipynb).



**Update File Paths**
In the last module of the notebook (or wherever the paths are specified), change the file paths to match the location where you placed the three Excel files on your local machine. For example:

file_path_single = r"your_local_path\final_chr_singletrip_data.xlsx"
file_path_multi  = r"your_local_path\final_chr_multitrip_data.xlsx"
file_path_weather = r"your_local_path\Updated_Weather_CH Robinson.xlsx"
Make sure to use the correct file path format (e.g., C:\path\to\folder\filename.xlsx on Windows).



**Notes**
These Excel files are essential for the Single_vs_Multiple.ipynb code to run properly.

Ensure that the Excel file names are exactly the same as stated above. If the file names differ, you will need to update the code references accordingly.

If you have any additional configuration changes (like environment variables, Python paths, etc.), make sure those are set up prior to running the notebook.


**Contact**
For any questions or issues regarding the data files or the notebook, please reach out to the project maintainer by email: chi.ce@northeastern.edu 