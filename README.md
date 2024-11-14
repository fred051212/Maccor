Input Data
  TXT files exported from Maccor Data Analysis Software (MIMS Client 2).

![image](https://github.com/user-attachments/assets/77af57e6-c61b-424c-9b1e-13e58c7e4f37)

Notebook Files:
  VoltageProfile_Comment.ipynb: Extracts the active mass value directly from a 'comment' field where the mass is input at the start of a test.
  VoltageProfile_NoComment.ipynb: Requires manual input of the active mass for specific capacity calculations.
    Output: Saves cycle-specific voltage profile plots as PNG images, displaying voltage versus specific capacity (mAh/cm²).

Usage
  Data Preparation:
    Input data as TXT files exported from Maccor Data Analysis Software (MIMS Client 2).
    In VoltageProfile_Comment.ipynb, input the active mass in the 'comment' field at the start of the test.
    For VoltageProfile_NoComment.ipynb, manually set the active mass value for specific capacity calculations.

Cycle Selection: Define cycle_number to select specific cycles for analysis.

Run Cells: Execute each cell sequentially to generate and save the specific capacity plots.

Output: Images are saved in high resolution (DPI 500) as PNG files. Modify filename to customize output file names.    
