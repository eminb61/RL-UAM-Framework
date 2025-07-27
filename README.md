# UAM Fleet Management with Deep Reinforcement Learning

A reinforcement learning framework for optimizing Urban Air Mobility (UAM) fleet operations in multi-vertiport networks. This repository implements the methodology described in "Online Fleet Management Under Uncertainty: A Deep Reinforcement Learning Approach" using VertiSim simulation environment.

## Overview

This project addresses the complex challenge of real-time fleet management in UAM networks by simultaneously optimizing:
- **Aircraft dispatch decisions** - when and which aircraft should serve waiting passengers
- **Routing decisions** - destination selection and repositioning flights
- **Charging scheduling** - optimal charging policies for eVTOL aircraft

Our approach formulates the problem as a Markov Decision Process (MDP) and employs Proximal Policy Optimization (PPO) enhanced with Long Short-Term Memory (LSTM) networks to learn adaptive policies that balance immediate service delivery with long-term operational efficiency.

## Key Features

- **Integrated RL Framework**: PPO+LSTM implementation specifically designed for UAM fleet management
- **VertiSim Integration**: Built on our open-source discrete-event simulation platform for UAM networks
- **Realistic Constraints**: Incorporates battery limitations, vertiport capacity, passenger waiting times, and safety reserves
- **Action Masking**: Ensures operational feasibility by restricting invalid actions based on current system state
- **Scalable Architecture**: Tested on networks ranging from 2 vertiports to complex hub-and-spoke configurations

## TODO
Running instructions

## Acknowledgments

This work was developed at UC Berkeley's Cal Unmanned Lab under the guidance of Professor Raja Sengupta. Special thanks to the VertiSim development team and NASA collaborators for their support and insights.

# Citation
1. Onat, E. B., Cao, A., Sengupta, R., & Hansen, M. Urban Air Mobility Fleet Management Under Uncertainty: A Deep Reinforcement Learning Approach. Available at SSRN 5072017.
2. Onat, E. B. (2024). Urban Air Mobility: Infrastructure and Operations (Doctoral dissertation, University of California, Berkeley).
