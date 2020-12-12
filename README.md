# TTS with WaveNet based neural networks

Demo of some of the use cases of Tacotron2 neural network from NVIDIA to generate speech from text.

This repository contains fully contained Jupiter Notebooks for Google Colaboratory.

Notebooks in this repository:

* [tts_griffin_lim.ipynb](tts_griffin_lim.ipynb) - 
  Demo with Tacotron2 for MEL spectrogram generation and Griffin-Lim algorythm 
  for MEL spectogram to audio signal reconstruction
* [tts_wavenet.ipynb](tts_wavenet.ipynb)
  Demo with Tacotron2 for MEL spectrogram generation and WaveNet vocoder for speech synthesys - 
  also demonstrates MEL spectogram modifications to fit WaveNet which was trained on 
  different hyperparameters
* [tts_waveglow.ipynb](tts_waveglow.ipynb) -
  Demo with Tacotron2 for MEL spectrogram generation and WaveGlow generative network for 
  speech synthesys

The best results are obtained by Tacotron2 + WaveGlow combination.

The repository also contains Python variants of the notebooks and WAV demo samples.

Licensed under GPL-3.0.