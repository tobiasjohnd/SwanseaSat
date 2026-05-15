# SwanseaSat
An improved version of the sat solver I wrote for my end of year project at Swansea University.

## CLI
- `swanseaSat path/to/cnf/file.cnf` solve a sat problem encoded in a cnf file
- `swanseaSat --benchmark path/to/folder/with/cnfs/` solve all cnf in a given directory and save the results to a txt file

## Features
- works with standard DIMACS CNF format
- makes use of avariable occurance table to speet up unit propagation and pure literal elimination.
- variable occurance based huristic for variable selection.

## Changes from the original version
- implemented a variable occurance table greatly improving the eficiency of the solver.
- generally improved code quality.
- migrated the project to CMAKE from a visual studio solution
- improved the testing (although its still not as thorough as id like)
- fixed some bugs that i found when i improved the testing.

## future improvements
these are some further improvements id like to try make to the solver in the future when i find a spare weekend or two.
- more complete CLI interface.
- more eficient memory management.
- a range of variable selection huristics.
- clause learning.
- back jumping.
