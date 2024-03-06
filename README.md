# FastAPI Boilerplate

This project serves as a template for creating applications with a simple endpoint using FastAPI. It is designed to get you up and running with FastAPI with minimal setup.

## Quick Start Guide

### Prerequisites

Ensure you have the following installed:

- python 3.11
- Pipenv (You can find the installation guide here: [Pipenv Documentation](https://pipenv-fork.readthedocs.io/en/latest/))

### Installation

1. **Set Up Virtual Environment and Install Dependencies**

   Use Pipenv to create a virtual environment and install the necessary dependencies:

   ```bash
   pipenv install
   ```

2. **Activate the Virtual Environment**

   To activate the virtual environment, run:

   ```bash
   pipenv shell
   ```

3. **Start the FastAPI Server**

   Launch the FastAPI server with uvicorn using the following command:

   ```bash
   uvicorn main:app --reload
   ```