# Wolf-Sheep-Grass Ecosystem Simulation

This project simulates a dynamic ecosystem of wolves, sheep, and grass. It allows you to explore population dynamics and interactions between predator, prey, and their environment using a cellular automaton model.

## Features

- **Grass Growth**: Regrows over time, serving as food for sheep.
- **Sheep Dynamics**: Move, eat grass, lose energy, and reproduce.
- **Wolf Dynamics**: Move, hunt sheep, lose energy, and reproduce.
- **Customizable Parameters**: Adjust grid size, initial populations, energy gains, reproduction rates, and more.
- **Interactive Widgets**: Use sliders and text inputs for real-time simulation customization.
- **Visualization**: Population dynamics plotted over time, showing trends in sheep, wolves, and grass.

## Requirements

- Python 3.7+
- Required libraries:
  - `numpy`
  - `matplotlib`
  - `ipywidgets`
  - `IPython`

Install dependencies using pip:

```bash
pip install numpy matplotlib ipywidgets


## How to Run

1. **Clone the repository or download the script.**
2. **Open the script in a Jupyter Notebook environment.**
3. **Execute all cells** to initialize the simulation environment.
4. **Use the interactive sliders** to set parameters such as:
   - **Grid Size**
   - **Initial Populations** (Sheep and Wolves)
   - **Grass Regrowth Rate**
   - **Energy Gains** (for Sheep and Wolves)
   - **Reproduction Rates**
   - **Energy Loss Rate**
5. **View the population dynamics plot** generated at the end of the simulation.


![Population Dynamics Plot](population_dynamics.png "Population Dynamics Over Time")
