<br><br>
<p align="center">
  <img src='./assets/Metaworld.gif' width="200" />
  <img src='./assets/Box_Pushing.gif' width="200" />
  <img src='./assets/Table_Tennis.gif' width="200" />
</p>

## Abstract

In applying Reinforcement Learning (RL) to robot trajectory generation, two key challenges commonly emerge. First, the stochastic exploration strategies of step-based RL are unable to produce high-order smooth trajectories. Second, existing methods struggle with effectively modeling movement correlations among different time steps and degrees of freedom, which are crucial for complex tasks and safety measures. Episodic RL methods address these challenges by employing parameterized trajectory generators like Movement Primitives (MP), framing the problem as contextual optimization. While effective in generating smooth trajectories and capturing some movement correlations, these methods lack in utilizing temporal structure within trajectories, resulting in suboptimal sample efficiency. We introduce the Temporally-Correlated Episodic RL (TCE) method to address these shortcomings. TCE enhances exploration efficiency by sampling multi-second trajectories in a parameterized space, thereby assuring high-order trajectory smoothness and the capture of movement correlations. For policy updates, TCE breaks down the entire trajectory into smaller segments, evaluating each segment on its distinct advantages. This nuanced approach allows us to utilize temporal information obtained during trajectory execution.
We validate the effectiveness of TCE through experiments on various robotic manipulation tasks, showing its advantages over step-based and episodic RL approaches.

<br><br>
![TCE](https://github.com/TemporallyCorrelatedExploration/TemporallyCorrelatedExploration.github.io/assets/146423176/d74e470b-3954-4281-85bb-e48c16e73b73)
<!--- -->

<div align="center">
  <br><br>
    <a href='https://github.com/TemporallyCorrelatedExploration/Temporally-Correlated-Exploration'><img src='./assets/CodeOnGithub.png' width="300px"></a>
</div>
