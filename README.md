Programming Exercises
=====================

[![Running Test in CI](https://github.com/FZJ-PGI-12/programming-exercises/actions/workflows/python-package-conda.yml/badge.svg)](https://github.com/FZJ-PGI-12/programming-exercises/actions/workflows/python-package-conda.yml)

Programming exercises for the lectures of Tobias Stollenwerk

 - [Summer term 2025 - Lecture on Near-term Quantum Computing in at RWTH Aachen](https://www.fz-juelich.de/en/pgi/pgi-12/activities/teaching/summer-term-2025/near-term-quantum-computing) see [folder](./2025-summer-rwth/)
 - [Summer term 2024 - Lecture on Near-term Quantum Computing in at RWTH Aachen](https://www.fz-juelich.de/en/pgi/pgi-12/activities/teaching/summer-term-2024/near-term-quantum-computing) [folder](./2024-summer-rwth/)

Setup environment
-----------------

 - Install [miniforge](https://github.com/conda-forge/miniforge) to set up an environment for the Python installation. Alternative: Anaconda or Miniconda.
 - Create new conda environment
    
       conda create -n programming-exercise python=3.12  

 - Activate the new environment

       conda activate programming-exercise

 - Clone this repository and enter the directory

       git clone https://github.com/FZJ-PGI-12/programming-exercise.git
       cd programming-exercise/<lecture-folder>

 - Install the dependencies

       pip install -r requirements.txt

 - Start the notebook

       jupyter notebook
 
 - **Test your setup** by running all cells. There should be no errors 

Tests
-----

Test your environment with

    cd <lecture-folder>
    pytest --nbval-lax *.ipynb

There should be no errors

