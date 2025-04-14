# Notebooks for Behrens lab GridMaze tutorial on 14/4/25
@peterdoohan @charlesburns

### Note: you'll need to have access to ceph (SWC cluster) for these notebooks to run

### Before the tutorial
- Copy this folder to your working directory or navigate to:
    ```
    cd /ceph/behrens/peter_doohan/tutorials
    ```

- Make a new conda envionment from the requirements.txt in this repo:

    ```
    conda env create -f environment.yml --name GridMaze_tutorial
    ```

### Overview

We have 3 notebook tutorials that go with the in-person [presentation]("https://docs.google.com/presentation/d/1lQRU-A8gok-EogLtmchHHPMcaNdZcJtJo8tCKBUeOZY/edit?usp=sharing")

1. maze_representations.ipynb
    Details how mazes are represented in code (Dataset: goalNav_mFC)

2. accessing_maze_data.ipynb
    Explains how experiments are represented on disk and how you can load that data for your own analyses (Dataset: goalNav_mFC)

3. using_unitmatch.ipynb
    Quick demonstration on how to match cells (recorded with ephys) across days and session types (Dataset: goalNav_mEC)


