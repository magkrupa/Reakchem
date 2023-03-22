# Reakchem
Welcome to the Microservice in Python for Running SMARTS Reactions on SMILES-Formatted Reactants.
—---------------------------------------------------------------------------------------------------------------------

This code is designed to perform chemical reactions on reactants supplied in the SMILES format. To get started, the first step is to install and import the necessary packages: 
●	RdKit - which is an open source toolkit for cheminformatics and machine learning (https://www.rdkit.org/docs/Overview.html)
●	Itertools module a functions creating iterators for efficient looping (https://docs.python.org/3/library/itertools.html) 
A list of the required packages and the appropriate import statements can be found in the first code cell. Simply run the cell to import the necessary packages. The program was written with Python version 3.11 which is necessary to run the program. The program can be run using Jupyter Notebook.

It is important to provide the proper SMILES format of the molecule, which represents a linear string representation of its molecular structure. For more information on the SMILES format, please refer to the following Wikipedia website: https://en.wikipedia.org/wiki/Simplified_molecular-input_line-entry_system

After entering the SMILES format, the code will validate the format and ensure that the molecule is chemically reasonable.

The next step is to provide the reaction in SMARTS format, which represents a pattern-matching language for describing molecular structures. For more information on the SMARTS format, please refer to the following Daylight Theory website: https://www.daylight.com/dayhtml/doc/theory/theory.smarts.html

After entering the SMARTS format, the code will validate the format and ensure that it is correct and reactants from SMILES are compatible with reactants provided with SMARTS.

Please note that any additional reactants included in the SMARTS format but not present in the molecule should be specified without an atom number. For example, use "Cl" instead of "Cl99".

The code can be easily modified to do the reaction on multiple molecules, that is why the defined functions are used to adapt to work on multiple molecules.

The Microservice in Python for Running SMARTS Reactions on SMILES-Formatted Reactants has been designed to be easily modified for reactions on multiple molecules, and defined functions are provided to facilitate this process. By default, the program will output the number of unique product sets from the reaction, and up to 10 molecules can be visualized. It is important to note that the number of unique sets is not equal to the number of unique molecules, as one set can contain multiple molecules. If the number of unique molecules exceeds 10, the max value can be modified to accommodate the desired number.

Thank you for using this code. I hope you find it useful and enjoyable to use.
