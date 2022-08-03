# Adaptive Planner Parameter Learning from Reinforcement

This repository contains the [APPLR](https://www.cs.utexas.edu/~xiao/papers/applr.pdf) navigation approach adapted for usage in arena-rosnav platform.    
For original work refer to [UTexas](https://www.cs.utexas.edu/~xiao/Research/APPL/APPL.html#applr) and [original repository](https://github.com/Daffan/nav-competition-icra2022/tree/applr).  
**Please note** APPLR is appropriate for usage on **only** the [Jackal platform](https://clearpathrobotics.com/jackal-small-unmanned-ground-vehicle/).

# Installation

## Activate poetry shell
```bash
cd arena-rosnav # navigate to the arena-rosnav directory
poetry shell
```
## Make sure to source the workspace environment
```bash
cd ../.. # navigate to the catkin_ws directory
source devel/setup.zsh # if you use bash: source devel/setup.bash 
```
## Install Python dependencies
```bash
pip install -r requirements.txt
```
