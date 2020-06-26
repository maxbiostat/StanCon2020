**Bio**: Luiz is a microbiologist (BSc) with a PhD in Statistical Phylogenetics, interested in all of Biostatistics.
Lecturer at the School of Applied Mathematics, Getúlio Vargas Foundation (FGV), Rio de Janeiro, Brazil.

**Proposal**: "Efficient brute-force marginalisation of discrete variables in an epidemic model of sub-critical transmission".

When the basic reproduction number of a disease ($R_0$) is below 1, stochastic fluctuations can lead to stuttering chains of transmission, characterised by sporadic flare-ups ([Blumberg & Lloyd-Smith, 2013](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002993)).
Moreover, clusters of disease cases are often not observed completely.
Correct estimation of model parameters thus requires that we accommodate observation error through latent discrete variables.
In this talk I will discuss how to implement a dynamic truncation strategy to marginalise over the discrete latent components whilst controlling truncation error.
This strategy is applicable to a number of other marginalisation problems that might be encountered in practice and I shall include a discussion of the necessary regularity conditions.
I will also show other Stan-community favourites such as prior predictives checks and how they allow us to calibrate our beliefs about the (unobserved) true number of clusters, $N$.
In the end I will show applications to both simulated and real data.

Joint work with [Andrew Rambaut](http://tree.bio.ed.ac.uk/people/arambaut/), [Gytis Dudas](evogytis.github.io), [Tanja Stadler](https://bsse.ethz.ch/department/people/detail-person.MTYwMzA5.TGlzdC8yNjY5LDEwNjI4NTM0MDk=.html) and [Trevor Bedford](https://bedford.io/team/trevor-bedford/).

Keywords: discrete latent variables; epidemiology; marginalisation.
