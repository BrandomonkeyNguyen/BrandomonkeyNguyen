# Brandon Nguyen

## [Top-N Genre Classification Neural Network](https://github.com/beatsageo/Top_n) - Senior Capstone Project

I was primarily responsible for the Input Preprocessing portion of this project. I built python scripts using the Librosa library in order to convert audio files into formats that the neural network could read. The best formats for this were ones that could represent the sound frequencies over time. In the early stages, I created a spectrogram generator that was capable of creating jpg spectrogram images. Eventually we discovered MFCCs which are much more efficient. I have mainly worked on bug-fixes as needed by our data acquisition team and generally worked to optimize the scripts. The end goal for the MFCC generator script is for it to be used in the final product to convert user-submitted audio files into MFCCs for the neural network to process.

![Example Spectrogram](/spec-files/blues.00000.au_1.jpg) 
![Example Spectrogram](/spec-files/blues.00001.au_1.jpg)
