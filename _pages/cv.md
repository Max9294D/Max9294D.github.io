---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Computer Science, Polytechnique Montreal, 2027 (expected)
* M.S. in Artificial Intelligence & Applied Mathematics, Sorbonne University, 2023
* M.S. in Artificial Intelligence, ENSTA, 2023
* Preparatory school, Prytanée National Militaire, 2019
  
Work experience
======
* Spring 2023 - Fall 2023: Research Intern
  * Polytechnique Montreal
  * Operations Research & ML : Constraint Programming Solver leveraging Reinforcement Learning (CP, RL, GNN, DP, ML).
  * Supervisor: Professor Louis-Martin Rousseau & Professor Quentin Cappart
  
* Spring 2022 - Summer 2022: Research Intern
  * VO2 Group AI Lab
  * Reinforcement Learning : Explainable AI-based Trading Algorithm (DQN, DDPG, A2C)
  * Supervisor: Dr. Etienne Gay

* Fall 2021 - Winter 2022: Operation Research Intern
  * Total Energies Digital Factory
  * Applied Mathematics : Exact Method for the Vehicle Routing Problem
  * Supervisor: Pierre de Fréminville

* Summer 2021: Research Intern
  * Ecole Polytechnique Fédérale de Lausanne
  * Deep Learning : MRI Data Processing (RNN, LSTM, Transformer).
  * Supervisor: Professor Ileana O. Jelescu
  
Skills
======
* Coding : C++, Python, Julia, Java, C, Matlab, Octave, SQL.
* Languages : French (native), English (fluent), Spanish (intermediate), Chinese (beginner).
* Hobbies : Running, Triathlon, Hiking, Handball (Captain), Travels.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Vice-President of CORS Montreal Student Chapter
* Student Member of the Polytechnique Montreal Computer Science Department 
