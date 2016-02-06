# Sublime Text 3 Setup for Python

### Sublime Text Setup

- Install Sublime Text 3
- Install Sublime Text Package Control

### Setup for Python running environment

- Install Package : SublimeREPL
- In the Tools menu, select Build System -> Add New Build System and save as SublimeREPL-python.sublime-build

```
{
    "target": "run_existing_window_command", 
    "id": "repl_python_run",
    "file": "config/Python/Main.sublime-menu"
}
```

- In the Tools menu, select Build System -> SublimeREPL-python
- Write a sample python program and run it using 'ctrl+B'!

### Tip

- Select View -> Layout -> Rows : 2 to view the result in the same window.
- Add a macro to write a colon and new line at end of line.


