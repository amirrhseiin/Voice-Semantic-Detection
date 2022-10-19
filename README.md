# Voice-Semantic-Detection
##dataset: https://github.com/mansourehk/ShEMO

This project aims to classify the speaker's emotions into five classes using audio files. We used MFCC and Chroma_cens as feature extractors.
We designed an LSTM model with different optimizers, such as Adam and SGD.
Also, to study the effects of the two genders on the model's accuracy, it was trained on the audio of male and female speakers separately.


Chroma_cens : https://resources.mpi-inf.mpg.de/MIR/chromatoolbox/index.html#MuellerKC05_ChromaFeatures_ISMIR

MFCC : https://www.intechopen.com/books/from-natural-to-artificial-intelligence-algorithms-and-applications/some-commonly-used-speech-feature-extraction-algorithms
