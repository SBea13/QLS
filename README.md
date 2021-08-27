# QLS
Presentation and some code for the final exam of the course Quantitative Life Science by prof.S. Suweis @ UniPd
## Coexistence of many species in random ecosystem

In the "Simulations" folder, you can find two support files:
- build_function.R: it includes all the main support functions used for matrix generation, growth rate sampling
- lemke-howson.R: contains the algorithm for finding the equilibrium of the considered systems

The ``simulations_and_graphs`` notebook instead includes many graphs and simulations and some trials of analytical computations.

The reference paper *Coexistence of many species in random ecosystems*, by Carlos A. Servan, Jose A. Capitan, Jacopo Grilli, Kent E. Morrison and Stefano Allesina and the source code can be found at https://github.com/StefanoAllesina/randomzoo

The "QLS_slides" file are the slides prepared for the final presentation, that have the following abstract:

Abstract: "Ecosystems are usually characterized by an astonishing number of species, linked by complex interaction networks that define their dynamics. In such big communities, it is hardly possible for all the species to stably coexist. However, changing the point of view can help in studying coexistence: generally, natural communities are a portion of a bigger pool, pruned by population dynamics.
In this seminar, I will present the results achieved by Sérvan et al. (2018) in their paper "Coexistence of many species in random ecosystems": it is in fact possible to compute analytically the distribution of the number of species that can coexist when we start from a pool of species interacting randomly, and show that even in this case we can observe rich, stable communities. The most striking result is that, once stability conditions are met, network structure has very little influence on the level of biodiversity attained, besides, in this work the main drivers responsible for widespread coexistence in natural communities are presented, providing a baseline for determining which structural aspects of empirical communities promote or hinder coexistence. In my presentation, the main theoretical aspect will be supported by simulations of the main cases presented in the paper."
