## Abstract
The ProSeCo Planning framework, short for Probabilistic Semantic Cooperative Planning, is a sophisticated system designed to enhance the capabilities of automated vehicles (AVs). The primary objective of this framework is to equip AVs with the ability to implicitly demand and provide cooperation, thereby integrating smoothly into today's heterogeneous traffic. This is achieved by combining prediction and planning, modeling the problem as a Markov Decision Process (MDP), and considering all possible actions of traffic participants.

The framework employs Monte Carlo Tree Search (MCTS) in conjunction with Decoupled Upper Confidence bounds applied to Trees (DUCT) to identify near-optimal trajectories for all traffic participants. This results in a trajectory planner that enables implicit cooperation among traffic participants. The base algorithm has been further improved through parallelization and hyperparameter optimization to enhance performance and generate better solutions faster. It also incorporates learned reward models based on expert trajectories using Inverse Reinforcement Learning (IRL). This allows the system to adapt to a desired human driving style for smooth integration into human-centered traffic. The effectiveness of the framework has been demonstrated in 15 challenging multi-agent scenarios.

The source code of the ProSeCo Planning package is openly accessible on GitHub under the BSD 3-Clause License, and the runtime environment required to execute the package is available as a container on DockerHub. The research leading to this work was funded by the German Research Foundation (DFG) through the Cooperatively Interacting Automobiles (CoInCar) project.
## Setup
ProSeCo Planning is system independent due to Docker. To get started with the project, follow the instructions of the [proseco_workspace](https://github.com/ProSeCo-Planning/proseco_workspace).
## Citation
Please refer to the respective publication if you are using it for your work. Thank you very much 🙂!
```bibtex
@phdthesis{Kurzer2023,
    author       = {Kurzer, Karl},
    year         = {2023},
    title        = {Implicit Cooperative Decision-Making for Automated Vehicles},
    doi          = {10.5445/IR/1000164561},
    publisher    = {{Karlsruher Institut für Technologie (KIT)}},
    keywords     = {Artificial Intelligence, AI, Machine Learning, ML, Automated Vehicles, AVs, Autonomous Driving, AD, Automated Driving, AD, Cooperation, Multi-agent Markov Decision Process, MMDP, Search, Planning, Decision Making, Trajectory Planning, Monte Carlo Tree Search, MCTS, Decoupled Upper Confidence Bound for Trees, DUCT, Inverse Reinforcement Learning, IRL, Hyperparameter Optimization},
    pagetotal    = {160},
    school       = {Karlsruher Institut für Technologie (KIT)},
    language     = {english},
    url          = {https://publikationen.bibliothek.kit.edu/1000164561}
}

@inproceedings{Kurzer2022,
	title        = {Learning Reward Models for Cooperative Trajectory Planning with Inverse Reinforcement Learning and Monte Carlo Tree Search},
	author       = {Kurzer, Karl and Bitzer, Matthias and Zöllner, J. Marius},
	year         = 2022,
	booktitle    = {2022 IEEE Intelligent Vehicles Symposium (IV)},
	pages        = {22--28},
	doi          = {10.1109/IV51971.2022.9827031},
	url          = {https://doi.org/10.1109/IV51971.2022.9827031}
}
@inproceedings{Kurzer2020b,
	title        = {Accelerating Cooperative Planning for Automated Vehicles with Learned Heuristics and Monte Carlo Tree Search},
	author       = {Kurzer, Karl and Fechner, Marcus and Zöllner, J. Marius},
	year         = 2020,
	booktitle    = {2020 IEEE Intelligent Vehicles Symposium (IV)},
	pages        = {1726--1733},
	doi          = {10.1109/IV47402.2020.9304597},
	url          = {https://doi.org/10.1109/IV47402.2020.9304597}
}
@misc{Kurzer2020a,
	title        = {Parallelization of Monte Carlo Tree Search in Continuous Domains},
	author       = {Kurzer, Karl and Hörtnagl, Christoph and Zöllner, J. Marius},
	year         = 2020,
	publisher    = {arXiv},
	doi          = {10.48550/ARXIV.2003.13741},
	url          = {https://arxiv.org/abs/2003.13741}
}
@inproceedings{Kurzer2018b,
	title        = {Decentralized Cooperative Planning for Automated Vehicles with Continuous Monte Carlo Tree Search},
	author       = {Kurzer, Karl and Engelhorn, Florian and Zöllner, J. Marius},
	year         = 2018,
	booktitle    = {2018 21st International Conference on Intelligent Transportation Systems (ITSC)},
	pages        = {452--459},
	doi          = {10.1109/ITSC.2018.8569988},
	url          = {https://doi.org/10.1109/ITSC.2018.8569988}
}
@inproceedings{Kurzer2018a,
	title        = {Decentralized Cooperative Planning for Automated Vehicles with Hierarchical Monte Carlo Tree Search},
	author       = {Kurzer, Karl and Zhou, Chenyang and Marius Zöllner, J.},
	year         = 2018,
	booktitle    = {2018 IEEE Intelligent Vehicles Symposium (IV)},
	pages        = {529--536},
	doi          = {10.1109/IVS.2018.8500712},
	url          = {https://doi.org/10.1109/IVS.2018.8500712}
}
```
