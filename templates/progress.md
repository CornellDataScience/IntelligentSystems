# Progress Report Example

09/01 (John Smith):
* Read [ResNet paper](https://arxiv.org/abs/1512.03385)
  * Residual connections are easier to optimize and benefit from more layers.
* Created `preprocessing.py`
  * Functions to re-size images and convert to NumPy arrays (0-256).
  * Requires OpenCV: `pip install opencv-python`
  * Sample usage: `python preprocessing.py ./data/training-images/`
  * TODO: Delete images that are all the same color (=junk)
