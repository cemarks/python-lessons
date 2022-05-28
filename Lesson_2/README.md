# Lesson 2: Python Development & Pytest

## Objectives

1. Set up your development environment.
1. Understand how to run `pytest` and what it does.
1. Read and understand the basic structure of a python script.
    * Understand what `import` statements do.
    * Understand the function declarations and structure.
    * Identify and understand the execution lines
    * Understand the meaning of `if __name__ == "__main__":`
1. Understand how python interprets indentation.
1. Modify a simple function to make it work.
1. Understand documentation blocks and why they are important.  Note, these lessons will adhere to [Numpy Style](https://numpydoc.readthedocs.io/en/latest/format.html) documentation. 
1. Understand what a code style-guide is and why it is important to conform to an accepted coding style. The code in these lessons will conform to the [Google Python Style Guide](https://github.com/google/styleguide/blob/gh-pages/pyguide.md#38-comments-and-docstrings).
1. Understand type hinting and why it is useful to run `pylint`.

## Key Terms

* Module
* Function
* Script
* Parameter
* Variable and variable assignment
* Object
* Type (string, float, int)
* Return value
* Documentation
* Conditional (`if`) statement

## Activities

1. Use git to commit your work from the previous lesson, then pull from the github repository.
    ```sh
    git add -A
    git commit -m "Completed Lesson 1"
    git pull --rebase=true
    ```

1. Set up a virtual environment, activate, and install requirements.txt.
    ```sh
    cd Lesson_2
    python -m venv env
    source env/bin/activate
    pip install -r requirements.txt
    ```

1. Use your development environment to open hello.py and interpret what the script will do when it runs.
1. Run hello.py (from the terminal or using the IDE) and interpret the result.
    ```sh
    python hello.py
    ```

1. Run pytest and explain why the test fails.
    ```sh
    pytest
    ```
    
1. Fix hello.py so that it passes the tests, and confirm with pytest.
1. Run the script again and note the difference.
