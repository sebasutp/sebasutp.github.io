---
title: "Adaptation and robust learning of probabilistic movement primitives"
collection: publications
category: manuscripts
permalink: /publication/journal_1
date: 2020-03-02
venue: 'IEEE Transactions on Robotics'
paperurl: '/files/paper1.pdf'
excerpt: 'Introduces some operators for a probabilistic representation of robot trajectories.'
citation: 'S. Gomez-Gonzalez, G. Neumann, B. Schölkopf and J. Peters, "Adaptation and Robust Learning of Probabilistic Movement Primitives," in IEEE Transactions on Robotics, vol. 36, no. 2, pp. 366-379, April 2020, doi: 10.1109/TRO.2019.2937010.'
---

# Abstract

Probabilistic representations of movement primitives open important new possibilities for machine learning in
robotics. These representations are able to capture the variability
of the demonstrations from a teacher as a probability distribution
over trajectories, providing a sensible region of exploration and
the ability to adapt to changes in the robot environment. However,
to be able to capture variability and correlations between
different joints, a probabilistic movement primitive requires the
estimation of a larger number of parameters compared to their
deterministic counterparts, that focus on modeling only the mean
behavior. In this paper, we make use of prior distributions
over the parameters of a probabilistic movement primitive to
make robust estimates of the parameters with few training
instances. In addition, we introduce general purpose operators
to adapt movement primitives in joint and task space. The
proposed training method and adaptation operators are tested in
a coffee preparation and in robot table tennis task. In the coffee
preparation task we evaluate the generalization performance
to changes in the location of the coffee grinder and brewing
chamber in a target area, achieving the desired behavior after
only two demonstrations. In the table tennis task we evaluate the
hit and return rates, outperforming previous approaches while
using fewer task specific heuristics.
