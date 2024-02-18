##  First, the principle of the algorithm 

###  1. Algorithm overview 

  The essence of Euclidean clustering is to classify points with similar distances into a class. Assuming that there are points in the point cloud, define the Euclidean distance as the degree of intimacy of two of the points, and use the distance between the nearby points as the standard to realize point cloud clustering segmentation. The specific process of segmentation is as follows: for the pre-processed point cloud dataset, determine a query point, set the distance threshold, and find the nearest neighbors through KD-Tree; calculate the Euclidean distance from each nearest neighbor point to the query point; compare the distance with the distance threshold, and classify the smaller points into the class until the number of points in the class no longer increases, and the segmentation is completed. For more detailed implementation principles, please refer to: PCL Euclidean clustering segmentation, Open3D point cloud Euclidean clustering (python detailed process version), pclpy point cloud Euclidean clustering segmentation, and matlab point cloud clustering segmentation based on Euclidean distance. Because the algorithm principle is quite familiar and has been written many times, it will not be repeated. 

###  2. References 

>  [1] SONG Shuya. Point cloud segmentation method based on improved European clustering [J]. Metrology and Testing Technology, 2022, 49 (05): 96-100. DOI: 10.15988/j.cnki.1004-6941. 2022.5.029. 

##  Code implementation 

EuclideanCluster.h 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574575705
 ```  
EuclideanCluster.cpp 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574575705
 ```  
main.cpp 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574575705
 ```  
##  III. Display of results 

![avatar]( c8511c56fb9445c9bfc1ef99bc581876.jpeg) 

##  IV. Experimental data 

Link: https://pan.baidu.com/s/1JdXGgBMRBk6Ynbx6-pfiUw Extraction code: oupg 

