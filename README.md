## Setup Environment 

conda create --name main-ds python=3.12.5
conda activate main-ds
pip install -r requirements.txt


## Setup Environment - Terminal

mkdir proyek_analisis_data
cd proyek_analisis_data
pipenv install
pipenv shell
pip install -r requirements.txt


## Run steamlit
streamlit run dashboard.py

