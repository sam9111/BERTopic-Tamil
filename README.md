# C16 - TOPIC MODELING APPROACH TO CONTENT-BASED RECOMMENDER SYSTEM FOR TAMIL NEWS ARTICLES

### Source for Dataset

https://www.kaggle.com/datasets/vijayabhaskar96/tamil-news-classification-dataset-tamilmurasu

### Software and Hardware requirements

1. Minimum Python 3.9 version

2. Anaconda Environment

### Detailed instructions to execute the source code

1. Install all the required Python packages in a conda environment

   ```sh

    pip install -r requirements.txt
   ```

2. Create a /data folder and place the downloaded dataset inside it
3. Run the preprocessing/tamilmurasu_preprocessing.ipynb notebook to preprocess the dataset
4. To test the Adapted BERTopic model finetuned for this dataset, run BERTopic/BERTopic_final.ipynb
5. To test the comparison between different Tamil word embeddings for BERTopic and LDA, run the files under comparison folder
6. To test the LDA model, first run preprocessing/preprocessing_pipeline.ipynb notebook and then run comparsion/LDA.ipynb
7. To test the recommender system, run recommendation_system/recommender_system_experiments.ipynb
