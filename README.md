# RL-Cartpole-v0

This is my first guided project of RL. Used Cartpole environment from Open AI gym. As agent I have used DQNAgent, policy is BoltzmannQPolicy, memory is SequentialMemory. The model is succesfully trained. 

![Screenshot 2021-03-30 110235](https://user-images.githubusercontent.com/44130583/112939197-ad885d00-9148-11eb-8e33-1f67686b8159.png)

The only bug I am facing is that the visualisation is not working.

    _ = dqn.test(env, nb_episodes=15, visualize=True)
    
The most probable problem might be the pip installation of gym or keras-rl2.
