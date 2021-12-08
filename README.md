
02805 Social graphs and interactions
--------------------
This repository contains the work of Kiriakos Tsalkitzidis s202669@student.dtu.dk, Sebastian Ekpete s212266@student.dtu.dk, and Vetle Ottem Frantzvaag s203121@student.dtu.dk in the course [02805 Social graphs and interactions](https://kurser.dtu.dk/course/02805) offered by the Technical University of Denmark.

The repository contains our solution to the final project - the result can be seen at http://socialpokemon.dk/.

Final project description
--------------------
The primary purpose of this repository is to host our work on the final project. 
In the final project we looked into how we could analyze the Pokémon universe using different data science techniques, like networking and NLP.
The [Explainer Notebook](https://github.com/MikkelGroenning/social_graph/tree/main/Notebooks) as well as the website http://socialpokemon.dk/ explains in greater details the purpose of the project.


How to run the code
--------------------
An environment has been created to ensure the reproducibility of the data.
Please note that this requires a conda-distribution to be installed on the computer. 
From the top folder run the current command in the terminal:

`conda env create -f environment.yml`

Activate the environment by the following command

`conda activate environment.yml`

Verify that the correct environment is activated by running

`conda info --envs`

All code should now run as intended.

Directory Structure
--------------------
    .
    ├── README.md
    ├── setup.py
    ├── LICENCE
    ├── environment.yml     <- file with libraries and library versions for recreating the analysis
    ├
    ├── Assignment1         <- Solution to assignment 1       
    ├── Assignment2         <- Solution to assignment 2     
    ├── Data
    │   ├── processed       <- data for final project after all preprocessing has been done
    │   └── raw 		    <- original unmodified data or final project acting as source of truth and provenance
    │
    ├── notebooks 		    <- jupyter notebooks for analysis and explanation 
    ├── models 		        <- compiled model describing the graphs 
    ├── figures             <- figures created for the final project
    ├── src
    │   ├── data            <- helpfull script to deal with the data
    │   └── tools 		    <- tools for accessing the Twitter API
    ├── web_app
    │   ├── figures         <- figures used on the website
    │   ├── plotly-files    <- interactives plots used on the website
    │   └── Vendor          <- Exertnal CSS and JS script
