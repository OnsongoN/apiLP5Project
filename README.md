# apiLP5Project
we will build an API (Application Programming Interface) using FastAPI, for our Machine Learning Model


## Introduction

The objective of this project is to develop an API that can interact with machine learning models. This is a valuable solution for several reasons:

Model Confidentiality: The API acts as an intermediary, allowing users to interact with the model without revealing its underlying architecture.
User Convenience: Users familiar with APIs can readily access the model's capabilities through the API interface.
Scalability: APIs are well-suited for handling multiple user requests simultaneously, making the model accessible to a broader audience.
To achieve this, we'll first build and train four distinct machine learning models. These models will then be integrated into the API framework using FastAPI. Finally, the API can be deployed to allow users to interact with the models remotely via the internet protocol, as illustrated in the figure below.


## Description

1.  Build a ML model to predict the [Sepsis](https://www.kaggle.com/datasets/chaunguynnghunh/sepsis?select=README.md)(**Data set here**), 

2.  Build an API using Fast API, to embed the ML model built.

## Setup

Install the required packages from the requirements.txt to be able to run the evaluation locally.

You need to have [`Python 3`](https://www.python.org/) on your system (**a Python version higher than 3.10**). Then you can clone this repo and being at the repo's `root :: repository_name> ...`  follow the steps below:

- Windows:
        
        python -m venv venv; venv\Scripts\activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirement.txt  

- Linux & MacOs:
        
        python3 -m venv venv; source venv/bin/activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirement.txt  

1. **Create the Python's virtual environment** that isolates the required libraries of the project to avoid conflicts;
2. **Activate the Python's virtual environment** so that the Python kernel & libraries will be those of the isolated environment;
3. **Upgrade Pip, the installed libraries/packages manager** to have the up-to-date version that will work correctly;
4. **Install the required libraries/packages** listed in the `requirements.txt` file so that it will be allow to import them into the python's scripts and notebooks without any issue.

**NB:** For MacOs users, please install `Xcode` if you have an issue.

## Run FastAPI
  Live Demo:

  FastAPI:
 
  - Go to your browser at the following address, to explore the api and interact with the models :
        
      * http://127.0.0.1:8000/docs
      * http://127.0.0.1:8000/random_forest_predict
      * http://127.0.0.1:8000/logistic_regression_predict
      * http://127.0.0.1:8000/decision_tree_predict

![Alt text](<pics/Screenshot 2024-04-07 202420.png>)

To view the fastAPI in the dockerhub follow link:

* [Dockerhub](https://hub.docker.com/repository/docker/qochieng/sepssis-api/general)





## Resources
Here are some ressources you would read to have a good understanding of FastAPI :
- [Tutorial - User Guide](https://fastapi.tiangolo.com/tutorial/)
- [Video - Building a Machine Learning API in 15 Minutes ](https://youtu.be/C82lT9cWQiA)
- [FastAPI for Machine Learning: Live coding an ML web application](https://www.youtube.com/watch?v=_BZGtifh_gw)
- [Video - Deploy ML models with FastAPI, Docker, and Heroku ](https://www.youtube.com/watch?v=h5wLuVDr0oc)
- [FastAPI Tutorial Series](https://www.youtube.com/watch?v=tKL6wEqbyNs&list=PLShTCj6cbon9gK9AbDSxZbas1F6b6C_Mx)
- [Http status codes](https://www.linkedin.com/feed/update/urn:li:activity:7017027658400063488?utm_source=share&utm_medium=member_desktop)




## Author
Wilfred Onsongo

* [LinkedIn](https://www.linkedin.com/in/wilfred-onsongo/)

* [github](https://github.com/OnsongoN/apiLP5Project)

## License
MIT