# Self-Driving Car Engineer Nanodegree
## Project: Build a Traffic Sign Recognition Program using Deep Learning

### Overview

In this project, I use Tensorflow to classify traffic signs. I  trained a model so it can decode traffic signs from natural images by using the [German Traffic Sign Dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset). After the model was trained, I then tested it on new images of traffic signs from the web.

The project is in the notebook `Traffic_Signs_Recognition.ipynb`. There is a lot of information in there and the entire process is broken down into fairly small steps as follows:

- Dataset exploration
- Data augmentation
- Model generation
- Training
- Test on unseen images

### Dependencies

This project requires **Python 3.5** and the following Python libraries installed:

- Jupyter
- NumPy
- OpenCV
- SciPy
- scikit-learn
- TensorFlow
- Matplotlib
- Pandas

### Dataset

1. [Download the dataset](https://d17h27t6h515a5.cloudfront.net/topher/2016/November/581faac4_traffic-signs-data/traffic-signs-data.zip). This is a pickled dataset in which we've already resized the images to 32x32.
2. Clone the project and start the notebook.
```
git clone https://github.com/udacity/CarND-Traffic-Signs
cd CarND-Traffic-Signs
jupyter notebook Traffic_Signs_Recognition.ipynb
```
3. Follow the instructions in the `Traffic_Signs_Recognition.ipynb` notebook.

