# CAMERA Phase


0. login to NERSC Perlmutter::
    
    ssh <username>@perlmutter.nersc.gov
    
1. create conda environment and install dependencies::

    conda create -n phase -c conda-forge cupy matplotlib xraylib opencv
    conda activate phase
    
2. create a jupyterhub ipykernel::

    python -m ipykernel install --user --name phase --display-name "Python phase"::

3. clone my camera repository::
    
    git clone https://github.com/nikitinvv/camera
    
3. login in Jupyterhub at https://jupyter.nersc.gov/, allocate a GPU node, and select "Python phase" jupyter kernel

4. run jupyter notebooks from camera folder 
