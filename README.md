# Illumina-data-toolset
## HPC command
For HPC user, once you login via login node. The first command is to enter compute node. 

`srun --pty bash`

## Basic Bash commands

- [Beginner's Guide to the Bash Terminal](https://www.youtube.com/watch?v=oxuRxtrO2Ag)

## To use Conda

- Introduction (use Python as example) [Anaconda (Conda) for Python - What & Why?](https://www.youtube.com/watch?v=23aQdrS58e0)

- [Conda command cheatsheet](https://docs.conda.io/projects/conda/en/latest/user-guide/cheatsheet.html)

1. Download the installer:

    [Miniconda installer for macOS.](https://docs.conda.io/en/latest/miniconda.html)
2. Install:

    `bash Miniconda3-latest-MacOSX-x86_64.sh`
    
3. Follow the prompts on the installer screens.
4. To make the changes take effect, close and then re-open your terminal window.
5. Build a environment, named my_env, with a yaml file, which tells what packages need to be installed.

    `conda env create --name my_env --file my_pkg.yaml`

6. Activate enviroment.

    `conda activate my_env`
    
You will see your prefix change from base to my_env on the screen of terminal

```
(base) mymacbook:~ user$ conda activate my_env
(my_env) mymacbook:~ user$ 
```
This indicates your are in the my_env environment. You have to activate environment in each time of login.

## bcl2fastq
## Illumina run metrics
## fastqc
## multiqc