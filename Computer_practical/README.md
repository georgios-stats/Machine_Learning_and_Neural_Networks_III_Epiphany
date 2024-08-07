<!-- -------------------------------------------------------------------------------- -->

<!-- Copyright 2025 Georgios Karagiannis -->

<!-- georgios.karagiannis@durham.ac.uk -->
<!-- Associate Professor -->
<!-- Department of Mathematical Sciences, Durham University, Durham,  UK  -->

<!-- This file is part of Machine_Learning_and_Neural_Networks_III_Epiphany -->
<!-- which is the material of the course -->
<!-- MATH3431 Machine Learning and Neural Networks III -->
<!-- Epiphany term -->
<!-- taught by Georgios P. Katagiannis in the Department of Mathematical Sciences   -->
<!-- in the University of Durham  in Epiphany term in 2025 -->

<!-- Machine_Learning_and_Neural_Networks_III_Epiphany is free software: -->
<!-- you can redistribute it and/or modify it-->
<!-- under the terms of the GNU General Public License as published by -->
<!-- the Free Software Foundation version 3 of the License. -->

<!-- Machine_Learning_and_Neural_Networks_III_Epiphany is distributed ->
<!-- in the hope that it will be useful, -->
<!-- but WITHOUT ANY WARRANTY; without even the implied warranty of -->
<!-- MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the -->
<!-- GNU General Public License for more details. -->

<!-- You should have received a copy of the GNU General Public License -->
<!-- along with Machine_Learning_and_Neural_Networks_III_Epiphany -->
<!-- If not, see <http://www.gnu.org/licenses/>. -->

<!-- -------------------------------------------------------------------------------- -->



Aim
===

The aim of the computer practical handouts is for the students to be able to implement the methods introduced in the lecture int he computing environment and particularly in R programming language. 

------------------------------------------------------------------------

Preview:
========

Stochastic learning methods (Computer practical 1)  

<!--

-   Supplementary : [HTML](http://htmlpreview.github.io/?https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany/blob/main/Computer_practical/supplamentary_handout_computer_practical_1.xhtml) & [PDF](https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany/blob/main/Computer_practical/supplamentary_handout_computer_practical_1.pdf)  

-   Tasks : [Rnotebook](http://htmlpreview.github.io/?https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany/blob/main/Computer_practical/Stochastic_learning_methods_tasks.nb.html) & [Rmd](https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany/blob/main/Computer_practical/Stochastic_learning_methods_tasks.Rmd)  

-   Solutions : [Rnotebook](http://htmlpreview.github.io/?https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany/blob/main/Computer_practical/Stochastic_learning_methods_solutions.nb.html) & [Rmd](https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany/blob/main/Computer_practical/Stochastic_learning_methods_solutions.Rmd)  

-->

<!--
Stochastic learning methods SGLD (Computer practical 2)

-   Supplementary : [HTML](http://htmlpreview.github.io/?https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany/blob/main/Computer_practical/supplamentary_handout_computer_practical_2.xhtml) & [PDF](https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany/blob/main/Computer_practical/supplamentary_handout_computer_practical_2.pdf)  

-   Tasks : [Rnotebook](http://htmlpreview.github.io/?https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany/blob/main/Computer_practical/Stochastic_gradient_langevin_dynamics_tasks.nb.html) & [Rmd](https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany/blob/main/Computer_practical/Stochastic_gradient_langevin_dynamics_tasks.Rmd)  

-   Solutions : [Rnotebook](http://htmlpreview.github.io/?https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany/blob/main/Computer_practical/Stochastic_gradient_langevin_dynamics_solutions.nb.html) & [Rmd](https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany/blob/main/Computer_practical/Stochastic_gradient_langevin_dynamics_solutions.Rmd) 

-->

<!--

Support Vector Machines (Computer practical 3)

-   Tasks : [Rnotebook](http://htmlpreview.github.io/?https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany/blob/main/Computer_practical/Support_Vector_Machines_tasks.nb.html) & [Rmd](https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany/blob/main/Computer_practical/Support_Vector_Machines_tasks.Rmd)  

-   Solutions : [Rnotebook](http://htmlpreview.github.io/?https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany/blob/main/Computer_practical/Support_Vector_Machines_solutions.nb.html) & [Rmd](https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany/blob/main/Computer_practical/Support_Vector_Machines_solutions.Rmd) 

-->

<!--

Artificial Neural Networks (Computer practical 4)  

-   Tasks : [Rnotebook](http://htmlpreview.github.io/?https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany/blob/main/Computer_practical/Artificial_Neural_Networks_tasks.nb.html) & [Rmd](https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany/blob/main/Computer_practical/Artificial_Neural_Networks_tasks.Rmd)  

-   Solutions : [Rnotebook](http://htmlpreview.github.io/?https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany/blob/main/Computer_practical/Artificial_Neural_Networks_solutions.nb.html) & [Rmd](https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany/blob/main/Computer_practical/Artificial_Neural_Networks_solutions.Rmd)  

-->


------------------------------------------------------------------------


### How to download a specific file

1. You can just navigate to the file from the browser and download it.

2. You can use the GitZip add-on for Firefox available [HERE](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=3&cad=rja&uact=8&ved=2ahUKEwias52xjd3nAhXPUs0KHeXHCEUQFjACegQIAhAB&url=https%3A%2F%2Faddons.mozilla.org%2Fen-US%2Ffirefox%2Faddon%2Fgitzip%2F&usg=AOvVaw37servrJ29tuNcx9dIQDqy) or the Chrome add-on GitZip available [HERE](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=2&cad=rja&uact=8&ved=2ahUKEwias52xjd3nAhXPUs0KHeXHCEUQFjABegQIARAB&url=https%3A%2F%2Fchrome.google.com%2Fwebstore%2Fdetail%2Fgitzip-for-github%2Fffabmkklhbepgcgfonabamgnfafbdlkn%3Fhl%3Den&usg=AOvVaw1Pn3VXuXz1Fphl7dsPEhDS)


------------------------------------------------------------------------
