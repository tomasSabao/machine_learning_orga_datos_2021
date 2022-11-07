# machine_learning_orga_datos_2021
Final project for the subject Organizacion de Datos


### Introduction
As the final project for subject Organización de Datos, students were asked to create a predictor for a dataset of products obtained from the web. The dataset contains text data for products on sale (a description, a title and a category it belongs to). I decided to create a deep neural network to predict the category of a product based on its description and title.\ 
Due to github size constraints, the dataset as well as the finished models are not in this repo. If interested in obtaining said files, please message me directly

### Baseline creation
We begin first by creating a baseline from which we will improve. As this problem requires analyzing texts which are prone to be misspeled or have information that is not particularly helpful (stopwords, acronyms, etc), the baseline model will first remove said data, leaving only useful information, and then train. The created model can be seen in: [(https://colab.research.google.com/drive/1frsrD29tUWh33vsiXPo6wChP4cQ5_gVJ?usp=share_link)]\
The notebook creates three models, one which predicts using only the title of the product,  another which predicts using only the description, and finally one that uses both to predict

### Features added to the baseline model
In order to improve the results of the baseline model, the following features were implemented and used to create a new model:
1. Using POS (part of speech)\
   Link to notebook: [(https://colab.research.google.com/drive/13Ou-Jh2i8SPvMN42efMNg_Re93KI7m7q?usp=sharing)]\
2. Using POS + tagging \
   Link to notebook: [(https://colab.research.google.com/drive/1frsrD29tUWh33vsiXPo6wChP4cQ5_gVJ?usp=sharing)]\
3. Using bigrams\
   Link to notebook: [(https://colab.research.google.com/drive/1h8jr82U0anzDZWQ1TvlVH8GsHi2QorVF?usp=sharing)]\
4. Using embeddings + numerical features\
   Link to notebook: [(https://colab.research.google.com/drive/14b3HpW5X5HK-uVp94g0VPBXaHfQ-5dCK?usp=sharing)]\
   
### Results
A video was made to tell the reader the results of this project. It is required to have knowledge of Spanish to be able to understand it\
[(https://drive.google.com/file/d/17l2gvz3ce164jS1Q0LXfRQXvAvz45MwM/view?usp=sharing)] 
