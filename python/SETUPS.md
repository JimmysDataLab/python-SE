### Setup & Run Jupyter Notebooks w/ Virtual Environment & Kernels (Local)

1. Clone repo
	```bash
	mkdir -p <projectpath>
 	cd <projectpath>
	git clone <url> 
	```
	
3. Create virtual environment and activate it.
	It is best practise to create standalone virtual envs.
	```bash
 	cd <venvpath>
	python3 -m venv <envname>
 	source <envname>/bin/activate"
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
  
