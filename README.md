## Answering Business Questions using SQL
This project is about analyzing data from a database file using SQLite and python. It involves exploring certain questions which will be interesting for a business to invest in advertising campaigns and generating profit in certain countries.

## Dataset
The dataset we will be using for this project is Chinook database which is provided as a SQLite database file called `chinook.db` which can be downloaded from [here](https://github.com/lerocha/chinook-database). The Chinook database contains information about a fictional digital music shop - kind of like a mini-iTunes store.

The Chinook database contains information about the artists, songs, and albums from the music shop, as well as information on the shop's employees, customers, and the customers purchases. This information is contained in eleven tables. We have also included a schema diagram for the Chinook database for reference.

## Installation
### Getting the Notebook and data
- Clone this repo to your computer.
- Get into the folder using `cd Answering_Business_Questions_using_SQL`.
- Download the dataset from the above link.

## Install the requirements
All the python packages and libraries used in the project are listed in the file `requirements.txt`. You might want to install the listed version or newer of the python libraries. There are atleast two ways of getting all the libraries used:
- Download [Anaconda](https://www.anaconda.com/distribution/) python distribution, it will install all the libraries needed.
- Download [pip](https://pypi.org/project/pip/) and install the requirements using `pip install -r requirements.txt`.
- Make sure you use Python 3.

Other than the libraries and packages listed in file `requirements.txt`, we also need to use the sqlite interface provided by an in-built python module called `sqlite3`.

In case the notebook is not loading up, try [notebook viewer](https://nbviewer.jupyter.org/) to have it rendered.