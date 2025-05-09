# Data Type Investigation

You have a box that can contain any type of object (integer, float, string, list, etc.). Write a Python program that takes this object as input, determines its data type, and prints out whether it’s an integer, float, string, list, or dictionary.

??? Hints
    - You can use the `type()` function to determine the data type of an object.
    - Use conditional statements (if, elif, else) to check the type and print the appropriate message.
    - Consider using a dictionary to map types to their string representations for cleaner code.

## Before You Begin
The boilerplate code has been provided for you. Open the file `src/datatypes/object_type.py` in vscode. You will need to implement the function: `print_data_type(obj)`. 

## How to test
1. Run your program with `python object_type.py`.
2. Try adding different types of values under `if __name__ == "__main__":` block and see if it works as expected.
```python
if __name__ == "__main__":
    # Test with various conversions
    print_data_type(123)
    print_data_type("hello")
    print_data_type('test')
```
!!! Note
    Your tests should cover more data types than in the example.

## How to Submit

From github desktop or the command line, commit your changes and push them to your repository.

### Codespaces
If you are using codespaces, you can commit your changes directly from the Codespace interface. Click on the Source Control icon in the left sidebar, then click on the "..." button and select "Commit to main". Enter a commit message and click "Commit".

#### Codespace terminal or your local terminal. 

!!! Note
    You will need to have installed `git-scm` for this to work locally

At the `/datatypes $` prompt in your terminal:
```
git add -A 
```
Add all changed files in the repository to be committed
```
git commit -m "Upload completed object_type.py"
```
Commit all changes in the REPO with the comment “Upload completed object_type.py“ note: If the file is not complete, adjust the comment to describes what is being committed
```
git push 
```
Push all changes to the repo.