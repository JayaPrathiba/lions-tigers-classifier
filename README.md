# Lions vs Tigers Image Classifier 🦁🐯

A binary image classifier that distinguishes lions from tigers, built with Keras/TensorFlow using a small Xception-style CNN.

## Overview

This project adapts the classic Keras "Cats vs Dogs" image classification tutorial to a Lion vs Tiger dataset. It covers the full pipeline: data loading, corrupted-image filtering, augmentation, model training, and inference.

## Dataset

Uses the [`akrsnv/lions-and-tigers`](https://www.kaggle.com/datasets/akrsnv/lions-and-tigers) dataset on Kaggle — 400 images (256x256) across 2 classes.

```shell
pip install kaggle
kaggle datasets download -d akrsnv/lions-and-tigers
unzip -q lions-and-tigers.zip -d LionsTigers
