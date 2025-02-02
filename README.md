# MelodyTransformer

## Overview

MelodyTransformer is a follow-up project to MelodyLSTM. This model leverages transformers to generate fixed-length sequences of music. It learns from a dataset of MIDI files and generates new music based on the patterns it has learned.

## Features

**Dataset**:  
The project uses a subset of MIDI files from the MAESTRO Dataset. MAESTRO (MIDI and Audio Edited for Synchronous Tracks and Organization) is a dataset comprising approximately 200 hours of virtuosic piano performances, captured with fine alignment (~3 ms) between note labels and audio waveforms.

**Model**:  
The model is based on the Transformer architecture, which is widely known for its ability to handle sequential data with long-range dependencies effectively.

**Normalization/Denormalization**:  
L2 Normalization is applied to scale the dataset for training and generate outputs with consistent features.

---

### Packages

- Python
- PyTorch
- NumPy
- pretty_midi
