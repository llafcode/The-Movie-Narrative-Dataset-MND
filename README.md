# The-Movie-Narrative-Dataset-MND-

This is the first public dataset of labeled movies and movie scenes, in the perspective of the well-known movie narrative theory - [Save the Cat](https://savethecat.com). In this theory, there are 10 *types of movie story structure* and 15 *story beats* that advances the stories, and we have collected labels, via crowdsoucing, of 45 movies for the purpose of facilitating machine learning in the Computational Narrative Understanding community.

This dataset contains two parts:
1. Story type data: each of the 45 movies has been labeled with 1 - 3 story types, out of 10 options. We also provide features for preliminary machine learning experiments to classify the movies into story types. The paper of this work is still under review.
2. Scene classification: In each movie, each scene has been labeled witn **only 1** story beats, out of 15 options. We also provide features for preliminary machine learning experiments to classify the movies into story types. This work has been published to ECCV (2022), refer to the paper [MND: A New Dataset and Benchmark of Movie Scenes Classified by their Narrative Function]() for more details of the methdology and experimental settings. 

Due to the copyright issue we cannot publish the digital copy of the movies as well as the scenes. But we have provided the scene boundaries timestamps in the Scene_Classification folder.
