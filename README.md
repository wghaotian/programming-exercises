Programming Exercises
=====================

[![Running Test in CI](https://github.com/FZJ-PGI-12/programming-exercises/actions/workflows/python-package-conda.yml/badge.svg)](https://github.com/FZJ-PGI-12/programming-exercises/actions/workflows/python-package-conda.yml)

Programming exercises for the [lecture on Near-term Quantum Computing in the summer term 2024 at RWTH Aachen](https://www.fz-juelich.de/en/pgi/pgi-12/activities/teaching/summer-term-2024/near-term-quantum-computing)

Setup environment
-----------------

 - Install [miniforge](https://github.com/conda-forge/miniforge) to set up an environment for the Python installation. Alternative: Anaconda or Miniconda.
 - Create new conda environment
    
       conda create -n programming-exercise python=3.12  

 - Activate the new environment

       conda activate programming-exercise

 - Clone this repository and enter the directory

       git clone https://github.com/FZJ-PGI-12/programming-exercise.git
       cd programming-exercise

 - Install the dependencies

       pip install -r requirements.txt

 - Start the notebook

       jupyter notebook
 
 - **Test your setup** by running all cells. There should be no errors 

Tests
-----

Test your environment with

    pytest --nbval-lax *.ipynb

There should be no errors

