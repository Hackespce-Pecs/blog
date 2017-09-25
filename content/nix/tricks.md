# Nix Tricks #

## Dependencies ##

* Read **Nix rationale** to know why nix usefull
* Read **Nix offical documentation**, because basics won't be covered

## Package Managment ##

### Declarative over Procedural ###

One of Nix main powers is reproducibility, which can be heavily undermined with porcedurral package managment, i.e installing packages via commandline. That case the present state of your system is mirrored in your shell history, which is unreallyable, noisy and almost impossible to perfectly reproduce.
So you should use nix expression to define your intalled packages, which is by design reproductable, easy to read and can be version controlled.

#### User Level Package Managment ####
*Problem:* Unlike the system level configuration the user level nix environment definition is not so straightforward, and can be achived in multiple way.

### Nox tool for nix-env ###
with nox it is much easier and faster to search packages than with nix-env.
