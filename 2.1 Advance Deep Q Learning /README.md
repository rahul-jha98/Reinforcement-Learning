# Dueling Deep Q Learning with Doom (+ double DQNs and Prioritized Experience Replay).

In this scenario the agent has to pass through a corridor killing enemies on the way so as to reach the final chest. With abuot 500 epochs we can see some behaviour which are not human like. The agent sees that if it makes a quick dash in the initial moments of the game,
it can pass through the two enemies without killing them. But since it takes a toll on the health it begins trying to shoot the next set of enemies. 

Thus the agent found out that the enemies do not follow you and if you can take a hit on our health you can pass through without killing. 

![Animation.gif](./DoomCorridor.gif) 
