# Anime Synopsis Similarity

The **Anime Synopsis Similarity Checker** is a Python program that allows users to find the most similar anime titles based on their synopses using cosine similarity. It uses a dataset with anime titles and their respective synopses to perform the similarity check.

## Usage
The program has two main parts: dataset preparation and similarity checking. To use the program, first, download the scripts and the database and put them in the same folder. Then, execute the python script prepare_dataset.py to create the database so the program can work with it. This is a one-time process.
    
    'python prepare_dataset.py'
   
After the dataset is created, execute the anime_synopsis_similarity_checker.py and follow the program instructions.
    
    'python anime_synopsis_similarity_checker.py'
    
Once the program is running, the user is prompted to enter the title of the anime they want to search for. If the title is found in the dataset, the program returns the synopsis of the anime and a list of the most similar anime titles based on their synopses.

## Credits and Citations 
This work uses the [Anime Recommendations Database](https://www.kaggle.com/datasets/hernan4444/anime-recommendation-database-2020) dataset, made available by Hernan Valdivieso for the Advancement of Science and Art on Kaggle. Special thanks to Hernan Valdivieso and the dataset creators for making this data available.

This program was created by [Jonatas Fernandes Andrade](https://github.com/JFA000) and [Gabriel Medina da Assunção](https://github.com/gabs4841).
