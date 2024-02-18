##  First, the principle of the algorithm 

###  1. Process overview 

![avatar]( b6846274de794be398562ab6adc08b04.jpeg) 

   The Douglas-Puck method can be described as follows: connect the first and last vertices of a curve to a straight line, find the distance from the remaining vertices to the straight line, choose the largest one and compare it with the specified limit, if it is less than or equal to the limit, then delete all the points between the two ends of the straight line; if it is greater than the limit, keep the vertex with the largest distance from the straight line, and divide the curve into two parts. The above method is repeated for these two parts until further compression is finally impossible (see Figure 1).  

###  2. References 

>  [1] Peng Hucan, Dong Jian, Zheng Yidong, Li Gaixiao. Comparison of the efficiency of removing redundant vertices by vertical distance method and Douglas-Puck method [J]. Bulletin of Surveying and Mapping, 2010 (03): 66-67 + 71. [2] He Kuan, Sun Rui, Guan Yunlan, Zeng Chenxi. Point cloud data reduction based on point-by-point advance method [J/OL]. Bulletin of Surveying and Mapping: 1-4 

##  Code implementation 

DouglasPeuckerVacuate.h 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574538273
 ```  
DouglasPeuckerVacuate.cpp 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574538273
 ```  
main.cpp 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574538273
 ```  
##  III. Display of results 

![avatar]( 9b8b842becc94aa5964554d351f21abb.jpeg) 

