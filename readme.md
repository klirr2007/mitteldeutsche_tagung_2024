# Von der Ökoakustik zur Elektroakustik - Machine Learning im Kontext der Klanganalyse und Klangklassifikation

# From Ecoacoustic to Electroacoustic: Utilizing Machine Learning for Sound Analysis and Classification


This repository contains supplementary files and resources for my talk at the XVII. Mitteldeutsche Tagung. The materials are designed to provide a deeper understanding and hands-on examples related to the topics discussed during the presentation.

## Environment Setup

The code and notebooks in this repository are optimized for Python 3.11. We recommend setting up a virtual environment using Conda to manage the dependencies. You can create a new environment named `mittel_env` by running:

```bash
conda create -n mittel_env python=3.11
```
Once the environment is created and activated, install the required packages using:
```bash
pip install -r requirements.txt
```

## Repository Structure

The repository contains the following files and directories:

- `oekoakustik.pptx`: Presentation slides from the talk with audio.
- `oekoakustik.pdf`: Presentation slides without audio.
- Audio samples used in the notebooks:
  - `dufour_mono.wav`
  - `incidences_resonances.wav`
  - `rock_savanna.wav`
- Notebooks:
  - `mfcc_bank.ipynb`: A quick introduction to MFCC (Mel Frequency Cepstral Coefficients) filter banks.
  - `ssm_detail_vector.ipynb`: In-depth audio-based SSM (Self-Similarity Matrix) calculation.
  - `ssm_new_plotly.ipynb`: SSM calculation with visualization in Plotly.
  - `thresholds_parm.ipynb`: Threshold-based template matching with scikit-maad.
  - `tsne_mnist_demo.ipynb`: Introduction to dimensionality reduction algorithms based on the MNIST dataset.
  - `tsne_spectrum.ipynb`: Audio spectrum-based dimensionality reduction examples with scikit-maad.

## Getting Started

To get started, clone this repository and navigate to the cloned directory. Activate your `mittel_env` environment and install the required packages as described in the Environment Setup section above.

You can then open the notebooks using Jupyter Notebook or JupyterLab to follow along with the examples and explore the concepts discussed in the talk.
