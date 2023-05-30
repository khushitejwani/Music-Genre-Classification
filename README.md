# Music-Genre-Classification
Aim: To create a model, which classifies music samples into different genres. 
Goal: To see how to handle sound files in python, compute sound, audio features from them, run Algorithms on them, and see the results. 
Vision: To form a basic step for building a strong music recommendation system.

Made use of GTZAN Dataset, which consists of:
1000 audio tracks each 30 seconds long
10 genres, each represented by 100 tracks
10 genres: blues, classical, country, disco, hiphop, jazz, metal, pop, reggae, rock
Tracks are all 22050Hz
Mono 16-bit audio files in .wav format

Applied Libraries: 
Numpy
Librosa
Pandas
Keras 
Matplotlib
Pydub

Conclusion: The project provides the base for performing Music Genre Classification using Machine Learning Techniques.
The application uses a Convolutional Neural Network model to perform the classification.
A Mel Spectrum of each track from the GTZAN dataset is obtained. This is done by using the libROSA package of python.
A piece of software is implemented which performs classification of songs into their respective genres.

Future Scope: The extension of this work could be to consider bigger data sets and also tracks in different formats(mp3, au etc).
Objective for the future will be to stay updated with the change in styles of genres and extending our software to work on these updated styles.
Can also be extended to work as a music recommendation system depending on the mood of the person.
