# Track2vec-Project

In this project we developped a word2vec network in order to build a playlist completion tool (song suggestion).
The dataset we worked on contains 100000 playlists which are composed of an average of 24.1 songs. 

Steps taken: 
- Data analysis and preparation.
- Build, evaluation and tuning of the network's hyparameters.
- Use of KDTree to speed up the search for nearest neighbours.
- Creation of a radio function that takes as input a track number in the dataset and launches a series of tracks by randomly pulling in the neighborhood of the current track the next track to listen to.

Inside the "src" folder, you can find a well commented notebook detailing our work and the different step taken. ("src/track2vec-en.ipynb")

Technologies: Python, Sklearn, Tensorflow, Keras, ...

