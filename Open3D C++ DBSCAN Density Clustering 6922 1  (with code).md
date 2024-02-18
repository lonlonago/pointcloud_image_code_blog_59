##  First, the principle of the algorithm 

###  1. Density clustering 

![avatar]( 9d0d9199ca1a46549cec053ca6eb16dc.png) 

     This is the saved result.  

  Density clustering is defined as the largest set of densely connected points, which can divide regions with high enough density into clusters, and can find clusters of arbitrary shapes in noisy spatial databases. DBSCAN is a typical density clustering algorithm. It uses two parameters to describe the tightness of the sample. One is the neighborhood radius, which is used to describe the neighborhood distance threshold of the current point. The other is the number of points, which is used to describe the minimum number of data points within the neighborhood range. From the principle, several basic concepts need to be understood: 

The algorithm flow is as follows: 

![avatar]( 5261cb3b0c4043e8bfc12af1b17c565d.png) 

![avatar]( b70fe060a0a943f39c52f594bf0d485f.png) 

    As shown in the figure below, when the neighborhood radius eps = 4 and min_points = 3, the red point is the core point, the blue point is the boundary point, and the black point is the noise point. 

###  2. References 

>  [1] Ester and H.-P. Kriegel and J Sander and X. Xu, A density-based algorithm for discovering clusters in large spatial databases with noise, KDD, 1996. 

###  3. Main functions 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574553385
 ```  
Note: This algorithm precomputes all neighbors within the radius of all points. If the number of neighborhood points selected is too large, a large amount of memory may be required. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574553385
 ```  
##  III. Display of results 

![avatar]( da4c812676f54d418ae7d89d82344ea1.png) 

