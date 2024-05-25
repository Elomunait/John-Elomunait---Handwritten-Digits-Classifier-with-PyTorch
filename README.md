# MNIST Handwritten Digits Recognition

## Introduction
In this project, you will build a neural network to evaluate the MNIST dataset.

Some of the benchmark results on MNIST include:
- 88% [Lecun et al., 1998](https://hal.science/hal-03926082/document)
- 95.3% [Lecun et al., 1998](https://hal.science/hal-03926082v1/document)
- 99.65% [Ciresan et al., 2011](http://people.idsia.ch/~juergen/ijcai2011.pdf)

MNIST is a great dataset for sanity checking your models since the accuracy levels achieved by large convolutional neural networks and small linear models are both quite high. This makes it important to be familiar with the data.

## Installation
To set up the project, follow these steps:

1. Clone the repository:
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Install the required dependencies:
    ```bash
    python -m pip install -r requirements.txt
    ```

3. Upgrade Jupyter Notebook and enable widgets extension:
    ```bash
    %pip install --upgrade notebook
    %jupyter nbextension enable --py widgetsnbextension
    ```

## Usage
You can run the project by executing the Jupyter notebook. Here is an example of how to set up your environment and install dependencies:

```python
# Update the PATH to include the user installation directory. 
import os
os.environ['PATH'] = f"{os.environ['PATH']}:/root/.local/bin"

# Restart the Kernel before you move on to the next step.

# Install requirements
!python -m pip install -r requirements.txt

%pip install --upgrade notebook
%jupyter nbextension enable --py widgetsnbextension
```

## Examples
To get started with using the notebook, you can refer to the code snippets below:

```python
import os
os.environ['PATH'] = f"{os.environ['PATH']}:/root/.local/bin"

!python -m pip install -r requirements.txt

%pip install --upgrade notebook
%jupyter nbextension enable --py widgetsnbextension
```

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.