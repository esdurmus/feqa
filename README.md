# FEQA: A Question Answering Evaluation Framework for Faithfulness Assessment in Abstractive Summarization

This repository contains code for the paper

> **FEQA: A Question Answering Evaluation Framework for Faithfulness Assessment in Abstractive Summarization**.
> Esin Durmus, He He and Mona Diab
> In proceedings of ACL 2020.
> https://www.aclweb.org/anthology/2020.acl-main.454/

## Dependencies
- Python 3.6

Install all Python packages: `pip install -r requirements.txt`. 

## Data
The faithfulness annotations we collect for CNNDM and XSum are going to be added soon. 

## Code
Trained models for question generation and question answering systems are under [this drive](https://drive.google.com/drive/folders/1GrnfJxaK35O2IEevv4VbiwYSwxBQVI2X?usp=sharing).

1. Download **squad1.0** from Google Drive and place it under **qa_models** directory. 
2. Download **checkpoints** folder and place it under **bart_qg** directory. 

**feqa.py**: includes the code to run feqa pipeline (question generation, answering and metric calculation). 

See **run_feqa.ipynb** notebook for an example on how to run the pipeline for the given documents and output summaries. 

## Contact
You can send an email to ed459[at]cornell[dot]edu, if you have any questions or comments. 


