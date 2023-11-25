# Cellular Automata 

A cellular automaton is a mathematical and computational model used to simulate dynamic systems. It is composed of a grid of cells, each of which can be in a particular state. These cells evolve over time according to predefined rules that specify how the state of one cell relates to the state of its neighboring cells.

Each cell in a cellular automaton can have a finite set of possible states, and the evolution of the system occurs in discrete steps. The rule governing the transition from one state to another is applied simultaneously to all cells at each time step. This iterative process results in patterns of change in the system over time.

Cellular automata are used in various fields, such as simulation of natural phenomena, modeling of biological systems, complexity theory, and in general, as tools to study the dynamics of complex systems. A famous example of a cellular automaton is John Conway's "Game of Life", which has been widely studied and used to explore concepts of computational theory and emergence.

## Code

Each particle has 3 attributes:

- Color
- Position 
- Velocity 

Particles are only affected by other particles that are one unit distance away. The distance is calculated by taking the lenght of the distance vector.
$$r_{i,j} = x_j - x_i$$
$$r_{i,j} = 