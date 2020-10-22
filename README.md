# NEAT Flappy Bird

This project is based on NeuroEvolution of Augmenting Topologies (NEAT), which outperforms the best fixed-topology method on a challenging benchmark reinforcement learning task.Neuroevolution (NE), the artificial evolution of neural networks using genetic algorithms, has shown great promise in complex reinforcement learning tasks.NE is a promising approach to solving reinforcement learning problems for several reasons.
Past studies have shown NE to be faster and more efficient than reinforcement learning methods such as Adaptive Heuristic Critic and Q-Learning on single pole balancing and robot arm control.Because NE searches for a behavior instead of a value function, it is effective in problems with
continuous and high-dimensional state spaces.

NeuroEvolution of Augmenting Topologies (NEAT) paper link : 

http://nn.cs.utexas.edu/downloads/papers/stanley.ec02.pdf

I have implemented the NE in a game of Flappy Bird where each generation has a population of 10 birds. The bias is changed slightly based on the highest performing bird. The performance criteria is the distance which a bird travelled in its lifetime. Each new generation in based on the strongest bird of the last generation with some minute changes. These changes countinue till the game is able to play itself to a score of 100.

In this game, the AI has only a single input i.e when to jump. This jump decision is to be made on the criteria of the distance between the birds and the pipes.The red lines show the data available to the bird on which it has to make a decision about the jump.

### Application Flow
In the image we can see the number of alive generations, and the red line on which they will make the decision.
![Optional Text](../master/projImages/pygame.png)

### Tech Stack
Python

### Python Modules
pygame

neat

visualize
