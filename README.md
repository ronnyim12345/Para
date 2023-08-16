# hw4
Project 4 - Parallel Programming

HOW TO USE:

OPENMP:

1.) Change directory to "3way-openmp"

2.) Create the "build" directory

3.) Load the proper modules for running the cmake.

4.) Change directory to "build"

5.) cmake ..

6.) make

7.) Output file should be "hw4_openmp"

8.) Move up one directory by typing "cd .."

9.) Edit the bash script to change the directory to your home directory name

10.) Run the sbatch file by typing "sbatch openmp_sbatch_lowtier.sh"

11.) Confirm that a slurm output file has been created by typing "ls"

12.) After the task has finished running run the "outputresults.sh" file by typing "./outputresults.sh"

13.) Repeat those steps for pthread and mpi.


Troubleshooting:

If you run into issues with running the bash scripts make sure to use the command: 'chmod u+x filename' to get it executable rights.

If outputresults.sh doesn't for you try running the command 'seff jobID' where the job ID is the ID of the slurm out file.


    
