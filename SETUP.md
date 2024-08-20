### Setup & Run Jupyter Notebooks in VS Code w/ Virtual Environment & Kernels (Remote & Local)

1. Create project folder and change directory into that folder
	```bash
	mkdir ~/Desktop/GitHub/<reponame> && cd $_
	
	```
2. Create virtual environment
	```bash
	python3 -m venv <envname>
	
	```
3. Activate virtual environment
	```bash
	source <envname>/bin/activate
	
	```
4. Install ipykernel
	```bash
	pip install ipykernel
	
	```
 5. Create new kernel
	```bash
	python3 -m ipykernel install --user --name=<kernelname>
	
	```
6. Start Jupyter
	```bash
	jupyter notebook
	
	```
  
