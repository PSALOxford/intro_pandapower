## Introduction to Power Network Analysis with Pandapower
##### Xiangyue Wang, Thomas Morstyn

**Pandapower** is a popular open-sourced python package for power system modeling and optimization. Its name originates from the data analysis library, **pandas**, and the power flow solver library, **PYPOWER**. Pandapower combines the data structure of the former with solvers from the latter to:

- conduct static analysis of **three-phase distribution systems**, which are commonly found in Europe
- solve **AC and DC optimal power flow** problems
- conduct state estimation, static short-circuit simulation, and topological search.



As of Feburary, 2025, Pandapower **cannot** analyse distribution grids with unsymmetrical power lines design, such as the feeder design common in North America. It also cannot solved unbalanced power flow problems and conduct dynamic short-circuit simulation.

In this notebook, we will walk you through how to use pandapower for power flow optimization.
