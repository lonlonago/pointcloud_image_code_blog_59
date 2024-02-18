##  I. Overview 

  Given a point, find the point farthest from that point. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574596866
 ```  
##  III. Display of results 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574596866
 ```  


--------------------------------------------------------------------------------

##  I. Overview 

###  1. Algorithm source code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574541506
 ```  
###  2. Main functions 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574541506
 ```  
  The function that calculates the normal of the triangular plane of the model, usually called before rendering. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574541506
 ```  
##  III. Display of results 

###  1. Before calculation 

![avatar]( bbb162bdab1949879587872a843006b0.jpeg) 

###  2. After calculation 

![avatar]( c5d1e1df6c854a79b895a413a4ce0f28.jpeg) 



--------------------------------------------------------------------------------

##  I. Overview 

###  1. Algorithm principle 

  The calculation of triangular area in Open3D uses Helen's formula. For the specific calculation process, please refer to Baidu Encyclopedia. 

###  2. Main functions 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574546884
 ```  
###  3. Algorithm source code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574546884
 ```  
##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574546884
 ```  
##  III. Display of results 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574546884
 ```  


--------------------------------------------------------------------------------

##  I. Overview of the problem 

![avatar]( daef2ab1a09d403d854d74b99360ddbc.png) 

   C++ version of Open3D cannot read point clouds with Chinese names, and the visualization window cannot be set to Chinese names. As follows:   

##  II. Solutions 

>  Just add u8 in front of the Chinese name. 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

Test data: Open3D color point cloud registration test data ColoredICP.rar 

###  1. Overview of the principle 

>  Colored point cloud registration【配准论文解读】Color Point Cloud Registration with 4D ICP Algorithm 

###  2. References 

>  [1] Park J , Zhou Q Y , Koltun V . Colored Point Cloud Registration Revisited[C]// IEEE International Conference on Computer Vision. IEEE Computer Society, 2017. 

###  3. Main functions 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574550578
 ```  
This function implements the ColoredICP registration algorithm. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574550578
 ```  
##  III. Display of results 

![avatar]( c2087533a33548e7a7a7322feac2117c.png) 

 1. Initial position  

![avatar]( 0707547399f84f50a11edfe664dde8e1.png) 

 2. Color point cloud registration results  

##  IV. Python code 

Open3D color point cloud registration 



--------------------------------------------------------------------------------

##  Introduction to the algorithm 

###  1. Main function 

  The ComputePointCloudDistance function in Open3D provides a way to calculate the distance from the source point cloud to the target point cloud, computing the distance of the point cloud. That is, it calculates the distance from each point in the source point cloud to the nearest point in the target point cloud. 

###  2. Algorithm source code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957454416
 ```  
  In the example below, a function is shown to calculate the distance between two clouds and render colors based on the distance. Note that this method can also be used to calculate the Chamfer distance between two clouds. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957454416
 ```  
##  III. Display of results 

![avatar]( 3a1c08c3718b40009b748befc2bf0aa3.png) 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

###  1. Calculation formula 

  For any point in the point cloud data, calculate its covariance matrix according to the coordinates of the points in its neighborhood. The calculation formula is as follows:  

  Where is the neighborhood point, which is the neighborhood point and the centroid of the point. 

###  3. Main functions 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574560205
 ```  
###  4. Function source code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574560205
 ```  
##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574560205
 ```  
##  III. Display of results 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574560205
 ```  


--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

###  1. Calculation formula 

  The center of mass refers to the center of mass, which is considered to be the imaginary point where the mass of the object is concentrated at this point. Usually, the coordinates of the center of mass of the object are calculated as follows: Among them, the coordinates of each mass point are the corresponding mass of the mass point. 

###  2. Computing in the point cloud 

  When calculating the point cloud centroid, let the above formula, then the point cloud centroid coordinate calculation formula is as follows: 

###  3. Main functions 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574596429
 ```  
