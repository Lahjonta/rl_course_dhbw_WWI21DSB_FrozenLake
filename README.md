# WWI21DSB - Reinforcement Learning: FrozenLake Upgrade

This project, created for the Reinforcement Learning course (WWI21DSB, 2024), enhances the classic FrozenLake environment. The upgraded version introduces several new features:

-   Boosters: Special objects on the lake that increase the agent's step size.
-   Weapons: Collectible items that allow the agent to defeat enemies.
-   Enemies: Entities that chase the agent and can end the game if they catch it.

These additions increase the difficulty level of reinforcement learning experiments, offering new challenges and opportunities for strategy development. 
The agent is trained using Q-Learning in a non-slippery environment to facilitate a clearer understanding of the learning process.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
  
## Prerequisites

Ensure you have the following software installed on your system:

- Python 3.7 or higher
- Jupyter Notebook

## Installation

1. **Clone the repository**
   ```sh
   git clone https://github.com/Lahjonta/rl_course_dhbw_WWI21DSB_FrozenLake
   cd https://github.com/Lahjonta/rl_course_dhbw_WWI21DSB_FrozenLake

2. **Set up virtual environment (optional)**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

3. **Install Dependencies**
   ```sh
   pip install -r requirements.txt

## Usage
1.  **Start Jupyter Notebook**
    ```sh
    jupyter notebook

2.  **Open the FrozenLake_Upgrade.ipynb notebook**

    In the Jupyter interface, navigate to the directory where you cloned the repository and open the FrozenLake_Upgrade.ipynb file. 
    Run the notebook
    Execute the cells in the notebook sequentially to see the code and outputs for the FrozenLake environment upgrade and experiments.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.


   
