# Exercises-in-Computation

Home School Discussion and Study Notes

This is a draft collection of discussion and study notes on computation. 

## Our Study Theme

In addition to thinking about computation, Julia, and programming, we are interested in exploring the use of computation to gain further insight into math and physics concepts.

To begin our study we will follow discussions in Abelson & Sussman's Structure and Interpretation of Computer Programs while learning the Julia language.


## Julia Set Up

We will work with Julia directly in IJulia notebooks.

### Installation

We followed the instructions at https://github.com/stevengj/julia-mit (last checked 17 May 2015).

	* Install IPython via Anaconda package
	* Download Julia from julialang.org/downloads
	* In Julia
		julia> Pkg.add("IJulia")
		julia> Pkg.add("PyPlot")

### Running IJulia

	* Command line: move to the directory where you want to create your Julia files
	* Command line: execute ipython notebook --profile julia

### Keeping Julia current:

	* In Julia (or IJulia): julia> Pkg.update() 

### References

The first part of our study is based on the ideas and problems discussed in Abelson & Sussman, Structure & Intepretation of Computer Programs (2d ed.) (SICP). Our notes, however, are adapted into the Julia programming language rather than Scheme. Exercise and page numbers refer to SICP. 


