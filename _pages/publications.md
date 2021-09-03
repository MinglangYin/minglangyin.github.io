---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Journals

<!-- 12. M. Yin, R. Aaron, G.E. Karniadakis, "Non-invasive inference of arterial stiffness for osteoarthritis patients" under written (2021).

11. M. Yin, E. Zhang, Y. Yu, G.E. Karniadakis, "On the coupling of a macroscale method with Deep Operator Network" -->

1. M. Yin, E. Ban, E. Zhang, B. Rego, C. Cavinato, J.D. Humphrey, G.E. Karniadakis, "Simulating progressive intramural damage leading to aortic dissection using an operator-regression neural network", arXiv:2108.11985 (2021).

9. S. Goswami, M. Yin, Y. Yu, G.E. Karniadakis, "A physics-informed variational DeepONet for predicting the crack path in brittle materials", arXiv:2108.06905 (2021).

8. S. Cai, Z. Mao, Z. Wang, M. Yin, G.E. Karniadakis, "Physics-informed neural networks in fluid mechanics: A review", Acta Mechanica Sinica (2021).

7. A. Blumers*, M. Yin*, Y. Hasegawa, Z. Li, and G.E. Karniadakis. "Supervised parallel-in-time algorithm for long-time Lagrangian simulations of stochastic dynamics: Application to blood flow in zebrafish", Computational Mechanics (2021).

6. M. Yin, X. Zheng, J.D. Humphrey, G.E. Karniadakis, "Non-invasive inference of thrombus material properties with physics-informed neural networks." Computer Methods in Applied Mechanics and Engineering 375 (2021): 113603.

5. E. Zhang, M. Yin, G.E. Karniadakis, "Physics-Informed Neural Networks for Nonhomogeneous Material Identification in Elasticity Imaging", AAAI Conference (2020).

4. M. Yin}, A. Yazdani, and G.E. Karniadakis. "One-dimensional modeling of fractional flow reserve in coronary artery disease: Uncertainty quantification and Bayesian optimization." Computer Methods in Applied Mechanics and Engineering, 353 (2019): 66-85.

3. D. Hopper, D. Jaganathan, J. Orr, J. Shi, F. Simeski, M. Yin, J.T.C. Liu, "Heat Transfer in Nanofluid Boundary Layer Near Adiabatic Wall." Journal of Nanofluids 7.6 (2018): 1297-1302.

2. M. Yin, J. Kou, W. Zhang, "A reduced-order aerodynamic model with high generalization capability based on neural network", Acta Aerodynamica Sinica 35.02 (2017): 205-213.

1. J. Kou, W. Zhang, and M. Yin, "Novel Wiener models with a time-delayed nonlinear block and their identification." Nonlinear Dynamics 85.4 (2016): 2389-2404.

