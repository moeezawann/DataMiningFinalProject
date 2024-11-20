# Python Project Setup Guide

_A comprehensive guide to setting up the Python environment and installing dependencies using `requirements.txt`._

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
    - [1. Clone the Repository](#1-clone-the-repository)
    - [2. Navigate to the Project Directory](#2-navigate-to-the-project-directory)
    - [3. Create a Virtual Environment](#3-create-a-virtual-environment)
    - [4. Activate the Virtual Environment](#4-activate-the-virtual-environment)
    - [5. Install Dependencies](#5-install-dependencies)
- [Running the Project](#running-the-project)
- [Getting Out of `venv`](#getting-out-of-venv)

## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Python 3.6 or higher**: Download from the [official Python website](https://www.python.org/downloads/).
- **pip**: Python’s package installer. It typically comes with Python. Verify by running:
    ```bash
    pip --version
    ```
- **Anaconda** (optional): A distribution of Python and R for scientific computing and data science. Download from the [official Anaconda website](https://www.anaconda.com/products/distribution).
- **Git**: To clone the repository. Download from the [official Git website](https://git-scm.com/).

## Installation

Follow these steps to set up the project on your local machine.

### 1. Clone the Repository

Open your terminal or command prompt and run:

```bash
git clone https://github.com/moeezawann/DataMiningProject4.git
```

### 2. Navigate to the Project Directory

```bash
cd DataMiningProject4
```

### 3. Create a Virtual Environment

It’s recommended to use a virtual environment to manage your project’s dependencies. Create one using `venv`:

```bash
python3 -m venv venv
```

This command creates a virtual environment named `venv` in your project directory.

### 4. Activate the Virtual Environment

- On macOS and Linux:

    ```bash
    source venv/bin/activate
    ```

- On Windows:

    ```bash
    venv\Scripts\activate
    ```

After activation, your terminal prompt should show the name of the virtual environment, e.g., `(venv)`.

### 5. Install Dependencies

Ensure that a `requirements.txt` file exists in the project root. To install the necessary packages, run:

- Using `pip`:

    ```bash
    pip install -r requirements.txt
    ```

    This command installs all the packages listed in `requirements.txt`.

- Using `Anaconda`:

    ```bash
    conda install --file requirements.txt
    ```

    This command installs all the packages listed in `requirements.txt` using Anaconda.

## Running the Project

Run the code by running
```bash
python main.py
```

## Getting Out of `venv`

To deactivate the virtual environment, use the following command:

- On macOS, Linux, and Windows:

    ```bash
    deactivate
    ```

This command will return your terminal to the global Python environment.
