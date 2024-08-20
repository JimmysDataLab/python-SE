### Setup & Run Jupyter Notebooks w/ Virtual Environment & Kernels (Local)

4. Create virtual environment and activate it.
	It is best practise to create standalone virtual envs.
	```bash
 	mkdir -p <venvpath>
 	cd $_
	python3 -m venv <envname>
 	source <envname>/bin/activate"
1. Clone repo
	```bash
	mkdir -p <projectpath>
 	cd <projectpath>
	git clone <url> 
	```
2. Add .gitignore
	```bash
 	cd <repo>
 	touch .gitignore
 	echo ".ipynb_checkpoints/" >> .gitignore
	```
6. Install ipykernel
	```bash
	pip install ipykernel
	```
7. Create new kernel
	```bash
	python3 -m ipykernel install --user --name=<kernelname>	
	```
8. Start Jupyter
	```bash
	jupyter notebook
	```
  
