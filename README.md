# Recommendations with IBM

### Table of Contents

1. [Installation](#installation)
2. [Instruction](#instruction)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Licensing, Authors, and Acknowledgements](#licensing)


## Installation <a name="installation"></a>

All the libraries required for running the app are listed in the requirement.txt file.
For installing these libraries, only run this comand with Python 3 in root path:

```
$ pip install -r requirements.txt
```


## Instruction <a name="instruction"></a>

Execute all cells of Recommendations_with_IBM.ipynb


## Project Motivation<a name="motivation"></a>

This is the third project for the Udacity Data Science Nanodegree program. For this project I am interestested in building a system of recommendation of IBM's articles. I develop all those steps: Exploratory Data Analysis,  Rank Based Recommendations, User-User Based Collaborative Filtering and Matrix Factorization.


## File Descriptions <a name="files"></a>
<pre>
<code>.
├── <b>README.md</b>
├── <b>Recommendations_with_IBM.ipynb </b> : Flask App Files
├── <b>data</b> : It contains all ETL Files 
│ ├── <b>articles_community.csv</b> :  Dimension table of article  
│ └── <b>user-item-interactions.csv</b> :  Fact table of user item interactions  
├── <b>top_5.p</b>: pickle file to test top 5 rank based recommendations
├── <b>top_10.p</b>: pickle file to test top 10 rank based recommendations
├── <b>top_20.p</b>: pickle file to test top 20 rank based recommendations
├── <b>user_item_matrix.p</b>: pickle file to load the user_item matrix
└── <b>requirements.txt</b>
 </code>
</pre>


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The Datasets used in this project is provided by IBM Watson Studio platform.
