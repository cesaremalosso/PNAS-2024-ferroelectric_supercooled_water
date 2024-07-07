# PNAS-2024-ferroelectric_supercooled_water
Data of paper: "Evidence of ferroelectric features in the low-density phase of undercooled water" by Malosso et al.

This repository contains the neural network model and the raw dataset used for the training.

Brief summary of the contents:
* ```dipole_model.pb``` :  Neural-network model built with DeepMD-kit v2.2.3 and trained to predict the molecular dipole of water molecule at liquid and supercooled conditions. Type 0 must refers to oxygen atoms and type 1 to hydrogen atoms.
* ```dataset``` : This folder contains all the frames used to trained the dipole model.
  
  * ```HDL``` : frames taken from water simulations at supercooled condition in the high-density phase. 
  * ```LDL``` : frames taken from water simulations at supercooled condition in the low-density phase. 
  * ```liquid```: frames taken from water simulations at supercooled conditions at different temperatures and densities.
