# Python Concepts & Practical Learning Repository

A comprehensive Python learning repository covering fundamental concepts, practical implementations, and hands-on exercises designed for beginners to intermediate Python developers.

## 📚 Repository Overview

This repository is structured to provide a progressive learning path through Python programming concepts, starting from environment setup to advanced topics. Each section includes theoretical concepts, practical examples, and exercises.

## 🗂️ Repository Structure

### 📁 00-Python-Virtual-Environment

Learn how to set up and manage Python virtual environments using different tools:

- **Commands/**: Virtual environment setup commands and instructions
- **using-python-venv/**: Example setup using Python's built-in `venv` module
- **using-virtualenv/**: Example setup using the `virtualenv` package

**Virtual Environment Methods Covered:**

- Python built-in `venv` module
- `virtualenv` package
- Anaconda/Conda environments

### 📁 01-Python-Basics

Foundation Python concepts and syntax:

- **1.0-Basic.ipynb**: Introduction to Python basics
- **1.1-Variables.ipynb**: Variables, data types, and basic operations
- **test.py**: Practice Python scripts

## 🚀 Getting Started

### Prerequisites

- Python 3.8+ installed on your system
- Basic understanding of command line/terminal operations

### Setting Up Your Environment

#### Method 1: Using Python venv (Recommended)

```bash
# Create virtual environment
python -m venv myenv

# Activate virtual environment
# On Windows:
myenv\Scripts\activate
# On macOS/Linux:
source myenv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Deactivate when done
deactivate
```

#### Method 2: Using virtualenv

```bash
# Install virtualenv if not already installed
pip install virtualenv

# Create virtual environment
virtualenv -p python3 virtual_env

# Activate virtual environment
# On Windows:
virtual_env\Scripts\activate
# On macOS/Linux:
source virtual_env/bin/activate

# Deactivate when done
deactivate
```

#### Method 3: Using Anaconda/Conda

```bash
# Create conda environment
conda create -p venv python==3.12

# Activate environment
conda activate venv/

# Install dependencies
pip install -r requirements.txt

# Deactivate environment
conda deactivate
```

## 📖 Learning Path

### 1. Environment Setup (00-Python-Virtual-Environment)

- Understand the importance of virtual environments
- Learn different methods to create and manage environments
- Practice with provided examples

### 2. Python Basics (01-Python-Basics)

- Python syntax and basic concepts
- Variables and data types
- Basic operations and expressions

## 🛠️ Tools & Technologies

- **Python 3.8+**: Core programming language
- **Jupyter Notebooks**: Interactive learning environment
- **Virtual Environments**: Isolated Python environments
- **Git**: Version control

## 📋 Requirements

The project dependencies are listed in `requirements.txt`:

```txt
ipykernel
```

Additional packages may be added as the repository grows.

## 🤝 Contributing

This is a learning repository. If you'd like to contribute:

1. Fork the repository
2. Create a feature branch
3. Add your improvements or fixes
4. Submit a pull request

## 📞 Support

If you encounter any issues or have questions:

- Check the documentation in each folder
- Review the example implementations
- Create an issue for bugs or suggestions

## 📄 License

This project is for educational purposes. Feel free to use and modify for your learning journey.

## 🎯 Future Topics (Planned)

- Data Structures and Algorithms
- Object-Oriented Programming
- File Handling and I/O Operations
- Error Handling and Exceptions
- Modules and Packages
- Web Development with Flask/Django
- Data Analysis with Pandas
- API Development
- Testing and Debugging

---

**Happy Learning! 🐍**

*This repository is continuously updated with new concepts and practical examples.*
