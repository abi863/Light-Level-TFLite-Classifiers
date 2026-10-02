# Light-Level Classification Using TensorFlow Lite

## Project Overview

A small neural network classifies light sensor ADC readings into Dark, Normal, and Bright categories. The model is trained using Python and TensorFlow/Keras, converted to TensorFlow Lite, and tested using Python inference.

## Categories

* Dark: ADC below 1200
* Normal: ADC from 1200 to 2800
* Bright: ADC above 2800

## Technologies

* Python
* TensorFlow / Keras
* TensorFlow Lite
* NumPy and Pandas

## Project Workflow

1. Prepare the labeled light-level dataset.
2. Train a small neural network.
3. Convert the trained model to `.tflite`.
4. Load the converted model using the TensorFlow Lite interpreter.
5. Verify predictions for sample ADC readings.

## Files

* `light_data.csv`: Training data
* `train_convert.py`: Training and conversion script
* `verify_model.py`: Inference test script
* `light_classifier.tflite`: Converted model

## Result

A TensorFlow Lite model is generated and used to classify sample light readings into Dark, Normal, or Bright categories.

## Note

The dataset and thresholds are for demonstration. Validate the model with real sensor measurements before practical use.
