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

3. If you want to run the result of pre-computed dynamic simulation, unzip the pre-computed log inside the log folder.
