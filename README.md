# This project is for creating directories for the project through pathlib
## Step 1: Import libraries
```
""" Start a data analytics project. """
import pathlib
```
## Step 2: Create a function that takes a parameter for the name of a directory
```
def create_project_directory(directory_name: str):
    """
    Create a project sub-directory.
    :param directory_name: Name to be created, e.g. "test"
    """
    pathlib.Path(directory_name).mkdir(exist_ok=True)
```
## Step 3: Create main() function create_project_directory() function to create directories
```
def main():
    """ Scaffold a project. """
    create_project_directory(directory_name='test')
    create_project_directory(directory_name='docs')
```
## Step 4: Call main() function
```
if __name__== '__main__':
    main()
```

```
