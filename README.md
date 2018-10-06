# ncaa
The source code compiled in C is exceed 25M, so, for simplisity, we upload a gui program for reader to reproduce the results in our manuscript, it is easily to use. The only thing you deed do is to download the sinanet and pubmed data set and place it in data file. Then you can run the code, and input the data file name, load the parameters in config file, run the ncaa in menu "method", and plot the result in menu "metric", enjoy.
note:The information about our manuscript will be upload once it is accepted, this work is supported by our project Grant No.61762047.
The source code has been used to apply for patent, so the complete file will be upload later.
This is the core code which described in our manuscript, you can check its performance according to our manuscript. It is developed using C\python\matlab, all .dll files are compiled under windows 10.
If you have any problems, please contact us as soon as possible. You can email to: dingcaiying@tyut.edu.cn.

# data files
The pubmed data is not upload completedly due to the 25M limit, you need to find it and cite these papers:
pubmed: Namata, G. M., London, B., Getoor, L. & Huang, B. Query-driven active surveying for collective classification. In
Workshop on Mining and Learning with Graphs (2012). URL https://linqs.soe.ucsc.edu/node/53.
sinanet:Jia, C., Li, Y., Carson, M. B., Wang, X. & Yu, J. Node attribute-enhanced community detection in complex networks. Sci.
Reports 7 (2017). URL https://doi.org/10.1038/s41598-017-02751-8.

# require for code run
You need run our code in right machine and right matlab version, which are described following:

MATLAB Compiler

1. Prerequisites for Deployment 

. Verify the MATLAB Runtime is installed and ensure you    
  have installed version 9.2 (R2017a).   

. If the MATLAB Runtime is not installed, do the following:
  (1) enter
  
      >>mcrinstaller
      
      at MATLAB prompt. The MCRINSTALLER command displays the 
      location of the MATLAB Runtime installer.

  (2) run the MATLAB Runtime installer.

Or download the Windows 64-bit version of the MATLAB Runtime for R2017a 
from the MathWorks Web site by navigating to

   http://www.mathworks.com/products/compiler/mcr/index.html
   
   
For more information about the MATLAB Runtime and the MATLAB Runtime installer, see 
Package and Distribute in the MATLAB Compiler documentation  
in the MathWorks Documentation Center.    


NOTE: You will need administrator rights to run MCRInstaller. 


2. Files to Deploy and Package

Files to package for Standalone 
================================
-ncaa_main.exe
-MCRInstaller.exe 
   -if end users are unable to download the MATLAB Runtime using the above  
    link, include it when building your component by clicking 
    the "Runtime downloaded from web" link in the Deployment Tool
-This readme file 

3. Definitions

For information on deployment terminology, go to 
http://www.mathworks.com/help. Select MATLAB Compiler >   
Getting Started > About Application Deployment > 
Deployment Product Terms in the MathWorks Documentation 
Center.
