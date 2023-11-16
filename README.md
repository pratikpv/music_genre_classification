# Introduction
This Python Jupyter Notebook aims to perform classification of Music Genre.

We use GTZAN genre collection dataset, which can be downloaded from https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification


This dataset consists of 10 genres, i.e., blues, classical, country, disco, hiphop, jazz, metal, pop, reggae, rock.
Each genre consist of 100 music clips, each clip is 30 seconds long.

<img src="https://fairgaze.com/images/UploadedImages/thumbs/0292990_0292990_resize-1607630237807008719Differentofmusicgenres.jpg" width="500" height="200"/>


# Summary

We extracted several features such as from audio files chroma_stft, rmse, spectral_centroid,spectral_bandwidth,rolloff, zero_crossing_rate and 20 of the MFCCs. We used ANN-based model to classify music genre using these features. This approach gives about 64.00% test accuracy.

We also generated mel spectrogram images from the audio files. We used CNN based model to classify music genre based on these images. This method gives about 71.73% test accuracy.
