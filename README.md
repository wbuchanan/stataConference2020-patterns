# Stata Conference 2020

## Session 3
__Implementing programming patterns in Mata to optimize your code__

Have you ever created a program that requires a nontrivial amount of data to be present or available (for example, look-up/value tables, data used for the program interface, etc…)? If you have, you’ll likely have experienced the performance penalty that multiple I/O operations can cause.

In this talk, I’ll provide an example of how to implement a common programming pattern from the computer science field and how it can solve this performance issue more effectively. Based on a set of scripts developed by Adam Nelson (https://github.com/adamrossnelson/StataIPEDSAll), I developed a solution (https://github.com/wbuchanan/ipeds) that uses the singleton pattern to reduce object instantiation and I/O operations over multiple calls in order to improve performance.
