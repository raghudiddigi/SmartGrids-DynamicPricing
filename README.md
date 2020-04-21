# A Stochastic Game Framework for Efficient Energy Management in Microgrid Networks

This repository contains all the code, results and supplementary for the paper **"A  Stochastic Game Framework for Efficient Energy Management in Microgrid Networks"**, which has been accepted to ISGT Europe 2020. 

The file **requirements.txt** contains all the requirements needed to run the code. You can also use **install.sh** to set up a virtual environment (smart_grids) and installs all the dependencies automatically.

To install all the dependencies follow the following steps:
```
pip install -r requirements.txt
```
or for creating a virtual environment and then installing the dependencies:
```
chmod +x install.sh
./install.sh
```
Make sure you have **virtualenv** package installed. Check [this](https://gist.github.com/frfahim/73c0fad6350332cef7a653bcd762f08d) guide to install virtualenv.

### Steps to run the code

-   Go to the code folder . This contains:
    -   **main.ipynb** (contains all the code to run the experiment).
    -   **DQN_agent.py** (contains classes and functions for the agents).
    -   **config.json**: Contains the various renewable energy generation profiles for each agent for which we have run our experiment. 
    - **Results.md** : Contains the google drive link for the logs and saved models of all the experiments run.
-   Create two folders, 'logs' and 'saved', where all the results of the experiments and the trained models will be saved
-   Run the main.ipynb notebook using jupyter.
- All the results will be stored in the 'logs' folder and all the trained models will be stored in the 'saved' folder.