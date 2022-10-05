---
title: Home
---

<h1> <span STYLE="font-size:25.0pt">G</span>ames <span STYLE="font-size:25.0pt">O</span>ptimization <span STYLE="font-size:25.0pt">A</span>lgorithms <span STYLE="font-size:25.0pt">L</span>earning </h1>

The Games, Optimization, Algorithms, and Learning Lab (GoalLab) studies theory of machine learning  and its interface with learning in games and algorithmic game theory, optimization, dynamical systems, probability and statistics.

# Research Highlights
{% capture text %}
Our recent focus has been on finding Nash equilibria in Markov games. Two representative papers include computing Nash Equilibria in [Adversarial Team Markov Games.](https://arxiv.org/abs/2208.02204) and [in Markov Potential Games.](https://arxiv.org/abs/2106.01969) Other works include analysis of [natural policy gradient in multi-agent settings](https://arxiv.org/abs/2110.10614).<br/>
{:.center}
{% endcapture %}
{%
  include feature.html
  image="images/papers/advteamgames.png"
  title="Multi-agent Reinforcement Learning"
  text= text
%}

{% capture text %}
The PI and the group is actively working on learning in games. Papers include results on last iterate convergence using optimism in [zero-sum games](https://arxiv.org/abs/1807.04252) and [beyond](https://arxiv.org/abs/2203.12056) (like potential games). Other works include proving [cycling](https://arxiv.org/abs/1710.11249) or even [chaotic behavior](https://arxiv.org/abs/1703.01138) of the learning dynamics, the analysis of [average performance](https://arxiv.org/abs/1403.3885) of learning in games and stability analysis in [evolutionary dynamics](https://arxiv.org/abs/1408.6270). 
{:.center}
{% endcapture %}
{%
  include feature.html
  image="images/lastiterate.png"
  title="Learning in Games"
  flip=true
  text=text
%}

{% capture text %}
Inspired by the success of Stochastic Gradient Descent in training neural networks, the group has focused on non-convex optimization. Using techniques from dynamical systems, we are able to show that Gradient Descent and other first order methods [avoid strict saddle points](https://arxiv.org/abs/1710.07406).
{:.center}
{% endcapture %}
{%
  include feature.html
  image="images/photo.jpg"
  title="Non-convex and min-max optimization"
  flip=true
  text=text
%}

{% capture text %}
Our group has focused on the problem of expressivity of Neural Networks. Using techniques from Dynamical systems, we are able to prove [tradeoffs between the depth and the width in feedforward Neural Networks](https://arxiv.org/abs/1912.04378). Here is also a [follow-up paper](https://arxiv.org/abs/2003.00777) that strenghtens the results.
{:.center}
{% endcapture %}
{%
  include feature.html
  image="images/photo.jpg"
  title="Deep Learning Theory"
  flip=true
  text=text
%}

{% capture text %}
Our team includes 3 PhD students, multiple undergrads and external collaborators.
{%
  include link.html
  link="team"
  text="Meet our team"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}
{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
