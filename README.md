# manipulation_final_project

## Installation

Use Deepnote with [russtedrake/manipulation:mesh_painter Docker Image](https://hub.docker.com/layers/russtedrake/manipulation/mesh_painter/images/sha256-8fc458eafa518bd2d23386e3c0960863c2f9a55abf29adfb1043ee7fa1af5337?context=explore) 

or

Install pydrake and additional dependencies locally then run with russtedrake/manipulation:mesh_painter Docker Image

## Code

Our repository consists of code to wipe a single plate with our hybrid force-position controller (final_plate_wipe.ipynb), generate and evaluate waypoints to wipe using our different optimization approaches (final_trajectory_evaluation.ipynb), and run our full contoller (final_experiments.ipynb)[WARNING running is very slow on Deepnote].

## Paper

Also in this repository is our paper for the project.

Enjoy!



## Note: Running the MeshPainter Notebook
### Prerequisite:
Unfortunately, we have not found a way to get this code to work with DeepNote (please do try though using the docker container `russtedrake/manipulation:mesh_painter`). Thus, in order to run it, you will have to first clone [this PR of Drake](https://github.com/RobotLocomotion/drake/pull/16147), and then [install PyDrake from source](https://drake.mit.edu/python_bindings.html). 

Install moviepy with `pip install moviepy`

### Usage
You should be able to just run all cells in the notebook. Take care to read the comments: you will probably have to change particular paths and uncomment various lines.
