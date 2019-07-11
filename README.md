# Hand Gesture Recognition
Hand gesture recognition - machine learning model using keras, numpy and openCV

## Anaconda and Jupyter Notebook Configuration
* Download and insatll anaconda software
* Conda is a package manager to manage virtual environment and install packages.
* Here are some helpful commands using conda:
    ```bash
        #update conda in your default environment
        $conda upgrade conda
        $conda upgrade --all

        # create a new environment with conda
        $conda create -n [my-env-name]
        $conda cerate -n [my-env-name] python=[python-version]

        # activate the environment you created
        $source activate [my-env-name]

        # take a look at the environment you created
        $conda info
        $conda list

        # install a package with conda and verify it's installed
        $conda install numpy
        $conda list

        # take a look at the list of environments you currently have
        $conda info -e

        # remove an environment
        $conda env remove --name [my-env-name]
    ```
* Next, install TenslowFlow in the virtual environment you created with conda
    ```bash
        # install pip in the virtual environment
        $conda install pip

        # install Tensorflow CPU version
        $pip3 install --upgrade tensorflow # for python 3.*

        # install Keras (Note: please install TensorFlow first)
        $pip install Keras
    ```
* After installing TensorFlow you can verify its installation with python in command line and Invoke python from your shell as follows:
    ```bash
    # invoke python from your shell
    $python

    # create a simple TensorFlow program inside the python interactive shell
    >>>import tensorflow as tf
    >>>hello = tf.constant('Hello, TensorFlow!')
    >>>sess = tf.Session()
    >>>print(sess.run(hello))

    # Exit the python shell
    >>>Ctrl+D
    ```
 * Launch Jupyter Notebook   

## Dataset
* Download dataset from this link -
* Dataset is divided in two parts: Training data and Test data

## Running the model
* Git clone this repository in a new folder
* Put the dataset(Train and Test folders) in that folder
* Open the classification_model.ipynb file in jupyter notebook
* Run the file
