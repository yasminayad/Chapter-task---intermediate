# Chapter-task---intermediate
This repository contains a Jupyter Notebook that focuses on cleaning and preprocessing a dataset of motorcycles. The dataset contains various attributes related to different motorcycle models, and this notebook ensures data consistency, handles missing values, and prepares the data for further analysis and visualization.
The dataset contains various attributes, including:
Model , Brand , Year , Displacement (ccm) , Engine cylinder , Engine stroke , Gearbox , Fuel system , Cooling system , Transmission type

#Data Cleaning Steps
The following columns were removed as their large number of nan values:
Power (hp) , Fuel control , Dry weight (kg) , Wheelbase (mm) , Seat height (mm)

Filled missing values in Gearbox with the most common value (mode).

Filled missing values in Fuel capacity (lts) with the column's mean value.

Filled missing values in Fuel system with the most common value (mode).

Converted Year column to string format and removed unnecessary text (CE).

Standardized Category by keeping only the first category if multiple were listed.

Ensured Displacement (ccm) is stored as a numerical (float) value.

Cleaned Gearbox column to standardize values (e.g., converting variations like 6-speed manual → 6-speed).

Cleaned Fuel system column:

Converted all values to lowercase.

Removed extra details after a dot (.), keeping only the main system type.

Cleaned Cooling system column:

Converted all values to lowercase.

Standardized variations (e.g., oil & air and oil and air → oil & air).
