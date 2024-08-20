### Setup & Run Jupyter Notebooks w/ Virtual Environment & Kernels (Local)

1. Clone repo
	```bash
	BASE_PATH="$HOME/Desktop/JimmysDataLab"
	REPO_URL="https://github.com/JimmysDataLab/python-SE.git"
	mkdir -p $BASE_PATH
	git clone $REPO_URL "$BASE_PATH/$(basename $REPO_URL .git)"
	```
	
3. Create virtual environment and activate it.
	It is best practise to create standalone virtual envs.
	```bash
 	REPO_URL="https://github.com/JimmysDataLab/python-SE.git"
 	VENV_PATH="$HOME/Desktop/venvs"
 	ENV_NAME="$(basename $REPO_URL .git)-env"
 	echo $ENV_NAME
	python3 -m venv $ENV_NAME
 	source "$VENV_PATH/$ENV_NAME/bin/activate"
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
  
