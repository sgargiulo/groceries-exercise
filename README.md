# groceries-exercise


## Prerequisites

  + Anaconda 3.7
  + Python 3.7
  + Pip

## Installation

Fork this repository under your own control, then clone or download the resulting repository onto your computer. Then navigate there from the command line:

```sh
cd groceries-exercise
```

> NOTE: subsequent usage and testing commands assume you are running them from the repository's root directory.

## Environment Setup

Use Anaconda to create and activate a new virtual environment, perhaps called "groceries-env":

```sh
conda create -n groceries-env python=3.7 # (first time only)
conda activate groceries-env
```

From inside the virtual environment, install package dependencies:

```sh
pip install pytest
```
From within the virtual environment, demonstrate your ability to run the Python script from the command-line:

```sh
python groceries.py
```
If working properly, you should see the "products" data structure 

## Setup



## Usage

Run the recommendation script:

```py
python app/groceries.py
```

## Testing

Install pytest (first time only):

```sh
pip install pytest
```

Run tests:

```sh
pytest

# or, skipping tests that issue network requests:
CI=true pytest
```

## [License](/LICENSE.md)
