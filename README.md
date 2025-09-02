[![Python Template for IDS706](https://github.com/Pat-Zhu/IDS_706_HW1_NEW/actions/workflows/main.yml/badge.svg)](https://github.com/Pat-Zhu/IDS_706_HW1_NEW/actions/workflows/main.yml)
# IDS_706_HW1_NEW

The repository for homework 1 IDS_706

##  Project Description
This project is developed as part of **IDS706 Homework 1**.  
It demonstrates the use of Python, Makefile, and GitHub Actions. 

The repository includes:
- A simple Python script (`hello.py`)
- Linting setup using `flake8`
- A Makefile to automate tasks
- Unit tests in `test_hello.py`
- A `requirement.txt` file for the required packages
- A GitHub Actions workflow for CI

##  Setup Instructions

 **Clone the repository and install necessary dependencies**
   ```bash
   git clone https://github.com/Pat-Zhu/IDS_706_HW1_NEW.git
   cd IDS_706_HW1_NEW
   ```
   ```python
   pip install -r requirements.txt
   ```

## Usage Examples

This project includes a simple Python script (`hello.py`) and corresponding tests (`test_hello.py`).  
Below are examples of how to run them.

1. Run the Python script
```bash
python hello.py
```

```python
from hello import say_hello, add, multi

print(say_hello("Patrick"))
print("2 + 3 =", add(2, 3))
print("2 * 3 =", multi(2, 3))
```

The output will be 

Hello, Patrick, welcome to Data Engineering Systems (IDS 706)!

2 + 3 = 5

2 * 3 = 6

2. Run the test script with pytest or using the make file
   
```bash
pytest test_hello.py
```
or

```bash
make test
```
