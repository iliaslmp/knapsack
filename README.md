
# Knapsack Solver
This repository contains C++ code about the knapsack 0-1 problem
The generator folder contains two very helpful tools to create one knapsack 0-1 problem or a pack of problems
The problems can solved using 6 algorithms:
   a. Greedy approach
   b. Brute force
   c. Branch and bound
   d. Dynamic programming
   e. Dynamic OR-Tools solver
   f. Integer OR-Tools solver
The solution of each problem is stored in a file
The solution of pack of problem is stored in a CSV file for generating statistics

## Instructions:
1. Download this repository
2. Run the file Knapsack.exe
3. On the menu select the option 8:Create all knapsack problems (320 files)
   This selection will create the folder knapsack_problems with 320 knapsack problems files  that can be solved using the Knapsack.exe
4. On the menu select the algorithm with which you want to solve all problems or one of then   
   You can create a CSV files with the solutions of all problems for each algorithm separately or for all algorithms     

==================================
Knapsack.exe          This the main solver with many features
or_tools_dynamic.exe  Util that used by the main file to solve a problem using the OR-Tools Dynamic algorithm
or_tools_integer.exe  Util that used by the main file to solve a problem using the OR-Tools Integer algorithm
knapsack_gen.exe      Util that used by the main file to create a knapsack problem

All of these files has to be to the same folder

## Other folders:
generator folder: 
    knapsack_gen.c      : Contains the code the knapsack generator (C++ code)
    knapsackFilesCreator: This utils calls the knapsack generator to create 320 probles files (C++ code)
    oneClickCreator     : MsDos batch file that call the knapsackFilesCreator (C++ code)

//===================================
## Required hardware and software:
CPU: 64bit
Windows 64bit
Ram: 10Gb

//===================================
## Licence: This code is created by Ilias Lamprou
You can use it for educational use
For commercial use you have get the permission of the owner

