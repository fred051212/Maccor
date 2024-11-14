Voltage Profile Analysis
This Jupyter Notebook provides an analysis and visualization of battery voltage profiles across different cycles. It leverages the Pandas and Matplotlib libraries for data handling and plotting.

Project Structure
Notebook File: VoltageProfile_FN_Comment.ipynb — Contains the code to analyze voltage and capacity data across multiple cycles.
Output Image: The notebook saves voltage profile plots as PNG files for each specified cycle.
Features
Data Loading: Uses Pandas to handle cycle data stored in result_df.
Plot Customization: Provides customizable plot properties, including tick intervals, font styles, and plot limits.
Cycle Selection: Allows for analysis of specific charge-discharge cycles by specifying cycle_number.
Requirements
To run the notebook, ensure you have the following Python packages installed:

pandas
matplotlib
Usage
Load Data: Ensure result_df contains voltage and capacity data with the following columns: Capacity_Cycle{cycle}_C, Voltage_Cycle{cycle}_C, Capacity_Cycle{cycle}_D, and Voltage_Cycle{cycle}_D.
Set Parameters: Modify the cycle_number variable to analyze specific cycles.
Run the Notebook: Execute each cell in order to plot and save the voltage profile images.
Customization
Adjust plot properties, such as font size, linewidth, and axis labels, to match the desired visual style.
Customize the output file name by setting the filename variable.
