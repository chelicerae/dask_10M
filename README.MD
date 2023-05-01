## How to launch

1. I used `python3.7` for running this code, probably earlier versions of `python3` will work as well.
2. Install clean python virtual environment with `python3 -m venv env` or `conda create -n myenv python=3.7`.
3. Activate `env` with `source env/bin/activate` or `conda activate env`. 
4. With env activated intall dependencies written in `requirements.txt` with  `pip install -r requirements.txt` command.
5. Add newly created venv to `ipython notebook` with `python3 -m ipykernel install --user --name=env`.
6. Launch `jupyter notebook` **from** activated venv. 
7. With `jupyter notebook` launched pay attention to choose the correct kernel for `jupyter notebook`, it should be `env`, or whatever name you gave to env. 