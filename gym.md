# Importing and using an environment
* Importing an environment:
```python
import gym
env = gym.make('CartPole-v0')
```
* Updating the environment
```python
observation, reward, done, info = env.step(action)
```
