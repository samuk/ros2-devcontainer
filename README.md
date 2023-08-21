# Development container for ROS2 Humble Hawksbill
## OS : Ubuntu 22.04 Jammy Jellyfish

## Install

1) Download and install [VScode](https://code.visualstudio.com/Download)
2) In VScode go Extensions > Install devcontainer
3) Download and extract this repo
4) Edit devcontainer.json for your GPU/ graphics card
5) Open this repo in VScode
6)  Ctrl+shift+p then click “Reopen in devcontainer” to build the environment and start.


## Features added : Desktop-lite, Nvidia Cuda, python, git
Additional packages installed. (Check installation-script.sh for detailed view)

GUI desktop access tutorial available [here.](https://github.com/devcontainers/features/tree/main/src/desktop-lite)

Review nvidia hardware availability and modify devcontainer.json file before building container.
Alternatively, use the main-noGPU branch for github codespaces or devices without nvidia hardware.

