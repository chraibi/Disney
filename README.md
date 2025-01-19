# Disney Simulation

This is a simulation using [JupedSim](www.jupedsim.org)

## Usage

To get started, create a virtual environment and install the required packages by following these steps:

```bash
# Create a virtual environment
python3 -m venv .venv

# Activate the virtual environment
source .venv/bin/activate

# Install the required packages
pip install jupedsim plotly
```
<img width="666" alt="Screenshot 2025-01-19 at 18 47 00" src="https://github.com/user-attachments/assets/0fd8f680-e3e3-4d99-a8b3-0bf3fff015cc" />



## TODOs 

- [ ] Create more than one goal
- [ ] Fake close goals. In JuPedSim goals are polygons. As soon as agents enter them, they are taken out of the simulation.
      To simulation closed doors, set `agent.model.v0` to 0 in some area before the exits.
- [ ] When creating the agents, and in case there is a jam, the simulation will break with the error: RuntimeError: Model constraint violation: Agent too close to agent.
      This needs some work to fix.       
