# Calculator Project

A simple Python calculator built using the command-line interface.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

1. **Python 3.x**  
   The programming language used for this project. You can check if Python is installed by running:
   
```bash
   python --version
```

   If Python is not installed, you can download it from [python.org](https://www.python.org/downloads/).

2. **Virtual Environment (venv)**  
   Python's `venv` is used to create an isolated environment for your project. It is bundled with Python 3.x, so you don’t need to install it separately. To verify if `venv` is available, run:
   ```bash
   python -m venv --help
   ```

3. **Basic Python Knowledge**  
   This project assumes you have a basic understanding of Python programming, such as working with variables, functions, and loops.

## Setup Instructions

Follow these steps to set up the project on your local machine:

### 1. Clone the Repository
Clone the project repository or download the project files:

```bash
git clone https://github.com/vaibhavvatsbhartiya/Vaibhav-Vats-Python-Full-Stack-Developer.git
cd beginner_projects
cd 01_Calculator
```

### 2. Create a Virtual Environment
Set up a virtual environment to manage project dependencies:

```bash
python -m venv venv
```

### 3. Activate the Virtual Environment
Activate the virtual environment:

- **On Windows**:
  ```bash
  venv\Scripts\activate
  ```
- **On macOS/Linux**:
  ```bash
  source venv/bin/activate
  ```

You should now see `(venv)` at the start of your terminal prompt, indicating that the virtual environment is active.

### 4. Install Dependencies (If Any)
Install the necessary dependencies using `pip` (if required). For this basic project, you don’t need any external libraries, but in the future, you can add them to `requirements.txt` if needed.

```bash
pip install -r requirements.txt
```

### 5. Run the Calculator
Run the calculator program:

```bash
python calculator/calculator.py
```

You should now be able to use the calculator in your terminal!

## How the Calculator Works

1. The program will prompt you to choose an operation: addition, subtraction, multiplication, or division.
2. After selecting the operation, you will be asked to input two numbers.
3. The result of the operation will be displayed on the screen.
