# Factor-Generation-by-Evolving-Neural-Network

This project is to show a typical progress to perform factor combination by Evolving Neural Network. 
1. For each set of factors, initialize a NN, deciding it's specific initial nodes numbers according to number of original factors，number of hidden nodes to add into the generations. 
2. Select the best NN on each generation according to the fitness score calculated by calculating Rank ic on a rolling window. 
3. Move on with the winners on each generation, decide the number of generations to comb the factors. 
4. Use the output of the final evolved NN. 
