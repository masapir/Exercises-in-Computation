# Exercises-in-Computation

This is a draft collection of home school discussion and study notes on computation. 

## Our Study Theme

In addition to thinking about computation, Julia, and programming, we are interested in exploring the use of computation to gain further insight into math and physics concepts.

## Julia Set Up

We work with Julia directly in IJulia notebooks.

### Installation

Instructions at https://github.com/stevengj/julia-mit (last checked 17 May 2015).

	* Install IPython via Anaconda package
	* Download Julia from julialang.org/downloads
	* In Julia
		julia> Pkg.add("IJulia")
		julia> Pkg.add("PyPlot")

### Running IJulia

	* Command line: move to the directory where you want to create your Julia files
	* Command line: execute ipython notebook --profile julia

### Keeping Julia Current

	* In Julia (or IJulia): julia> Pkg.update() 

### References

The first part of our study references concepts and exercises discussed in Abelson & Sussman, *Structure & Intepretation of Computer Programs* (2d ed.) (SICP). 

Our notes are adapted into the Julia programming language. http://julia.readthedocs.org/en/latest/


