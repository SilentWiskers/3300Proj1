# Introduction

This code is a part of Empirical Roofline Tool of Berkley Lab. The main code can be found here:- https://bitbucket.org/berkeleylab/cs-roofline-toolkit/src/master/Empirical_Roofline_Tool-1.1.0/.

The Emperical Roofline Tool, automatically generates a roofline data for a given computer. This includes the maximum bandwidth for the various levels of the memory hierarchy and the maximum gflop rate. This data is obtained using a variety of "micro-kernels". 

The ERT comes with a set of configuration files for a number of computers/architectures. These configuration file can be adapted to your
local environment and needs to better measure the roofline parameters of your computer(s).

To find out more about using this tool please read the user's manual, "ERT_Users_Manual.pdf".

Each of the subdirectories also contains README files with information about the purpose and contents of the subdirectory.
