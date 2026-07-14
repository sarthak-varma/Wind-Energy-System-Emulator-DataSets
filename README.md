# Wind-Energy-System-Emulator-DataSets
This dataset contains the I-V and P-V values for different wind conditions for using it with a Programmable Power Supply for Emulation of Wind Energy System.

This dataset contains the baseline current-voltage (I-V) characteristic profiles used to emulate a micro wind turbine using a programmable DC power supply. The data serves as the foundation for validating standalone Maximum Power Point Tracking (MPPT) control systems without requiring a physical wind tunnel setup.

The dataset includes:
1. Wind Turbine I-V Curves: Current and voltage data matrices simulated across a comprehensive range of operating wind speeds (m/s).
2. Aerodynamic & Mechanical Mappings: Corresponding P-V characteristics reflecting the turbine's power coefficient (Cp) curves.

To use the dataset, extract the I-V data points from the XLSX file sheet named "IV Computed" and save it as a .csv file. Then, import this file into National Instruments LabVIEW or proprietary programmable power supply software for writing the I-V values onto the programmable power supply. By sweeping these look-up tables (LUTs), the hardware power supply accurately mimics the non-linear electrical output of a real wind turbine generator under dynamic wind conditions, enabling hardware-in-the-loop validation of model-independent MPPT algorithms.
