# RL Course - Aprendizado por Reforço

Este repositório contém notebooks e códigos para estudo e implementação de algoritmos clássicos de Aprendizado por Reforço (Reinforcement Learning, RL), utilizando principalmente a biblioteca [Gymnasium](https://gymnasium.farama.org/) e PyTorch. O foco é didático, cobrindo desde métodos Monte Carlo até Deep Q-Networks (DQN).

## Conteúdo

- **1-monte-carlo-evaluation.ipynb**  
  Avaliação de políticas usando o método Monte Carlo em ambientes discretos (FrozenLake).

- **2-monte-carlo-with-stats.ipynb**  
  Monte Carlo com estatísticas de convergência e análise de desempenho.

- **3-monte-carlo-full.ipynb**  
  Iteração geral de políticas (GPI) com avaliação e melhoria de política via Monte Carlo.

- **4-TD.ipynb**  
  Métodos de Diferença Temporal (TD), incluindo TD(0), com e sem ambiente escorregadio.

- **5-Qlearning-TD.ipynb**  
  Implementação do Q-Learning (TD Control) no ambiente FrozenLake.

- **6-QLearning-Lunar-Lander.ipynb**  
  Desafio de implementar Q-Learning para o ambiente LunarLander, discutindo as dificuldades de ambientes com espaço de estados contínuo.

- **6-QLearning-Lunar-Lander-Solution.ipynb**  
  Solução para o Q-Learning no LunarLander, incluindo discretização do espaço de estados.

- **7-DQN.ipynb**  
  Implementação de Deep Q-Network (DQN) para o ambiente CartPole, baseada no tutorial oficial do PyTorch.

## Requisitos

- Python 3.8+
- [Gymnasium](https://gymnasium.farama.org/)
- [PyTorch](https://pytorch.org/)
- numpy, matplotlib

Instale as dependências com:

```bash
pip install gymnasium[box2d] torch matplotlib numpy