###  4. Function source code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574596429
 ```  
##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574596429
 ```  
##  III. Display of results 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574596429
 ```  
![avatar]( 78533aebcfbf4718a0928b6a726142bf.jpeg) 

##  IV. Python code 

Open3D Computing Point Cloud Centroid 



--------------------------------------------------------------------------------

##  First, the main function 

###  std::distance 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574584505
 ```  
  Count the number of elements between [first, last). 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574584505
 ```  
##  Second, the maximum coordinate and its index 

  Here, to calculate the minimum value of the coordinate Z value and its index, for example, to calculate the maximum value of x, y, the minimum value coordinate and its index, simply modify the code. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574584505
 ```  
##  III. Display of results 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574584505
 ```  
##  IV. Reference link 

std::distance 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

###  1. Calculation process 

###  2. References 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574554934
 ```  
##  III. Display of results 

![avatar]( 9b8e42edfbbd4c0b92efbec060276a2f.png) 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574598766
 ```  
##  III. Display of results 

![avatar]( da3085e7c9b440378bda9bf4ee0bf1b3.png) 

##  IV. References 

>  [1] Ma Zhenyu, Pang Yong, Li Zengyuan, Lu Hao, Liu Luxia, Chen Bowei. Fine classification of ground-based lidar forest near-surface point clouds and extraction of fallen trees [J]. Chinese Journal of Remote Sensing, 2019, 23 (04): 743-755. 



--------------------------------------------------------------------------------

##  First, the angle of radian rotation 

###  1. Calculation formula 

###  2. Main functions 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574571739
 ```  
>  To use this function, add: #include "angles .h" header file 

###  3. Sample code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574571739
 ```  
###  4. Display of results 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574571739
 ```  
##  Second, the angle of rotation 

###  1. Calculation formula 

###  2. Main functions 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574571739
 ```  
>  To use this function, add: #include "angles .h" header file 

###  3. Sample code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574571739
 ```  
###  4. Display of results 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574571739
 ```  
##  III. Normalized to (-PI, PI) 

###  1. Main function 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574571739
 ```  
>  To use this function, add: #include "angles .h" header file 

#include"angles.h 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574571739
 ```  


--------------------------------------------------------------------------------

##  I. DEM 

   Digital Elevation Model (Digital Elevation Model), referred to as DEM, is a digital simulation of ground terrain (that is, the digital expression of terrain surface morphology) through limited terrain elevation data. It is an entity ground model that represents ground elevation in the form of a set of ordered numerical arrays. It is a branch of Digital Terrain Model (DTM), from which various other terrain characteristic values can be derived. Generally speaking, DTM is a spatial distribution that describes a variety of geomorphological factors including elevation, such as slope, aspect, slope change rate, etc., including linear and nonlinear combinations. Among them, DEM is a zero-order simple single-item digital geomorphological model. Other geomorphological characteristics such as slope, aspect, and slope change rate can be derived on the basis of DEM. One article to understand DEM DSM DOM TDOM tilt photography 3D modeling, laser point cloud... 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574518471
 ```  
##  III. Display of results 

>  The above code realizes the format of converting the point cloud into DEM and saving it as a point cloud. The DEM model can be generated by using Delaunay triangulation to build a TIN triangulation network. The Delaunay triangulation network is realized in the CloudCompare software, so the software is directly used to generative model. 

###  1. Primitive point cloud 

![avatar]( 4558cc0995984b46bad3a4d121f40f23.png) 

###  2. DEM point cloud 

![avatar]( 8928f9160fcc4318ad62b57c49818012.png) 

###  3. DEM model 

![avatar]( 9fb946843dee4e37b9d132ded31093ae.png) 

##  IV. Test data 

Link: https://pan.baidu.com/s/1qPJY2usVBWGkdaq8VNoDog extraction code: ftx5 



--------------------------------------------------------------------------------

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



--------------------------------------------------------------------------------

