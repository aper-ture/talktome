# talktome

Testing **USR 2.0**, a model that reads speech from audio, from lips, or from both
([paper](https://arxiv.org/abs/2602.19316) · [authors' code](https://github.com/ahaliassos/usr2)), on Google Colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aper-ture/talktome/blob/main/USR2_Noor_Colab.ipynb)

## What the notebook does
Each step is explained through the *Noor and the Chef Who Reads Lips* story.

1. Switches on a GPU and downloads the authors' code and a trained model (Huge or Base+).
2. Cuts a 5–15 second clip from a YouTube video (or one you upload).
3. Transcribes it three ways: **audio only**, **lips only**, **audio + lips**.
4. Scores each against what was really said (word error rate).
5. Adds crowd noise at 0 dB and checks whether the lips rescue the audio.

About 35–75 minutes the first time on a free Colab T4 GPU.

## How to run it
Click the **Open in Colab** badge, choose **Runtime → Change runtime type → T4 GPU**,
then run the cells top to bottom with **Shift + Enter**.
