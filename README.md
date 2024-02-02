# Digipodium Python Data Analytics and Data Science Environment Setup

## Table of Contents

1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
   - [Miniconda](#miniconda)
   - [Git](#git)
   - [VSCode](#vscode)
   - [VSCode Extensions](#vscode-extensions)
   - [Git Configuration](#git-configuration)
   - [Jupyter Notebook Integration](#jupyter-notebook-integration)
4. [Conclusion](#conclusion)

## Introduction

Welcome to the Digipodium Python Data Analytics and Data Science Environment Setup documentation. This guide will walk you through the step-by-step process of setting up your environment for Python data analytics and data science.

## Prerequisites

Before you begin, make sure you have the following prerequisites installed:

- A computer with internet access
- Basic familiarity with the command line

## Installation

### Miniconda

Miniconda is a minimal distribution of Conda, a package manager for Python. It is recommended for managing your Python environments.

1. **Download Miniconda:**
   - Visit the [Miniconda website](https://docs.conda.io/en/latest/miniconda.html) and download the appropriate installer for your operating system.

2. **Install Miniconda:**
   - just check all the boxes and press next

### Git

Git is a version control system that will help you track changes in your code.

1. **Download Git:**
   - Visit the [Git website](https://git-scm.com/downloads) and download the installer for your operating system.

2. **Install Git:**
   - dont change any setting, keep pressing next and it will be installed. close allter

### VSCode

Visual Studio Code (VSCode) is a powerful code editor that provides excellent support for Python development.

1. **Download VSCode:**
   - Visit the [VSCode website](https://code.visualstudio.com/) and download the installer for your operating system.

2. **Install VSCode:**
   - Follow the installation instructions provided on the VSCode website.

### VSCode Extensions

Enhance your VSCode experience with the following extensions:

1. **Python Extension:**
   - Open VSCode.
   - Navigate to the Extensions view (`Ctrl + Shift + X`).
   - Search for "Python" and install the one provided by Microsoft.

2. **SQLite3 Editor Extension:**
   - Open VSCode.
   - Navigate to the Extensions view (`Ctrl + Shift + X`).
   - Search for "SQLite" and install the "SQLite" extension.

3. **VSCode Icons:**
   - Open VSCode.
   - Navigate to the Extensions view (`Ctrl + Shift + X`).
   - Search for "VSCode Icons" and install the one you prefer.

### Git Configuration

Configure your Git username and email:

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

Replace "Your Name" and "your.email@example.com" with your actual name and email.

### Jupyter Notebook Integration

To use Jupyter Notebooks inside VSCode, install the `ipykernel` package using the following command:

```bash
conda install -c anaconda ipykernel
```

Now, you can create and run Jupyter Notebooks directly within VSCode.

## Conclusion

Congratulations! You have successfully set up your Python data analytics and data science environment using Miniconda, Git, and VSCode. Happy coding!
