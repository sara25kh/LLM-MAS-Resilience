# LLM-MAS-Resilience
This project models fault propagation and hallucination spread in Large Language Model Multi-Agent Systems (LLM-MAS) using graph-based simulations. Different network topologies including Path, Complete, Tree, and Small-World graphs are analyzed to evaluate system resilience under random and targeted (high-impact) fault injection strategies. 

Two diffusion models are implemented: the Independent Cascade (IC) probabilistic model and a Trust-based threshold model. The project compares how topology structure, node centrality, and trust dynamics influence cascade behavior, system collapse, and robustness.

The goal is to analyze worst-case attack scenarios, identify critical nodes, and evaluate structural resilience across different network architectures.

# Probabilistic Attack Graph Simulator (PAGS)
PAGS is a network robustness analysis project implemented using Python and the NetworkX library. The framework models attack propagation on graph-based networks and evaluates system resilience through Monte Carlo simulations. Key metrics such as Network Blast Radius, Overall Compromise Probability, and RASR (Robustness–Attack Success Rate) are computed to quantify how attacks spread and how likely a system is to be compromised. The project provides a lightweight and flexible environment for analyzing probabilistic attack behavior using graph theory, statistical simulation, and visualization tools.

This project implements a probabilistic attack propagation model on graph-based networks using NetworkX. Monte Carlo simulations are performed to estimate the blast radius of attacks, the probability of overall system compromise, and the RASR robustness metric. The implementation relies on Python scientific libraries (NumPy, Pandas, Matplotlib) and provides visual and statistical insights into network resilience under stochastic attack scenarios.
# Prerequisites

Before running the code, make sure you have the following installed:

- Python 3
- Virtualenv

To install Virtualenv, run the following command:
```
python3 -m pip install virtualenv
```

# Run

To execute the code using the virtual environment (venv), follow these steps:

1. Create a virtual environment named `myenv` by running the following command:
    ```
    python3 -m venv venv
    ```

2. Activate the virtual environment by running the appropriate command based on your operating system:
    - For Linux/Mac:
        ```
        source venv/bin/activate
        ```
    - For Windows:
        ```
        venv\Scripts\activate
        ```

3. Install the required packages by running the following command:
    ```
    pip install -r requirements.txt
    ```

4. Remember to deactivate the virtual environment when you're done by running the following command:
    ```
    deactivate
    ```