##  First, the main function 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574521341
 ```  
>  Function Feature: Move unless finite point from PointCloud Args: remove_nan (bool, optional, default = True): Remove NaN value from PointCloud remove_infinite (bool, optional, default = True): Remove infinite value from PointCloud 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574521341
 ```  
##  III. Display of results 

![avatar]( 526740e1f50a407ea206fc6c9f3bdd2b.png) 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

###  1. Implementation process 

  The RGB-D camera can measure the depth of each pixel. After measuring the depth, the RGB-D camera usually completes the pairing between the depth depth and the color map according to the placement of each camera during production, and outputs the one-to-one corresponding color map and depth map. We can read the color information and distance information at the same position, calculate the 3D camera coordinates of the pixels, and generate a point cloud. The calculation formula is: in the formula, it is the depth value, and the unit is meters; it is the scaling multiple of the depth value; it is the pixel coordinate, which is the 3D point cloud coordinate corresponding to the pixel; it is the focal length of the camera, and it is the optical center of the camera, which is the so-called internal parameter. The pose of the camera is also called the external parameter of the camera, which will change with the camera movement. Knowing the inner parameter can generate a point cloud from the color map and depth map, and knowing the outer parameter can splice the point cloud generated by the color map and depth map measured at different positions of the same object into a complete ground object point cloud. 

###  2. Main functions 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574569638
 ```  
Realize the fusion of color images and depth images into RGBD to generate point clouds. This function has 5 built-in parameters, which are: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574569638
 ```  
This function is used to set the internal parameters of the camera and can be used as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574569638
 ```  
PinholeCameraIntrinsicParameters :: the default camera parameters provided by PrimeSenseDefaul for Open3D, its image resolution is: 640x480, focal length = (525.0, 525.0), optical center = (319.5, 239.5). The default outer parameter is the identity matrix. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574569638
 ```  
This function implements the internal parameter setting of the camera. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574569638
 ```  
or 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574569638
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574569638
 ```  
This function converts an RGBD image into a point cloud. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574569638
 ```  
##  III. Display of results 

![avatar]( 8b8eee416b6d4757ba43866f97a616d1.jpeg) 

 1. Color image 2. Depth image 3. Point cloud  

##  IV. Relevant links 

[1] Open3D 深度图像与彩色图像生成RGBD/点云(用法总结) 

##  Test data 

Test data of image transition point cloud realized by Open3D, PCL, matlab and other algorithms 



--------------------------------------------------------------------------------

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



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

###  1. Overview of the principle 

  In the area where the fluctuation is small and the point cloud does not contain outlier noise in the local range of the ground, the ground point and the non-ground point can be divided and extracted according to the height difference between each point and the lowest point. 

###  2. References 

>  Feng Maolin. Building Contour Extraction from Airborne Lidar Point Cloud under Tree Occlusion [D]. Southwest Jiaotong University, 2017. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529934
 ```  
##  III. Display of results 

###  1. Primitive point cloud 

![avatar]( 7aeb904005bf4cf19d0ec31cbdc97e68.png) 

###  2. Extract the results 

![avatar]( 4ec3b1473e104766b859b24feb776ffd.png) 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

###  1. Overview of the principle 

  Equal spacing thinning algorithm: Set the sampling spacing in the original point cloud data to, first select 1 point at the beginning of the data; then keep 1 point per interval until all points are screened. The advantages of the equal spacing thinning method are simple, fast and efficient, but the disadvantage is that it cannot better retain the micro-terrain features. 

###  2. References 

>  [1] Wang Daojie, Chen Bei, Sun Jianhui. Influence of airborne LiDAR point cloud density on DEM accuracy [J]. Bulletin of Surveying and Mapping, 2022 (05): 140-144 + 169. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574555890
 ```  
##  III. Display of results 

![avatar]( b63ffd21c49d470985e135b7e6c721c7.png) 



--------------------------------------------------------------------------------

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



--------------------------------------------------------------------------------

