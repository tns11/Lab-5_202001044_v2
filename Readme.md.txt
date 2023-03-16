# Lab 5 - Static Analysis


Name: Soni Tarang Nileshkumar

Student ID: 202001044

Course: IT314 - Software Engineering

Lab: 5 

Title: Static Analysis

---------------------------------------------------------------------------------------------





Selected Tool: Prospector

Reason → Brings together the functionality of other STatic analysis tool and is usable out of the box.


<h1>Errors in file: </h1>

Source: https://prospector.landscape.io/en/master/


import numpy as np
-> from tkinter import *
from PIL import Image


ITERATIVE = 0
A_STAR = 1


 Error displayed: Wildcard import tkinter
-> This error is a valid error. The developer imported the whole library rather than just the required modules, which would unnecessarily increase the time of execution and size of project.




References:
  1.https://www.geeksforgeeks.org/pylint-module-in-python/

<img src = "Line50_Error.jpg> 
The error is a valid one. The if block contains a complex code (as it is having many if-elseif branches starting from line 65.
Due to it, bugs may creep in the future. But the high complexity of the code is due to the complex nature of the algorithm of solution to the problem.
(We are testing for all possible neighours, etc.0). Unless the algorithm is optimised, we have to use the branching. Hence, considering the problem and its algorithm, it really is not a error.
