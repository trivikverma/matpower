# matpower
Use the python version of Matpower to extract Admittance matrix for further processing

## Source Code for extracting admittance matrix from case data in matpower / pypower

### Install pypower

1. Update Conda
`conda update -n base conda`
- if you don't have the package manager conda, you can install it from anaconda (website)
2. Create a new virtual environment with the conda package manager
`conda create -n <env_name> -c pypower`
or using the pip package manager
`pip install pypower`
3. Activate the environment
`source activate <env_name>`
4. Test within the Jupyter Notebook if you may using the getAdmittanceMatrix notebook

If you cannot load the **virtual environment** in your _jupyter notebook_, try the following,

Install the ipython kernel module into your virtualenv
`pip install ipykernel`

Now run the kernel *self-install* script:
`python -m ipykernel install --user --name=my-virtualenv-name`
