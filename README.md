# RL-Cartpole-v0

This is my first guided project of RL. Used Cartpole environment from Open AI gym. As agent I have used DQNAgent, policy is BoltzmannQPolicy, memory is SequentialMemory. The model is succesfully trained. The only bug I am facing is that the visualisation is not working.

    _ = dqn.test(env, nb_episodes=15, visualize=True)
    
The most probable problem might be the pip installation of gym or keras-rl2.
