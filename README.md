# potential-benchmarks

Several classic and ML potentials were tested, and depending on their performance, the potentials are split in 3 groups:

The 1st group consists of the MEAM and Tersoff potentials, which show almost the same performance.  
The 2nd group consists of the modified Tersoff, the ReaxFF and the COMB3 potentials, which are ~x8 slower than the potentials of the 1st group. 
The 3rd group comprises the ML potentials (SNAP, NN model + SNAP descriptors, NN model + SO3 descriptors), which are ~x30-80 slower than the potentials 1st group and x4-12 times slower than the potentials of the 2nd group.
