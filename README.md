# CubeSat-Topology-Optimization
This is the first time I upload .exe file. Although it is ordered by the editor, I am excited about it.
.stl file is the model of CubeSat and show_TO.mp4 is the vedio of topology optimization.
The model, .stl file should be put in a subdirectory named with "show" together with the neccessary FreeFem++ file like FreeFem++.exe(for version 3.*).

During optimization, some .txt file will be built on directory. 
1.txt represents the first order natural frequency;
2.txt represents the second order natural frequency;
3.txt represents the third order natural frequency;
4.txt represents the fourth order natural frequency;
5.txt represents the fifth order natural frequency;
flag.vtk is the voxel model;
.ele, .face, .neigh and .node are the mesh information.

In the subdirectory named with "show", .vtk group file represent the optimization on topology. 
You can view the process of TO by ParaView.
