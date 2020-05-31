# three samples from my recent activity

For this portfolio, I have selected the following three coding samples.

## 1. ambercalculator 

https://github.com/matbonfanti/ambercalculator

Since March 2009 I have been working in the group of Prof. M. Garavelli, University
of Bologna. In this context, I have been primarily responsible for the maintenance and development
of the Python code COBRAMM (https://site.unibo.it/cobramm), a tool that has been created
to realize spectroscopic simulations of photo-active systems in condensed phase (e.g.
molecules in solvent or pigments embedded in protein environments).

COBRAMM is a large project with a long history: my contribution 
is intertwined with the code from the people who have started and developed
the project before me. For this reason I have selected only a relatively
small excerpt, that I wrote from scratch and I think is representative
of my programming style. 

This code chunk, named *ambercalculator* is available from my GitHub repository:

    git clone https://github.com/matbonfanti/ambercalculator.git
    
 A more detailed description and instructions for installation and 
 testing are available in the README file.
 
## 2. mime

https://github.com/matbonfanti/mime

This second example is a small code named *mime* that I developed while working
in Frankfurt University in 2018. The purpose of this code is relatively
simple: fit a two-dimensional function to some input 
data to derive an analytical representation of the data.
However, in the attempt to make the code more powerful and 
reusable, I adopted a solution in which the analytic form of the 
function is easily generalizable by using SymPy, a Python library for
symbolic calculation. 

The code is available from my GitHub repository 

    git clone https://github.com/matbonfanti/mime.git

and the README file contains a more detailed description,
and instruction for installation and testing.

## 3. sarastro

https://github.com/matbonfanti/sarastro

I started working with Python around 2016, initially only for small 
analysis scripts. For most of my activity I have instead used FORTRAN 90/95, 
which has been for a long time the most popular programming language 
in the academic community of theoretical and computational chemistry. 

The code *sarastro* is the last program that I wrote in FORTRAN, at the
end of 2018. The purpose of the code is very technical: solving
the Time-Dependent Schr&ouml;dinger Equation (TDSE) with a 
methodology known as variational multiconfiguration Gaussian wavepacket (vMCG),
in which the wavefunction is described as a combination of multi-dimensional
Gaussian Wavepackets (GWPs).

Despite the very specific context of this project and despite the use of 
an "out-of-date" programming language, I think that *sarastro* is 
a good example of my programming style, for two reasons:
* I built the code organizing most tasks in an object-oriented paradigm,
  despite the fact that this is not straightforward using FORTRAN 
  structures.
* most general-purpose modules (e.g. Clock.f90, InputField.f90, MyError.f90,
  MyLinearAlgebra.f90) come from previous project, even from years before,
  because since the very beginning of my activity I attempted to create 
  a personal library of FORTRAN modules that I could reuse in all sorts of 
  projects.

Also in this last case the code is available from my GitHub repository 

    git clone https://github.com/matbonfanti/sarastro.git

and the detailed description and instructions are in the README file.
