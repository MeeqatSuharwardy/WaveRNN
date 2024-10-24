# Installation
Ensure you have

  Python >= 3.6
  Pytorch 1 with CUDA
Then install the rest with pip:

pip install -r requirements.txt

# How to Use

## Quickstart

If you want to use TTS functionality immediately you can simply use:

python quick_start.py

This will generate everything in the default sentences.txt file and output to a new 'quick_start' folder where you can playback the wav files and take a look at the attention plots

You can also use that script to generate custom tts sentences and/or use '-u' to generate unbatched (better audio quality):

python quick_start.py -u --input_text "What will happen if I run this command?"
