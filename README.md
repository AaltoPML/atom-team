# Artificial agents with Theory Of Mind

AI has recently shown impressive advances, from learning to play the Atari
games to defeating expert human players in the game of Go. Beyond games, AI has
also exploded in fields such as computer vision and natural language
processing, where vast amounts of labeled data are available. More broadly
speaking, technology as a whole has massively changed the landscape of most
fields. However, current approaches can only help in tasks where we either can
precisely specify the objective or already have plenty of observations of
solutions to learn from.

Unfortunately, important real-world problems rarely have well-specified objectives or
solutions to learn from. Instead, most problems depend on the goals and
preferences of humans - the users - who are solving them. As a result, we need
approaches that explicitly consider the user. We, the [Artificial agents with
Theory Of Mind team of FCAI](https://fcai.fi/fcai-teams#atom), do exactly that
by developing techniques and methods that assist users in their tasks.

![AI-assistance diagram](figures/ai-collaboration.png)

For this we have developed a
[tutorial](https://github.com/AaltoPML/ai_assistance_tutorial) where you can
see and play around with a concrete application of AI-assistance. Below you
find a sample of our work.

## AI assistants for designers

This paper presents the general AI-assisted Design framework. Based on the
recent rise in the use of AI in design practice, and on gaps that remain in
current assistance systems for design, it argues for a new assistance paradigm:
AI-assisted Design. We focus particularly on the experience of the designer,
explaining why designer autonomy, as well as control over the AI assistant, is
important for ownership and effectiveness. We explain the general outlines of
the AI-assisted design framework and go in depth on some of the more novel
aspect, including the need for user modelling and how one can ensure designer
control.

![Diagram for AI assisted design](figures/AI_assisted_design_slide_diagram.png)

De Peuter, S., Oulasvirta, A., & Kaski, S. (2023). Toward AI assistants that let designers design. AI Magazine, 44(1), 85-96.

## Differential user models

Probabilistic user modeling is essential for building machine learning systems
in the ubiquitous cases with humans in the loop. However, modern advanced user
models, often designed as cognitive behavior simulators, are incompatible with
modern machine learning pipelines and computationally prohibitive for most
practical applications. In this work, we address this problem by introducing
widely-applicable end-to-end differentiable surrogates for bypassing this
computational bottleneck; the surrogates enable inference with modern cognitive
models in modern machine learning with online computational cost.

![Diagram for learning differentiable surrogates](figures/differential-user-models.png)

Alex Hämäläinen, Mustafa Mert Çelikok, and Samuel Kaski. Differentiable user models. The 39th Conference on Uncertainty in Artificial Intelligence, 2023.

## Zero-shot assistance

This paper presents a general-purpose instance of the AI-assisted design
framework. We formulate an instance in which an assistant helps an agent (f.ex.
a human) solve a decision problem through advice. We focus particularly on the
negative effect of biases within the agent on the effectiveness of advice, and
show that modelling biases can help mitigate these effects. Finally, we
introduce an MCTS-based planning algorithm for finding the assistant’s optimal
advice policy.

![Diagram for zero-shot assistance](figures/ai-assisted-design-diagram-technical.png)

De Peuter, S., & Kaski, S. (2022). Zero-Shot Assistance in Sequential Decision Problems.

## Cooperative optimization

The paper describes a cooperative Bayesian Optimization problem where two
agents work together to optimize black-box functions of two variables. This
approach is motivated by collaboration between humans and AI, where an
AI-assistant helps a human user solve a problem through collaborative
optimization. The solution involves strategic planning of queries using Bayes
Adaptive Monte Carlo planning and a user model that accounts for conservative
belief updates and exploratory sampling of points to query. The paper presents
a promising approach to cooperative optimization that has practical
applications in human-AI teamwork.

![Diagram for zero-shot assistance](figures/coop-bayes-opt.png)

Ali Khoshvishkaie, Petrus Mikkola, Pierre-Alexandre Murena, Samuel Kaski.
Cooperative Bayesian optimization for imperfect agents. ECML-PKDD 2023

