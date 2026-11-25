# analog-tools

Python scripts I'm building while studying circuit analysis (EE 222, Fundamentals of Electric Circuits by Alexander & Sadiku). Each tool solves a type of problem I also work by hand, so it doubles as an answer checker.

## Tools
| Script | What it does | Status |
| --- | --- | --- |
| ohms.py | Solves V, I or R from the other two, plus power | in progress |
| divider.py | Voltage and current divider calculator | planned |
| two_node.py | Two-node nodal analysis with Cramer's rule | planned |
| two_mesh.py | Two-mesh analysis with Cramer's rule | planned |
| thevenin.py | Load-power table for a Thevenin equivalent | planned |
| nodal.py | Nodal analysis for any size circuit (NumPy) | planned |
| rc_plot.py | Plots RC charging/discharging vs measured data | planned |

## Run
Python 3.15+. Install libraries: `python -m pip install numpy matplotlib`

Run a tool: `python ohms.py`

## Author
Jahmari Jones, BSEE student, Jacksonville University
