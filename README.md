Apache License
Version 2.0, January 2004
http://www.apache.org/licenses/

TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

...
# My GitHub Repository

Welcome to my GitHub repository! This project aims to showcase the use of simple interest calculation through a shell script.

## Contents
- [License](LICENSE)
- [Code of Conduct](CODE_OF_CONDUCT)
- [Contributing Guidelines](CONTRIBUTING.md)
- [Simple Interest Script](simple-interest.sh)

## Usage
To use the simple interest script, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
cd your-repo
./simple-interest.sh 1000 5 2
# Code of Conduct

## Our Pledge

In the interest of fostering an open and welcoming environment, we as contributors and maintainers pledge to make participation in our project and our community a harassment-free experience for everyone, regardless of age, body size, ...

# Contributing Guidelines

Thank you for considering contributing to our project! We welcome your contributions.

## Reporting Issues

If you encounter any issues with the project, please open an issue on our [GitHub repository](https://github.com/your-username/your-repo/issues).

## Pull Requests

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m 'Add feature'`.
4. Push to your branch: `git push origin feature-name`.
5. Submit a pull request.

...

#!/bin/bash

# Simple Interest Calculation Script

principal=$1
rate=$2
time=$3

# Simple Interest formula: SI = (P * R * T) / 100
interest=$((($principal * $rate * $time) / 100))

echo "Principal: $principal"
echo "Rate of Interest: $rate%"
echo "Time: $time years"
echo "Simple Interest: $interest"
