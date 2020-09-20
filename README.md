# DOSP Project 1
Introduction
=

The goal of the project 1 is to use ___F#___ and ___Akka Actor Model___ to build a good solution for the _Lucas Square Pyramid_ problem to find __Perfect Square__ on mutiple core.<br>

Problem Definition
=
An interesting problem in arithmetic with deep implications to elliptic curve theory is the problem of finding perfect squares that are sums of consecutive squares. A classic example is the Pythagorean identity:<br>
<center>3<sup>2</sup>+4<sup>2</sup>=5<sup>2</sup></center><br>
that reveals that the sum of squares of 3,4 is itself a square. Amore interesting example is Lucas' Square Pyramid:<br>
<center>1<sup>2</sup>+2<sup>2</sup>+...+24<sup>2</sup>=70<sup>2</sup></center><br>
In both of these examples, sums of squares of consecutive integers form the square of another integer.<br>
The goal of this first project is to use F# and the actor model to build a good solution to this problem that runs well on multi-core machines.<br>

Requirements
=

__Input:__ The input provided (as command line to your program, e.g. my app) will be two numbers: N and k. The overall goal of your program is to ﬁnd all k consecutive numbers starting at 1 and up to N, such that the sum of squares is itself a perfect square (square of an integer).<br>
__Output:__ Print, on independent lines, the ﬁrst number in the sequence for each solution.<br>
Example 1:<br>
dotnet fsi proje1.fsx 3 2<br>
3<br>
indicates that sequences of length 2 with start point between 1 and 3 contain 3,4 as a solution since 3<sup>2</sup>+4<sup>2</sup>=5<sup>2</sup><br>
Example 2:<br>
dotnet fsi proj1.fsx 40 24<br>
1<br>
indicates that sequences of length 24 with start point between 1 and 40 contain 1,2,...,24 as a solution since 1<sup>2</sup>+2<sup>2</sup>+...+24<sup>2</sup>=70<sup>2</sup><br>
