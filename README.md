# stppRstudioServerLinux: Space-Time Point Pattern Simulation, Visualisation and Analysis

Many of the models encountered in applications of point process methods to the study of spatio-temporal phenomena are covered in 'stppRstudioServerLinux'. This package provides statistical tools for analyzing the global and local second-order properties of spatio-temporal point processes, including estimators of the space-time inhomogeneous K-function and pair correlation function. It also includes tools to get static and dynamic display of spatio-temporal point patterns.

## This is the development version

This version does not include some functions for the visualization and animation of the spatio-temporal point patterns, as well as the libraries 'rpanel', 'rgl' and their dependencies. 

**Installation guide**

The easiest way to install the development version of `stppRstudioServerLinux` from GitHub is using the `devtools` package which can be installed run the next command:
```
install.packages('remotes')
```
and thereafter run the commands:
```
require(remotes)
install_github('frajaroco/stppRstudioServerLinux')
```

## References

- [Gabriel E., Rowlingson B., Diggle P. (2013). stpp: an R package for plotting, simulating and analyzing Spatio-Temporal Point Patterns. *Journal of Statistical Software*, **53**(2), 1-29.](https://www.jstatsoft.org/article/view/v053i02/v53i02.pdf)

## CiteBibtex

A BibTeX entry for LaTeX users is

```
@misc{gdrrc00,
	author = {Edith Gabriel and Peter J. Diggle and Barry Rowlingson and Francisco J. Rodr\'iguez-Cort\'es},
	title = {stpp: Space-Time Point Pattern Simulation, Visualisation and Analysis},
	year = {2020},
	note = {R package version 2.0-4},
	url = {https://cran.r-project.org/web/packages/stpp}}
```
### Autors:

[Edith Gabriel, Avignon University, Avignon, France](http://edith.gabriel.pagesperso-orange.fr/Edith.html)

[Peter J. Diggle, Lancaster University, Lancaster, UK](https://www.lancaster.ac.uk/staff/diggle)

[Barry Rowlingson, Lancaster University, Lancaster, UK](http://barry.rowlingson.com)

[Francisco J. Rodríguez-Cortés, National University of Colombia, Medellín, Colombia](https://fjrodriguezcortes.wordpress.com)
