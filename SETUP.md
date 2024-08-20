### Setup & Run Jupyter Notebooks w/ Virtual Environment & Kernels (Local)

1. Clone repo
	```bash
	BASE_PATH="$HOME/Desktop/JimmysDataLab"
	REPO_URL="https://github.com/JimmysDataLab/python-SE.git"
	mkdir -p $BASE_PATH
	git clone $REPO_URL "$BASE_PATH/$(basename $REPO_URL .git)"
	```
	
3. Create virtual environment
	```bash
	python3 -m venv <envname>
	
	```
4. Activate virtual environment
	```bash
	source <envname>/bin/activate
	
	```
5. Install ipykernel
	```bash
	pip install ipykernel
	
	```
 6. Create new kernel
	```bash
	python3 -m ipykernel install --user --name=<kernelname>
	
	```
7. Start Jupyter
	```bash
	jupyter notebook
	
	```
  
