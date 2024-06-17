# wyag - Rewriting Git in Python

Welcome to wyag! This project is an educational journey to understand the internals of Git by rewriting it in Python. This repository follows the guide ["Write Yourself a Git"](https://wyag.thb.lt/) by Thibault Polge.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

wyag is an attempt to demystify the inner workings of Git by implementing its core functionalities in Python. This project is inspired by the "Write Yourself a Git" guide and aims to provide a hands-on learning experience for those interested in understanding how version control systems work under the hood.

## Features

- **Initialization**: Create a new repository.
- **Committing**: Record changes to the repository.
- **Branching**: Create, list, and switch branches.
- **Merging**: Combine different branches.
- **Logging**: View commit history.
- **Diffing**: Show changes between commits.

## Installation

To get started with wyag, you'll need Python 3.6 or higher. You can clone this repository and install the necessary dependencies:

```bash
git clone https://github.com/yourusername/wyag.git
cd wyag
pip install -r requirements.txt
```

## Usage

Once installed, you can start using wyag from the command line. Here are some basic commands:

```bash
# Initialize a new repository
python wyag.py init

# Add a file to the staging area
python wyag.py add <file>

# Commit changes
python wyag.py commit -m "Your commit message"

# Create a new branch
python wyag.py branch <branch_name>

# Switch to a branch
python wyag.py checkout <branch_name>

# Merge a branch into the current branch
python wyag.py merge <branch_name>

# View commit history
python wyag.py log

# Show changes between commits
python wyag.py diff <commit1> <commit2>
```

For a full list of commands and options, refer to the documentation or use the `--help` flag:

```bash
python wyag.py --help
```

## Project Structure

Here's an overview of the project structure:

```
wyag/
├── libwyag.py      # Core functionality of the 'wyag' package
├── wyag.py         # Main executable script
├── setup.py        # Defines the installation details
└── README.md       # This README file
```

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request. Make sure to follow the code style and include tests for new features.

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature-branch`)
6. Create a new Pull Request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [Gabriele Cinà](https://github.com/gabrycina/) For inspiring us with his live to follow this project with him.
- [Thibault Polge](https://wyag.thb.lt/) for the "Write Yourself a Git" guide.
- [The Git Community](https://git-scm.com/community) for their incredible work on Git.
