# playing-piano-with-a-robotic-hand
Final project of the MIT 6.834 manipulation, fall 2021

## Dependencies

1. numpy
2. pandas
3. pygame
4. drake
5. drake-manipulation
6. meshcat

## How to run

1. Initialize piano sound library submodule.
```
git submodule update --init --recursive
```

2. Run  `pianobot_notebook.ipynb` at a machine where sound output is available.

3. Pre-computed simulation logs may be available upon requests. Due to its size (~10GB), the repo does not contain the log files.