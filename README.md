# Julia Function Bug
This repository demonstrates a subtle bug in a Julia function that involves unexpected behavior when handling negative input values. The function `my_function` aims to return the square of a positive number, and simply return the number if it's negative. However, due to a missing explicit `return` statement in the `else` condition, the function behaves unexpectedly. This example highlights the importance of explicit `return` statements in Julia functions for avoiding unexpected behavior and enhancing code clarity and predictability.