---
layout: distill
title: Maximizing the Spread of Influence through a Social Network
#permalink: /blog/influence-spread-maximization
mathjax: true
tags: Information-Diffusion, Submodular-Functions
authors:
    - name: Ipsit Mantri
      url: "https://ipsitmantri.github.io/"
      affiliations:
        name: EE, IITB
bibliography: influence_max.bib
---
In construction
===

## Keywords
approximation algorithms, social networks, viral marketing, word-of-mouth, information diffusion, submodular functions, discrete optimization
## Overview
This paper is about approximation algorithms formulated to solve the problem of picking the right initial set of nodes (called source nodes or seeds) in a social network so that the spread of the influence is maximized over the network. This paper also proposes a general approach for reasoning about the performance guarantees of algorithms in the context of influence propogation.<d-cite key="10.1145/956750.956769"></d-cite><d-cite key="10.1145/775047.775057"></d-cite>
## Some Background
>**social network**: A graph of relationships and interactions within a group of individuals.  

Consider the following situation. We all use different social media websites and applications. Suppose a friend X (he/him/his) of yours has founded a start-up, which basically sells grooming kits for men. X wants to increase his sales by doing marketing on social media websites. He is not famous on social media and does not have an active presence. What do you think about his reach if he starts this social media marketing campaign himself by posting photos and videos? It won't be that great. You are active on social media and you have say 1 million followers. How would the reach be if you promoted your friend X's products? The reach will be much larger. In other words, the information will *spread* to a larger number of people, i.e., you helped in *maximizing the spread of influence through a social network!*   

As we see, this is a more fundamental problem and occurs in widely different scenarios like adoption of new medicines, rise of political movement, craze for a cell phone, or even a spread of pandemic! It is important to understand the dynamics of these "word-of-mouth" effects. This is a widely studied problem in social sciences. 
