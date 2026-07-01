# COVID-19 Chest X-Ray Classification

Deep-learning classifier that detects COVID-19 / pneumonia from chest X-ray images, with a
small Flask web app for running inference on new images.

## What's inside

- **`COVID-19 X-Ray Classification.ipynb`** — model training / experimentation notebook.
- **`COVID-19 X-Ray Cross Validation Model.ipynb`** — cross-validated training for a more
  robust estimate of generalization.
- **`COVID-Model-200-3-5-25.h5`** — trained Keras model weights.
- **`webapp/`** — Flask app (`webapp.py`) that loads the model and classifies uploaded
  X-ray images.

## Stack

Python · TensorFlow / Keras · NumPy · Flask · Jupyter.

## Run the web app

```bash
cd webapp
pip install -r requirements.txt
python webapp.py
```

Then open the local URL and upload a chest X-ray to get a prediction.

## Status

Research / portfolio project. Not intended for clinical use.
