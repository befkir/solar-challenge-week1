# Solar Challenge Week 1

Welcome to the Solar Challenge Week 1 project repository! This repository contains the code, tests, and documentation related to the first week of the solar challenge. The goal of this challenge is to build a scalable and maintainable solution for a solar-powered system.

# Project Structure

The repository is organized into the following structure:

```
├── .vscode/
│ └── settings.json # VS Code workspace settings
├── .github/
│ └── workflows # GitHub Actions CI/CD configuration
│ ├── unittests.yml # Unit testing workflow
├── .gitignore # Git ignore rules to exclude unnecessary files
├── requirements.txt # Python dependencies for the project
├── README.md # Project overview and documentation
├── src/ # Main source code for the project
├── notebooks/ # Jupyter notebooks for experimentation
│ ├── **init**.py # Initialization file
│ └── README.md # Notebooks-related documentation
├── tests/ # Unit tests for the project
│ ├── **init**.py # Initialization file for tests
├── scripts/ # Utility and helper scripts
│ ├── **init**.py # Initialization file
│ └── README.md # Scripts-related documentation
└── env/ # Virtual environment folder (exclude from version control)
```
# Prerequisites

To get started, ensure you have the following installed on your system:

Python 3.7 or above

pip (Python package installer)

# Setting Up the Development Environment

1. Clone the Repository
   Start by cloning the repository to your local machine:

```
git clone https://github.com/yourusername/solar-challenge-week1.git
cd solar-challenge-week1 2. Create a Virtual Environment
```

For isolating dependencies, it's recommended to create and activate a virtual environment. Here's how to do it:

On macOS/Linux:

```
python3 -m venv env
source env/bin/activate
```

On Windows:

```
python -m venv env
```

.\env\Scripts\activate 3. Install Dependencies
Once your virtual environment is active, install the required Python dependencies:

```
pip install -r requirements.txt
```

# Running the Project

The source code for the project can be found in the src/ directory.

Notebooks for experimentation and exploration are located in the notebooks/ directory.

Unit tests for the project are located in the tests/ directory. You can run the tests using a testing framework like pytest:

```
pytest tests/
```

# CI/CD Workflow

The repository includes an automated testing workflow through GitHub Actions. The CI/CD pipeline is configured to run unit tests whenever changes are pushed to the repository.

The workflow configuration can be found under .github/workflows/unittests.yml.

# Contributing

Contributions to this project are welcome! To contribute, please fork the repository, make your changes, and submit a pull request. Ensure that your code passes all tests and adheres to the coding standards.
