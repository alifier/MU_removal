# Project: A CNN that Removes Lipstick from Images of Women
## Goal: Teach a CNN to Reproduce Images of Caucasian Women while Simultaneously Removing their Lipstick


The report is saved in an iPython Notebook format. To review it click on the [Makeup_CNN_final.ipynb](./Makeup_CNN_final.ipynb) file.

If you want to run the code in your computer you will need to follow the **Install** and **Run** instructions.

## Data

The VMU dataset was assembled by synthetically adding makeup to 51 female Caucasian subjects in the FRGC dataset. For the training of our network we used pairs of the original images and the same images with lipstick. The dataset can become available upon contacting Antitza Dantcheva. More information can be found on [her personal webpage](http://www.antitza.com/makeup-datasets.html).


### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [SciPy](https://www.scipy.org/install.html)
- [matplotlib](http://matplotlib.org/)
- [Tensorflow](https://www.tensorflow.org/install/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included.

### Run

In a terminal or command window, navigate to the top-level project directory `customer_segments/` (that contains this README) and run one of the following commands:

```bash
ipython notebook Makeup_CNN_final.ipynb
```  
or
```bash
jupyter notebook Makeup_CNN_final.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.
