---
# Snake Game using Reinforcement Learning

###Serving for the course Artificial Intelligence - IT3160E

This mini-project delves into the application of Deep Q-learning, a powerful Deep
Reinforcement Learning (DRL) technique, to train an AI agent to master the deceptively
challenging Snake game. Our objective is to showcase the effectiveness of Deep Q-learning
in enabling an agent to learn optimal strategies through interaction with the game
environment and maximizing its reward. The project employs a custom-designed Deep Qlearning architecture within the agent, utilizing a neural network to approximate the Q-values
associated with potential actions. This empowers the agent to dynamically evaluate and
prioritize moves based on their predicted long-term value, navigating the intricate obstacles
presented by the limited action space and fleeting rewards inherent to the game. By analyzing
the agent's performance over numerous iterative interactions with the game, we witness its
impressive evolution. The interplay of exploration and exploitation within the Deep Qlearning framework drives continuous improvement, culminating in the agent achieving
exceptional performance marked by record-breaking scores. This remarkable journey not
only demonstrates the power of Deep Q-learning in tackling complex optimization
challenges but also paves the way for its broader application in diverse real-world domains
where intelligent adaptation and decision-making are crucial.

---
## Overview

This report presents a journey into the application of Deep Q-Learning (DQN) for
mastering the classic Snake game. Our methodological exploration unfolds in three key
chapters. First, we establish the theoretical foundations with an overview of Reinforcement
Learning (RL) principles, including the Markov Decision Process framework and the
Bellman Equation, which guides optimal policy discovery in Q-learning, the core algorithm
at the heart of DQN. Next, we delve into the transformative power of DQN, delving into the
intricacies of its core Q-learning mechanism and its enhanced ability to represent complex
state and action spaces through deep neural networks. We then unravel the optimization
process involved in training the DQN agent, encompassing loss functions and network
updates that shape its decision-making capabilities. Finally, we bridge the gap between
theory and practice with a detailed account of the experimental setup, encompassing the
Snake game environment, the DQN agent's architecture, and the training procedures and
evaluation metrics employed to assess its performance. The concluding chapter dissects the
results, analyzing the effectiveness of DQN in mastering the Snake domain while
acknowledging the remaining challenges, as the AI navigates increasingly complex
scenarios. Ultimately, this work paves the way for further exploration in leveraging AI
learning through games, unlocking new possibilities in the fascinating realm of RL.

---
## Requirements

The following libraries and frameworks are required for running the project:

- Python 3.10
- PyTorch
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- h5py
- tqdm
- wandb
...

To install these dependencies, you can use the provided `requirements.txt` file.

### Example:

```
pip install -r requirements.txt
```

---

## Installation

1. **Clone the repository:**

   ```
   git clone https://github.com/xt2201/it3320e-human-action-recognition-ucf101.git](https://github.com/sonho4ng/Snake-Game.git
   cd Snake-Game
   ```

2. **Install dependencies:**

   If you're using a `requirements.txt` file, run:

   ```
   pip install -r requirements.txt
   ```

   Alternatively, install required libraries individually using `pip`.


 










