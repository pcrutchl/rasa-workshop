# Building AI assistants that scale using machine learning and open source tools

This is a repository for a 3-hour workshop at O'Reilly AI Conference 2019 run by Justina Petraityte, Developer Advocate at Rasa. The actual exercise will be uploaded here before the workshop, but you can already use this repository to set up your environment.


## Software used in this workshop
During this workshop, we will program everything in Python. To successfully follow the workshop your environment should contain:  
- Python <= 3.6.8. 
- Jupyter notebook. 


During this workshop we will use only open source tools and software:  
- rasa NLU. 
- rasa Core 
- sqlite3. 
- pandas
- mongodb

Additional tools you will need to successfully follow this workshop:  
- Text editor. 
- Browser  


## Installation

To install the required python modules you can create a virtual environment and install the dependecies there using a requirements.txt file provided in this repo:

1. Create a conda environment:
`conda create -n rasa-workshop python=3.6.8`

2. Activate the environment:
`conda activate rasa-workshop`

3. Install the requirements:
`pip install -r requirements.txt`


If you don't want to use virtual environments, you can install the dependecies directly on your system using a requirements.txt file provided in this repo:

'pip install -r requirements.txt'


One of the steps in this workshop will also include using a Mongo DB. It's an optional step, but if you want to follow along, make sure to install Mongo DB on your machine as well. You can find the installation intructions for all operating systems [here](https://docs.mongodb.com/manual/installation/).



## Get in touch

If you encounter any problems while installing the dependencies or have any questions regarding this notebook, shoot me a message at juste@rasa.com
