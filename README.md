# Speech Emotion Recognition using MLP Classifier

## Abstract:

Speech Emotion Recognition, abbreviated as SER, is the act of attempting to recognize human emotion and the associated 
affective states from speech. This is capitalizing on the fact that voice often reflects underlying emotion through tone and pitch. 
Emotion recognition is a rapidly growing research domain in recent years. Unlike humans, machines lack the abilities to perceive 
and show emotions. But human-computer interaction can be improved by implementing automated emotion recognition, thereby 
reducing the need of human intervention.

In this project, basic emotions like calm, happy, fearful, disgust etc. are analyzed from 
emotional speech signals. We use machine learning techniques like Multilayer perceptron Classifier (MLP Classifier) which is 
used to categorize the given data into respective groups which are non linearly separated. Mel-frequency cepstrum coefficients 
(MFCC), chroma and mel features are extracted from the speech signals and used to train the MLP classifier. For achieving this 
objective, we use python libraries like Librosa, sklearn, pyaudio, numpy and soundfile to analyze the speech modulations and 
recognize the emotion. 

Using RAVDESS dataset which contains  around 1500 audio file inputs from 24 different actors (12 male and 12 female ) who recorded short audios in 8 different emotions, we will train a NLP- based model which will be able to detect among the 8 basic emotions as well as the gender of the speaker i.e. Male voice or Female voice.  
After training we can deploy this model for predicting with live voices.

## Deliverables:

Learn the basics of Python, ML/DL, NLP, librosa, sklearn, etc , Literature Review , analyzing the dataset and 
Feature extraction. Building and training the model on the training data, followed by testing on test data. And 
finally, testing the model on live audio input (unseen) and collecting the results:)


## Schedule:

Week1: 

    • covering ml\dl basics

Week 2:

    • building  audio recorder
    
    • plotting waveform and spectrogram
    
    • learning audio preprocessing for feature extraction

Week 3:

    • Implementing the code for feature extraction using Librosa library

Week 4:

    • Implement the MLP model for emotion recognition
    
    • Evaluating it on test set

Mid-term deliverables:

    - showing the waveforms and spectrograms of audio waves and present the mlp model.

Week 5:

    • Implementing LSTM model
    
    • Starting to implement CNN model

Week 6:

    • Complete the CNN model implementation.
    
    • Model will be evaluated on our voice
    
Week 7:

    • If interested then work could be done to improve accuracy by extracting some more features or by adding or removing some layers 
      Project ends.

End term deliverables: 

    - Presenting the progression of project and evaluating the model on live speech.
    
    
## References:

     - http://aishelf.org/audio-recog/
     
     - https://ijesc.org/upload/bc86f90a8f1d88219646b9072e155be4.Speech%20Emotion%20Recognition%20using%20MLP%20Classifier.pdf
     
     - https://ricardodeazambuja.com/deep_learning/2019/03/09/audio_and_video_google_colab/
