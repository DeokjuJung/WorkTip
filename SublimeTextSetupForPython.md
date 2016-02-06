# Sublime Text 3 Setup for Python

##### Sublime Text Setup

1. Install Sublime Text 3

2. Install Sublime Text Package Control

3. Install Package : SublimeREPL

4. In the Tools menu, select Build System -> Add New Build System and save as SublimeREPL-python.sublime-build
```
{
    "target": "run_existing_window_command", 
    "id": "repl_python_run",
    "file": "config/Python/Main.sublime-menu"
}
```

5. In the Tools menu, select Build System -> SublimeREPL-python

6. Write a sample python program and run it!

##### Tip

1. Select View -> Layout -> Rows : 2 to view the result in the same window.

2. Add a macro to write a colon and new line at end of line.


