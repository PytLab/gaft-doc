.. currentmodule:: gaft

Introduction
=============

Welcome to the `GAFT` documentation!

`GAFT` is a general genetic algorithm framwork written in Python with MPI 
parallelization under the GPLv3 license. It's an acronym for Genetic Algorithm
Framework for Python.

You can always find the latest stable version of the program
here: https://github.com/pytlab/gaft

This documentation describes version 0.5.6


Why Genetic Algorithm?
----------------------
In contrast to those local search methods, genetic algorithms which are 
categorized as global search heuristics are a particular class of evolutionary 
algorithm (EA) that utilizes techniques inspired by evolutionary biology ideas 
such as inheritance, mutation, selection and crossover. Without calculating 
derivatives, genetic algorithms can be used in many domains to find the optimal 
solutions for complex problems such as biology, engineering, computational chemistry, 
computer science and social science. Especially in a case where the mathematical 
data is available and answers are available but the formula that joins the data 
to the answers is missing, at this time, a genetic algorithm can be used to 'evolve' 
an expression tree to create a very close fit to the data, for example, the complex 
hyper parameters optimization of a mathematical model. At the same time, genetic algorithms 
have relative fixed iteration process and large space for algorithm adjustment 
by genetic operator improvement. Therefore, genetic algorithm is one of the most 
appropriate methods to construct a general optimization framework for more 
realistic applications in different fields

Why `GAFT`?
-----------
Optimization problem that needs is a common problem researchers meet in computational 
physics and chemistry field. It is a great challenge to create a high-efficient 
program that are general and easy-to-use enough to be used directly for optimizing 
different target problems and are customizable enough to help researcher to develop 
new algorithm and run tests.

To this end, we present a Python general Genetic Algorithm framework named GAFT which
provides flexible and customizable API to help researchers in various fields to apply genetic algorithm optimization flow to their own targets.

