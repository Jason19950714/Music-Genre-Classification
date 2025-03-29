# Music-Genre-Classification
### Data
We used the GTZAN Genre Dataset.
This dataset consists of 1000 audio tracks, each 30 seconds long. It contains 10 genres, each represented by 100 tracks. The tracks are all 22050Hz Mono 16-bit audio files in .wav format.
The genres are:
- blues
- classical
- country
- disco
- hiphop
- jazz
- metal
- pop
- reggae
- rock

### Model
We combine the Convolutional Neural Network and Recurrent Neural Network as CRNN, to handle the graphical and serial characteristics of data.

### Result
| Model                                     | Test Accuracy     |
|:------------------------------------------|:------------------|
| Feedforward Neural Network (FFNN)         | 0.100         |
| Convolutional Neural Network (CNN)        | 0.525         |
| Convolutional Recurrent Neural Network(CRNN)    | 0.670         |

The CRNN model excelled in the test.
