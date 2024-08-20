# Biophysically-realistic-balanced-state-model-of-the-barrel-cortex


Alizadeh A, Englitz B, Zeldenrust F (2023) Biophysically realistic balanced state model of the barrel cortex. Bernstein Conference 2023. doi: 10.12751/nncn.bc2023.358

network_sim.py  
                      -- runs the simulation for the model  
                      -- requires parameters_sim.py script for loading neuron numbers and connection probabilities  

parameters_sim.py  
                      -- asks user input for network configuration (r) and corresponding excitatory (e) and inhibitory (i) neuron numbers in layer 2/3 (L2/3) and layer 4 (L4) of the barrel cortex
*	r is ratio of excitatory to inhibitory neurons

*	r = 0 (7.35 - L4 and 5.25 - L2/3)  
L4   : n_e_4 = 1374 ; n_i_4 = 187   # layer 4 excitatory neuron; layer 4 inhibitory neuron
L2/3 : n_e_23 = 2232 ; n_i_23 = 425     # layer 2/3 excitatory neuron; layer 2/3 inhibitory neuron

*	r = 3  
L4   : n_e_4 = 1374 ; n_i_4 = 458  
L2/3 : n_e_23 = 2232 ; n_i_23 = 744  

*	r = 4  
L4   : n_e_4 = 1374 ; n_i_4 = 343  
L2/3 : n_e_23 = 2232 ; n_i_23 = 558  
                           
*	r = 5  
L4   : n_e_4 = 1374 ; n_i_4 = 274  
L2/3 : n_e_23 = 2232 ; n_i_23 = 446
