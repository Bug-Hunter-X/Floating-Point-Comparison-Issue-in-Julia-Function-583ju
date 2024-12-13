# Floating-Point Comparison Issue in Julia

This repository demonstrates a potential issue in Julia code related to floating-point number comparisons. The function `myfunction` aims to return the square of a number, making it negative for negative inputs. However, a direct comparison with zero (`x == 0`) can lead to unexpected results due to the inherent imprecision of floating-point representations.

The `bug.jl` file contains the problematic code, while `bugSolution.jl` provides a corrected version that addresses the floating-point comparison issue using a tolerance threshold.