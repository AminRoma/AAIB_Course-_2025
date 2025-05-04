# Reinforcement Learning for Dynamic Pricing Tutorial

## Overview

This repository contains a comprehensive Jupyter notebook tutorial on applying reinforcement learning (RL) to dynamic pricing problems. The tutorial is designed for students in a Deep Reinforcement Learning course, providing both theoretical background and practical implementation.

## Key Business Aspects Covered

The tutorial addresses several critical business challenges in pricing strategy:

1. **Variable Demand**: Modeling how customer demand fluctuates based on price, seasonality, and random factors
2. **Competitive Market**: Implementing strategic competitor pricing that responds to our pricing decisions
3. **Limited Inventory**: Optimizing pricing with finite inventory constraints
4. **Profit vs. Market Share**: Balancing immediate profit against long-term market share
5. **Seasonal Patterns**: Adapting to weekend and holiday effects on demand

## Reinforcement Learning Algorithms

The tutorial implements and compares three RL algorithms:

1. **Monte Carlo**: Learning directly from complete episodes without bootstrapping
2. **Deep Q-Network (DQN)**: Using experience replay and a neural network for Q-value approximation
3. **Double DQN**: Separating action selection and evaluation to reduce overestimation bias

## Educational Visualizations

The notebook includes several visualizations to help students understand key concepts:

- **Pricing Strategy Comparison**: Visual comparison of different pricing approaches
- **Competitor Interaction**: How agents respond to competitor pricing
- **Market Share Analysis**: Understanding the trade-offs between pricing and market share
- **Seasonal Adaptation**: How agents adapt to day-of-week patterns

## Getting Started

### Prerequisites

- Python 3.6+
- Jupyter Notebook
- Required packages: numpy, tensorflow, matplotlib, seaborn, tqdm, pandas

### Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/rl-dynamic-pricing-tutorial.git
   ```

2. Install required packages:
   ```
   pip install numpy tensorflow matplotlib seaborn tqdm pandas
   ```

3. Open the Jupyter notebook:
   ```
   jupyter notebook RL_Dynamic_Pricing_Complete.ipynb
   ```

## Tutorial Structure

The notebook is organized in a logical progression:

1. **Introduction and Setup**: Background on RL for dynamic pricing
2. **Environment Implementation**: Creating a realistic pricing environment
3. **Agent Implementations**: Implementing three RL algorithms
4. **Training Pipeline**: Training and comparing the agents
5. **Evaluation and Analysis**: Detailed performance comparison
6. **Business Insights**: Key takeaways for pricing strategy
7. **Extensions**: Suggestions for further exploration

## Learning Outcomes

After completing this tutorial, students will:

- Understand how to formulate pricing as a reinforcement learning problem
- Implement and compare different RL algorithms for pricing optimization
- Analyze how different business factors affect optimal pricing strategy
- Gain practical experience applying RL to a real-world business problem

## Citation

If you use this tutorial in your research or teaching, please cite:

```
@misc{rl-dynamic-pricing-tutorial,
  author = {Amin Asadi},
  title = {Reinforcement Learning for Dynamic Pricing Tutorial},
  year = {2025},
  publisher = {GitHub},
  url = {https://github.com/AminRoma/AAIB_Course_DRL_2025}
}
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- This tutorial was developed for a Deep Reinforcement Learning course
- Special thanks to the students who provided feedback on earlier versions
