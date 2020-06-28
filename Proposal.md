**Bio**: Luiz is a microbiologist (BSc) with a PhD in Statistical Phylogenetics, interested in all of Biostatistics.
Lecturer at the School of Applied Mathematics, Getúlio Vargas Foundation (FGV), Rio de Janeiro, Brazil.

**Proposal**: "Efficient brute-force marginalisation of discrete variables in an epidemic model of sub-critical transmission".

When the basic reproduction number of a disease is below 1, stochastic fluctuations can lead to stuttering chains of transmission, characterised by sporadic flare-ups ([Blumberg & Lloyd-Smith, 2013](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002993)).
Stochastic generative models have been designed for these sub-critical transmission dynamics that are parametrised in terms of the basic reproduction number and a heterogeneity parameter, which accounts for asymmetry in the cluster sizes. 
In many situations, such as imperfect contact-tracing, clusters of disease cases are not observed completely and correct estimation of model parameters thus requires that we accommodate observation error through latent discrete variables.
Under a binomial model of observation error, the marginalisation problem for this model does not yield closed-form expressions, necessitating brute-force marginalisation if one wishes to fit the model in Stan.
In this talk I will discuss how to implement a dynamic truncation strategy to marginalise over the discrete latent components whilst controlling truncation error.
This strategy is applicable to a number of other marginalisation problems that might be encountered in practice and I shall include a discussion of the necessary regularity conditions.
I will also present other Stan-community favourites such as prior and posterior predictive checks, and how they allow us to calibrate our beliefs about the (unobserved) true number of clusters.
In the end I will show applications to both simulated and real data.

Joint work with [Andrew Rambaut](http://tree.bio.ed.ac.uk/people/arambaut/), [Gytis Dudas](evogytis.github.io), [Tanja Stadler](https://bsse.ethz.ch/department/people/detail-person.MTYwMzA5.TGlzdC8yNjY5LDEwNjI4NTM0MDk=.html) and [Trevor Bedford](https://bedford.io/team/trevor-bedford/).

Keywords: discrete latent variables; epidemiology; marginalisation.
