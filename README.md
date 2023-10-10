# MovieCompanion - A Movie Recommender System

## Introduction
This Movie Recommendation System was developed to help explore unsupervised machine learning algorithms within Recommendation system algorithms. Real recommenders are
a lot more complex so this is just an introduction into the possibilities.</br>

Some of the algorithms we will be exploring include:

- Content Based Filtering
- Collaborative Filtering
- Hybrid

## Dataset
[The Movies Dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset) - Metadata on over 45,000 movies. 26 million ratings from over 270,000 users:</br>
The following files from the dataset were used:
- credits.csv
- keywords.csv
- links_small.csv
- movies_metadata.csv
- ratings_small.csv

Make sure you have the datasets in a folder "data" within your Google Drive if running this project on Colab.

## Results
Finding movies similar to Armageddon, assuming that user is in User Group 300. Feel free to input different movies in the Jupyter Notebook.
```
Top movies previously rated by User Group 300: 
                                       title  rating
0                                 Armageddon     5.0
1                              Jurassic Park     5.0
2  Star Wars: Episode I - The Phantom Menace     5.0
3                                   The Rock     5.0
4                         Planet of the Apes     5.0
5                                 Braveheart     5.0
6         Indiana Jones and the Last Crusade     4.5
7                                  Cast Away     4.5
8                                The Patriot     4.5
9                     Mission: Impossible II     4.5

These are the top 10 movies similar to 'Armageddon' (Content-Based Approach):

   movieId                               title
0     7907      Transformers: Dark of the Moon
1     7296                Terminator Salvation
2     4739  Terminator 3: Rise of the Machines
3     7424                          Surrogates
4     6394                        District B13
5     1011                      The Terminator
6     2040                              Meteor
7     8854                  Terminator Genisys
8     6738                            Sunshine
9     8207                              Looper

These are the top 10 movies similar to 'Armageddon' but sorted according to user group's taste (Hybrid Approach):

    movieId                 title  Estimated Rating
5      1011        The Terminator          4.391232
15     4349      The Professional          4.339073
19     7691              The Town          4.222113
4      6394          District B13          4.194526
10     6716                  Next          4.147678
1      7296  Terminator Salvation          4.134891
11     6242            The Island          4.002384
18     4150  The Sum of All Fears          3.898628
9      8207                Looper          3.858136
16      343               Timecop          3.838748
```
