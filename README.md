# RECOMMENDATION-SYSTEM-task-4-
COMPANY : CODETECH IT SOLUTIONS

NAME : VED SUHAS KULKARNI

INTERN ID : CT04WC71

DOMAIN : MACHINE LEARNING

DURATION : 4 WEEKS

MENTOR : NEELA SANTOSH

DESCRIPTION OF TASK : 

-This project is a Music Recommendation System built using Collaborative Filtering and Matrix Factorization techniques. The goal of this system is to recommend songs to users based on their listening history and preferences.
We achieved this by generating a user-song interaction matrix, computing cosine similarity, and recommending similar songs. Additionally, we implemented fuzzy matching to handle misspellings or variations in song names.

-We used a Spotify dataset (spotify_songs.csv) containing various song tracks with attributes like:

🎵 Track Name
🎤 Artist Name
📊 Popularity
🎼 Genre

-We used the Cosine Similarity technique to measure similarity between songs based on user ratings.

Higher similarity → Songs are more likely to be related.
Lower similarity → Songs are less related.

-One major challenge was that:

If a user typed "Shape of you", but the song in the dataset was "Shape Of You (Acoustic)", it would not be found.
To solve this, we implemented fuzzy matching using the fuzzywuzzy library to find the closest match.

OUTPUT : 
