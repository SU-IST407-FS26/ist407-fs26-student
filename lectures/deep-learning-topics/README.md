# Deep Learning Topics (optional)

These lectures are **optional reading**. Deep learning is not part of this course, and there are no
assignments, lab exercises, or participation questions on this material. They are taken from the
graduate course (IST 707), for anyone who wants to go further.

| Folder | Topics |
|---|---|
| `1-keras-introduction/` | Neural network basics (perceptrons, MLPs), tensors, Keras's Sequential and Functional APIs |
| `2-deep-learning-parameters-1/` | Activation functions; learning rates and learning-rate schedules |
| `3-deep-learning-parameters-2/` | Optimizers (momentum, AdaGrad, RMSProp, Adam); regularization (dropout and others). `extra/`: hyperparameter tuning with Keras Tuner |

## Running the notebooks

The saved outputs let you read every notebook without running it. Most of them need **TensorFlow**,
which is **not** installed in the course container (it is large). To run them, choose one:

- **In the course container (or Codespaces)**, open a terminal and run:

  ```bash
  pip install tensorflow keras-tuner
  ```

  Then restart the notebook kernel. The install is lost if the container is rebuilt, so you may need to
  run it again later.
- **Google Colab** (https://colab.research.google.com) has TensorFlow preinstalled: upload a notebook
  (and its `assets/` images, if you want them to show) and run it there.

`1-keras-introduction/1-lecture-intro-deep-learning-part1.ipynb` and
`2-deep-learning-parameters-1/0-activation-functions.ipynb` need only NumPy, SciPy, Matplotlib and
scikit-learn, so they run in the container as is.
