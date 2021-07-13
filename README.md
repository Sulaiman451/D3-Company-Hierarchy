# Overview
This uses D3 and Firestore to create a tree diagram, which represents the structure of a made-up company called Toretto's (yes, that's a Fast & Furious reference). Consider this an edited version of what is in Net Ninja's D3 course on Udemy.

New data, in the form of a new employee, can be added through a form which asks for the name of said employee, who they report to, and the department they work in. 

The big boss is Jack, his three children are next in the hierarchy as supervisors, and beneath those there are other employees. Each box in the tree diagram is colour-coded to indicate who is in what department (an ordinal scale running in the background).

The idea behind this is to demonstrate working with hierarchal data, in addition to using a tree diagram in D3.