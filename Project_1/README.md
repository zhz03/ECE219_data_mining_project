# ECE 219 Project 1 

### Requirements for running the program

- pandas: `pip install pandas`

- jupyter: `pip install jupyterlab notebook`

- numpy: `pip install numpy`

- matplotlib: `pip install matplotlib`

- sklearn: `pip install sklearn`

- re: `pip install re`

- strings: `pip install strings`

- nltk: `pip install nltk`

- umap: `pip install umap-learn`

- seaborn: `pip install seaborn`

### GLoVE Embedding File Download

- `mkdir glove`
- `cd glove`
- `wget "http://nlp.stanford.edu/data/glove.6B.zip"`
- `unzip glove.6B.zip`

### Run the Code 

1. Open the python notebook `Project1_RK.ipynb`
2. Add the following lines to a new cell to download nltk packages:
```python
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
nltk.download('stopwords' )
nltk.download('wordnet')
nltk.download('omw-1.4') 
```
3. Now comment the above lines and run the code till Question 7. Question 8 is a GridSearch which will take very long time, hence it is suggested to run this part at the last
4. Now run the rest of the questions (Question 9 to Question 13) and get the respective results. 
5. Once all the results are obtained run the cells for Question 8. It would take > 6 hours. 
