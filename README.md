# Futuremat_public
A public available version of furturemat code that contains core functionalities developed in our lab.

# Get starting with  futuremat_public
    ```bash
    git clone https://github.com/yangjackie/futuremat_public.git

    cd ~/<YOUR PROJECT DIRECTORY>/futuremat_public

    python3 setup.py build_ext --inplace
    ```

# Change PythonPath (Not recommend, need to be alternated in future)
    ```bash
    export PYTHONPATH="<work_dir>/futuremat_public"
    
    echo $PYTHONPATH # double check the PATH
    ```
# Install Pymatgen
    conda install --channel conda-forge pymatgen

# set up POTCAR directory

For **pymatgen**

    pmg config -p <UR/VASP/POTCAR> <Your dir for POTCAR>

For **futuremat_public**

Edit in settings.py
    
    vasp_pp_directory="<UR/VASP/POTCAR>"
    MPRest_key="" #get from materials project
    functional="<optional>" # such as 'pbe' et al. currently only support 'pbe'

    



