# Notes
### 5 Python tricks/tips
- Interactive Shell 
    - Instead of writing something like python main.py in terminal, you can write python -i main.py and run the file in shell. Instead of closing after running, it will give you access to functions and variables. 

- Python Debugger (pdb)
    - ```
      import pdb
      pdb.set_trace()
      ```

- The Virtual Environment
    - Dependency management can be quite annoying
    - ex: pip install virtualenv venv
    - Making projects portable

- List and Dict Comprehension
    - Instead of extracting certain elements ins a dict using multiple lines of code, we can use list comprehension.
    - list comprehension
    ```
        fruit_names = [fruit['name']] for fruit in fruits if fruit['name'][0] == 'a'
    ```

- Lambda Functions
