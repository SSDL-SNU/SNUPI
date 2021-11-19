# SNUPI
  Structured Nucleic Acids Programming Interface is a multiscale analysis framework for nucleic acid nanostructures based on the finite element model with the geometric and mechanical properties of DNA characterized by molecular dynamics simulation.  

# Updates
  - v2.00
    * Wireframe and topologically-closed circular design can be analyzed directly from caDNAno input files.
    * Analysis results can be exported in the oxDNA input file format.
    * The model for the single-stranded DNA part is improved.
  - v1.01
    * Support for commandline execution (see protocol.pdf)
    * Support for mac and linux OS
    * Modification of miscellaneous errors

# Prerequisite
  - The correct version of the MATLAB Runtime (version 9.6 (R2019a)) must be installed.
  - Download and install its Windows version at "http://www.mathworks.com/products/compiler/mcr/index.html".

# Procedure (win)
  - Execute 'SNUPI_GUI.exe'
  - Select a cadnano design file and options.
  - Run SNUPI and analyze the results.
  - Refer to 'readme' and 'Protocol.pdf' for more details on the program.
  
# Procedure (mac, linux)
  - Modify 'Input.txt' in the FILE folder to indicate a design file.
  - In the 'Input.txt' file, <lattice_type> and <file_directory> should be written.
  - (In terminal) To give a permission to execute, chmod +x *
  - (In terminal) Execute SNUPI in the FILE folder, ./run_SNUPI.sh <matlab_runtime_directory>
  - GUI mode is not supported.
  - Refer to 'readme' and 'Protocol.pdf' for more details on the program.
  
# Please cite the following paper when SNUPI is used.
  - Rapid Computational Analysis of DNA Origami Assemblies at Near-Atomic Resolution, ACS Nano (2021)
  - https://pubs.acs.org/doi/full/10.1021/acsnano.0c07717
