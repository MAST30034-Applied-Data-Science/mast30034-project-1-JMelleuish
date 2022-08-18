# MAST30034 Project 1 README.md
- Name: John Melleuish
- Student ID: 1171367

## README example
**Requirements:**

absl-py==1.2.0
appnope==0.1.3
asttokens==2.0.8
astunparse==1.6.3
attrs==22.1.0
backcall==0.2.0
Bashutils==0.0.4
branca==0.5.0
cachetools==5.2.0
certifi==2022.6.15
charset-normalizer==2.1.0
click==8.1.3
click-plugins==1.1.1
cligj==0.7.2
cycler==0.11.0
debugpy==1.6.3
decorator==5.1.1
entrypoints==0.4
executing==0.10.0
Fiona==1.8.21
flatbuffers==1.12
folium==0.12.1.post1
fonttools==4.35.0
gast==0.4.0
geopandas==0.11.1
google-auth==2.10.0
google-auth-oauthlib==0.4.6
google-pasta==0.2.0
grpcio==1.47.0
h5py==3.7.0
idna==3.3
importlib-metadata==4.12.0
ipykernel==6.15.1
ipython==8.4.0
jedi==0.18.1
Jinja2==3.1.2
joblib==1.1.0
jupyter-client==7.3.4
jupyter-core==4.11.1
keras==2.9.0
Keras-Preprocessing==1.1.2
kiwisolver==1.4.4
layers==0.1.5
libclang==14.0.6
Markdown==3.4.1
MarkupSafe==2.1.1
matplotlib==3.5.3
matplotlib-inline==0.1.3
munch==2.5.0
nest-asyncio==1.5.5
numpy==1.23.2
oauthlib==3.2.0
opt-einsum==3.3.0
packaging==21.3
pandas==1.4.3
parso==0.8.3
patsy==0.5.2
pexpect==4.8.0
pickleshare==0.7.5
Pillow==9.2.0
pip==22.2.2
prompt-toolkit==3.0.30
protobuf==3.19.4
psutil==5.9.1
ptyprocess==0.7.0
pure-eval==0.2.2
py4j==0.10.9.5
pyarrow==9.0.0
pyasn1==0.4.8
pyasn1-modules==0.2.8
Pygments==2.13.0
pyparsing==3.0.9
pyproj==3.3.1
pyspark==3.3.0
python-dateutil==2.8.2
pytz==2022.2.1
PyYAML==6.0
pyzmq==23.2.1
requests==2.28.1
requests-oauthlib==1.3.1
rsa==4.9
scikit-learn==1.1.2
scipy==1.9.0
seaborn==0.11.2
setuptools==63.4.1
Shapely==1.8.4
six==1.16.0
sklearn==0.0
stack-data==0.4.0
statsmodels==0.13.2
tensorboard==2.9.1
tensorboard-data-server==0.6.1
tensorboard-plugin-wit==1.8.1
tensorflow-estimator==2.9.0
tensorflow-macos==2.9.2
termcolor==1.1.0
threadpoolctl==3.1.0
tornado==6.2
traitlets==5.3.0
typing_extensions==4.3.0
urllib3==1.26.11
wcwidth==0.2.5
Werkzeug==2.2.2
wheel==0.37.1
wrapt==1.14.1
zipp==3.8.1

**Research Goal:** My research goal is tip analysis for credit card payments for NYC taxis.

**Timeline:** The timeline for the research area is Jan 2018 - Dec 2019.

To run the pipeline, run the following files in order:
1. `(taxi) preprocessing.ipynb`: This downloads the raw data into the `data/raw` directory and details all the preprocessing steps for the taxi dataset. finally producing the 'taxi' folder in `data/curated`.
2. `(Weather) preprocessing.ipynb`: This downloads the raw data into the `data/raw` directory and details all the preprocessing steps for the weather dataset. finally producing the 'weather.parquet' in `data/curated`.
3. `Analysis.ipynb`: This notebook outputs the combined dataset and is used to conduct analysis on the curated data.
4. `Statistical_Modelling.ipynb`: This notebook is used for creating and discussing the 3 modelled used to preict taxi tip amounts.
