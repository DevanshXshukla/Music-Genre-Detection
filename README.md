# Music-Genre-Detection
Music Genre Classification

<b> About the dataset </b>
The GTZAN genre collection dataset was collected in 2000-2001. It consists of 1000 audio files each having 30 seconds duration. There are 10 classes ( 10 music genres) each containing 100 audio tracks. Each track is in .wav format. It contains audio files of the following 10 genres:

- Blues
- Classical
- Country
- Disco
- Hiphop
- Jazz
- Metal
- Pop
- Reggae
- Rock

Feature Extraction:

Initial step in music genre classification project: 
- Extract features and components from audio files
- Identify linguistic content
- Discard noise
- Mel Frequency Cepstral Coefficients (MFCC):

Cutting-edge features for automatic speech and speech recognition studies !
Steps for generating MFCC features:
- Divide audio signals into smaller frames (20-40 ms each)
- Identify frequencies in each frame
- Separate linguistic frequencies from noise
- Discard noise using Discrete Cosine Transform (DCT)
- Retain specific sequence of frequencies with high information probability


Approach:
There are various methods to perform classification on this dataset. Some of these approaches are:

- Multiclass support vector machines
- K-means clustering
- K-nearest neighbors
- Convolutional neural networks
