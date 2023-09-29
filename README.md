### Page for ICLR24 submission 5877

In applying Reinforcement Learning (RL) to robot trajectory generation, two key challenges commonly emerge. First, the stochastic exploration strategies of step-based RL are unable to produce high-order smooth trajectories. Second, existing methods struggle with effectively modeling movement correlations among different time steps and degrees of freedom, which are crucial for complex tasks and safety measures. Existing solutions, typically employing parameterized trajectory generators like Movement Primitives (MP), frame the problem as contextual optimization. While effective in generating smooth trajectories and capturing some movement correlations, these methods lack in utilizing temporal structure within trajectories, resulting in suboptimal sample efficiency. We introduce the Trajectory-Centric Exploration (TCE) method to address these shortcomings. TCE enhances exploration efficiency by sampling multi-second trajectories in a parameterized space, thereby assuring high-order trajectory smoothness and the capture of movement correlations. For policy updates, TCE breaks down the entire trajectory into smaller segments, evaluating each segment on its distinct advantages. This nuanced approach allows us to utilize temporal information obtained during trajectory execution.
We validate the effectiveness of TCE through experiments on various robotic manipulation tasks, showing its advantages over both step-based RL and existing trajectory-centric approaches.

