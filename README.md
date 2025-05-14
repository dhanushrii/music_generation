# Music Generation using LSTM
This project generates piano music using a Long Short-Term Memory (LSTM) neural network trained on the MAESTRO v2.0.0 MIDI dataset (https://magenta.tensorflow.org/datasets/maestro). It involves parsing MIDI files, training a deep learning model to learn musical patterns, and generating new musical sequences.

**Overview**
- Uses LSTM networks to generate music sequences by learning patterns from classical piano performances.
- The model predicts the next note in a sequence, allowing it to generate melodies and harmonies.
  
**Features**
- Data Preprocessing: Conversion of MIDI files into numerical sequences for LSTM training.
- Music Generation: Generate new music by predicting the next note in the sequence.
- Model Evaluation: Evaluation of the model using metrics like MAE, RMSE, and accuracy.

**Technologies Used**
- Python: Core programming language for the entire project.
- LSTM (Long Short-Term Memory): neural network model used for sequence generation.
- MAESTRO v2.0.0 Dataset: Dataset of classical piano performances (MIDI format).
- Libraries & Tools:
  - pathlib, os, glob, zipfile, time: File and directory handling.
  - requests, tqdm: Dataset downloading and progress tracking.
  - music21: Parsing, processing, and creating MIDI files.
  - numpy: Data preprocessing and numerical operations.
  - torch, torch.nn, torch.optim, DataLoader, TensorDataset: Model building and training with PyTorch.
  - matplotlib.pyplot: Visualization of training loss and accuracy.
  - midi2audio, FluidSynth: Converting MIDI files to audio.
  - IPython.display.Audio: Playing generated audio within Jupyter notebooks.

**Evaluation**
