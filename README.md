# Audio-Copyright-Protection-based_on-AI-Audio-Data-Poisoning-Demo
AI Audio Data Poisoning is a Python script that demonstrates how to add adversarial noise to audio data. This technique, known as audio data poisoning, involves injecting imperceptible noise into audio files to manipulate the behavior of AI systems trained on this data.


## How It Works

The script adds random noise to the original audio signal, creating a "poisoned" version of the audio. This poisoned audio may still sound similar to the original to human ears but can cause misclassification or errors when processed by AI models trained on the data.

## Usage

### Install dependencies

- `pip install numpy`: For numerical operations and generating random noise.
- `pip install librosa`: For loading audio files.
- `pip install soundfile`: For saving audio files.

### Run Script

`python Audio-Copyright-Protection-based_on-AI-Audio-Data-Poisoning-Demo.py`

