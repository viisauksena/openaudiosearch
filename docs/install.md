# Installation

Installation Steps:
* Elasticsearch
* miniconda
* Additional packages
* Conda environment
* Download models


### Elasticsearch
Install an Elasticsearch instance. \#FIXME native/docker

### miniconda
Download miniconda installer (Python 3.8) from [here](https://docs.conda.io/en/latest/miniconda.html). Run the installer script `bash Miniconda3-latest-Linux-*.sh` in Terminal and follow the prompts. After installation is completed, re-open Terminal or `source ~/.bashrc`.

### Additional packages
Install additional packages on your machine:  
`sudo apt-get install portaudio19-dev`

### Conda environment
Creat a new conda environment, using the yaml file provided in project root directory.  
`conda env create -f environment.yml`

Activate environment: `conda activate oas`

### Download models
Either download and extract the following models repositories in `~/models`:
* [VOSK Standard DE](https://alphacephei.com/vosk/models/vosk-model-de-0.6.zip)
* [VOSK Speaker Identification](https://alphacephei.com/vosk/models/vosk-model-spk-0.4.zip)
* [deepspeech-german](https://drive.google.com/drive/folders/1PFSIdmi4Ge8EB75cYh2nfYOXlCIgiMEL)

Or, run \#FIXME script to automate downloading and extraction of models.
