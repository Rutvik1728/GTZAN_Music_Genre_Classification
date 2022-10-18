Music Genre Classification
===
Sequence of Classification
---
```sequence
Audio File->Spectrogram:
Spectrogram->CNN:
CNN->FCNN:
FCNN->Classification:
```
# Sequence of Operations
- An audio file is imported
- The waveform and sample rate of the audio file is extracted
- From this waveform, Its spectrogram is generated
- This spectrogram is fed into a CNN
- The output of the CNN is fed into a FCNN
- From FCNN the classified music genre is obtained

# About
- Max Training Set Accuracy : 100%
- Max Test Set Accuracy : 65%
