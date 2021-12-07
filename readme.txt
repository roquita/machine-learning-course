Previously install virtualenv using "pip install virtualenv"
1- Go to project dir.
2- Open cmd and run "python3 -m venv {ENV_NAME}"
3- Run ".\{ENV_NAME}\Scripts\activate" to activate virtual env
4- Run "pip install ipykernel"
5- Add all python packages you need.
6- Add kew kernel with "python -m ipykernel install --user --name={ENV_NAME}"
7- Verify with "jupyter kernelspec list"
8- Run "deactivate"
9- Your new kernel is ready to use
10- Run jupyter with "jupyter notebook --notebook-dir=Z:/"



To check packages: pip freeze
To create requirements: pip3 freeze > requirements.txt

To ADD kernel to jupyter: python -m ipykernel install --user --name={ENV_NAME}
To CHECK list of kernels: jupyter kernelspec list
To REMOVE a kernel: jupyter kernelspec uninstall {ENV_NAME}
To open jupyter: jupyter notebook --notebook-dir=Z:/
