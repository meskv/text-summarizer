# text-summarizer



* Run the template.py file -> create all the requiled template file structure
    ```bash
    python template.py
    ```
* create a virtual environment
    ```
    # conda create -n env_name python=3.8 -y
    ```
    ```bash
    conda create -n textSum python=3.8 -y
    ```
* activate the environment
    ```bash
    conda activate textSum
    ```

## Requirements
* transformers
* transformers[sentencepiece]
* datasets
* sacreblue
* rouge_score
* py7zr
* pandas
* nltk
* tqdm
* PyYAML
* matplotlib
* torch
* notebook
* boto3
* mypy-boto3-s3
* python-box==6.0.2
* ensure==1.0.2
* fastapi==0.78.0
* uvicorn==0.18.3
* Jinja2==3.1.2
* -e .

* install all the requirements
    ```bash
    pip install -r requirements.txt
    ```