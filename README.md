# SNUPI
  SNUPI is a multiscale analysis framework for the prediction of structured DNA assemblies.


# Updates
  - v3.01 (2024/01/24)
	* Minor error fix
  - v3.00 (2023/09/27)
	* Dynamic simulations
	* Restarting simulations
	* GPU acceleration
  - v2.01 (2022/01/18)
	* Minor error fix
  - v2.00 (2021/11/19)
	* Analysis of wireframe or topologically-closed designs
	* export of the oxDNA input file format.
	* Improved modeling of the single-stranded DNA
  - v1.01 (2021/02/23)
	* Support for command line execution (see protocol.pdf)
	* Support for mac and linux
	* Minor error fix
  - v1.00 (2021/01/07)
	* Initial upload


# Prerequisite
  - The correct version of the MATLAB Runtime should be installed.
  - v3: Runtime version R2022b (9.13)
  - v2: Runtime version R2019a (9.6)
  - v1: Runtime version R2019a (9.6)
  - Download link: http://www.mathworks.com/products/compiler/mcr/index.html


# How to run (Window)
  - Execute 'SNUPI.exe'
  - The example result files will be saved in the 'OUTPUT' folder.
  - To analyze custom design files, modify 'Input.txt'


# How to run (Linux)
- Open the terminal
- Move the current directory to the SNUPI folder
- Give permission to execute
	* chmod +x *
- Execute SNUPI
	* ./run_SNUPI.sh <mcr_directory>
- For example,
	* ./run_SNUPI.sh /usr/local/MATLAB/MATLAB_Runtime/R2022b
- The result files will be saved in the 'OUTPUT' folder.
- To analyze custom design files, modify 'Input.txt'


# How to run (Mac)
- Open the terminal
- Move the current directory to the SNUPI folder
- Give permission to execute
	* chmod +x *
- Execute SNUPI in the FILE folder using Terminal
	* ./run_SNUPI.sh <mcr_directory>
- For example,
	* ./run_SNUPI.sh /Applications/MATLAB/MATLAB_Runtime/R2022b
- The result files will be saved in the 'OUTPUT' folder.
- To analyze custom design files, modify 'Input.txt'

  
# Assign design files
  - Modify the 'Input.txt' file to assign design files.
  - In the 'Input.txt' file, <lattice_type> and <file_directory> should be denoted.
  - Use caDNAno design files (json and csv).
  - The percentage mark ('%') represents comments
  - Example designs were already assigned.
    

# Technical details
  - SNUPI framework (static analysis): Rapid computational analysis of DNA origami assemblies at near-atomic resolution, ACS Nano (2021), https://doi.org/10.1021/acsnano.0c07717
  - Improved model of single-stranded DNA: Characterizing and harnessing the mechanical properties of short single-stranded DNA in structured assemblies, ACS Nano (2021), https://doi.org/10.1021/acsnano.1c08861
  - Partition and relocation framework (free-form structures): Predicting the free-form shape of structured DNA assemblies from their lattice-based design blueprint, ACS Nano (2022), https://doi.org/10.1021/acsnano.1c10347
  - Langevin dynamics simulation: A computational model for structural dynamics and reconfiguration of DNA assemblies, Nature Communications (2023), https://doi.org/10.1038/s41467-023-42873-4
  - Graph neural network (Deep SNUPI): Prediction of DNA origami shape using graph neural network, Nature Materials (2024), https://doi.org/10.1038/s41563-024-01846-8
  
  
