# Prey-Predator Modeling

This project presents a mathematical model for the predator-prey relationship in an ecosystem. We use a system of coupled differential equations to describe the dynamics of the population of prey and predator. The model is analyzed using numerical methods, such as Euler's method and the Runge-Kutta method, to simulate the behavior of the system. We investigate the stability of the equilibrium points, the existence of limit cycles, and the effect of changing parameters on the behavior of the system. We also illustrate the system's behavior using phase plots and field lines. Finally, we discuss the biological significance of our findings and the limitations of the model.

## Introduction
Prey-predator modeling is a topic of great interest in ecology and biology. It provides a way to understand the complex dynamics of predator-prey interactions in natural ecosystems. These interactions are vital for maintaining ecological balance and are often affected by environmental factors. Mathematical models using ordinary differential equations (ODEs) are an essential tool for studying these interactions and predicting the long-term behavior of populations. Lotka-Volterra equations are a famous example of such models used to model the dynamics of a simple predator-prey system.

## Problem Statement
This project aims to develop a mathematical model of a prey-predator system using ODEs, incorporating realistic assumptions and parameters, exploring numerical methods, and analyzing system stability. The model will predict population dynamics and investigate ecological factors. The goal is to provide ecologists and biologists with insights and a useful tool to study and manage natural ecosystems.

## Euler's method and the Runge-Kutta method
Euler's method and the Runge-Kutta method are numerical methods used to approximate solutions of differential equations. Euler's method is a simple algorithm that uses the slope of the tangent line at a point to estimate the value of the function at the next point. The Runge-Kutta method is a more accurate and robust method that uses intermediate values calculated at the previous steps. Both Euler's method and the Runge-Kutta method are widely used for numerical simulations of differential equations.

## Lotka-Volterra equations
Lotka-Volterra equations describe the dynamics of a simple predator-prey system. They were first proposed by Alfred J. Lotka and Vito Volterra in the 1920s and are used to model the interaction between populations of predator and prey species. The equations describe how the populations of predators and prey change over time and can exhibit complex and oscillatory behavior, with the predator and prey populations fluctuating in response to each other. The equations have been used in many fields to study the dynamics of populations in predator-prey interactions and other systems of interacting species.

## Assumptions & Restrictions
The model assumes continuous growth, a constant environment, no migration, no external factors, and linear interactions between the prey and predators. These assumptions may not always hold in real-world situations and can limit the accuracy of the model.

## Main Equations
The main equations for the project are a system of two coupled ordinary differential equations, which describe the dynamics of the prey and predator populations.

dP/dt = αP – βPQ

dQ/dt = γPQ - δQ

Where P is the prey population, Q is the predator population, α is the prey growth rate, β is the predation rate, γ is the predator growth rate, and δ is the predator death rate.

## Solving the ODE
Our objective is to determine the steady state or equilibrium point of the system, where the rate of change is zero. To achieve this, we must identify the solutions of the system of equations. In this case, we obtain two solutions, the trivial and non-trivial solutions. The trivial solution corresponds to zero populations of prey and predators, which is not useful for our analysis. The non-trivial solution provides the values of both the prey and predator populations at the steady state.

## Simulation & Graphs
We used the Runge-Kutta method to simulate the behavior of the system and visualize the results using population vs. time and prey vs. predator graphs. The observed population dynamics show a cyclic pattern of alternating increases and decreases, with the predator population lagging behind the prey population due to the low predator growth rate.

## Conclusion
This project has provided a comprehensive understanding of the predator-prey relationship in an ecosystem using a mathematical model. Although the model has limitations, this project has helped us to understand the basic principles of predator-prey modeling and the numerical methods used for simulation. Further research can be done to incorporate more realistic and complex biological factors to improve the accuracy of the model.

## Contact
If you have any questions, suggestions, or concerns regarding this project, please feel free to contact us:

Adham Saad: s-adham.saad@zewailcity.edu.eg

Mohamed Morshedy: s-mohamed.morshedy@zewailcity.edu.eg

Omar Awad: s-omar.awad@zewailcity.edu.eg

Mahmoud Elshahed: s-mahmoud.elshahed@zewailcity.edu.eg

Thank you for your interest and support!
