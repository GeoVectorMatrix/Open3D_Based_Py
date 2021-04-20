# Open3D_Based_Py

Algorithm implementations based on Open3D （ https://github.com/intel-isl/Open3D ）

## Region growing
A simple implementation for region growing based on the normal differences. 

<div align=center><img src="https://github.com/GeoVectorMatrix/Open3D_Based_Py/blob/main/Imgs/RG_0.png" width="500" height="270"/><br/></div>
<p align="center">Orignal point clouds </p>

<div align=center><img src="https://github.com/GeoVectorMatrix/Open3D_Based_Py/blob/main/Imgs/RG7_5.png" width="500" height="270"/><br/></div>
<p align="center"> Classical region growing with the angle threshold equals 7.5 degree, the minimal cluster size is set to 100.  </p>

<div align=center><img src="https://github.com/GeoVectorMatrix/Open3D_Based_Py/blob/main/Imgs/RG_10.png" width="500" height="270"/><br/></div>
<p align="center"> Classical region growing with the angle threshold equals 10.0 degree, the minimal cluster size is set to 100.  </p>

## CGAL + Open3D in Shape detection

<div align=center><img src="https://github.com/GeoVectorMatrix/Open3D_Based_Py/blob/main/Imgs/RG_CGAL.png" width="500" height="270"/><br/></div>
<p align="center"> CGAL region growing with the default setting, except the minimal cluster size is set to 100. </p>

## Edge points detection demos
<div align=center><img src="https://github.com/GeoVectorMatrix/Open3D_Based_Py/blob/main/Imgs/Edges.png" width="600" height="270"/><br/></div>
<p align="center"> Extracting 3D edge candidates from point clouds. Edge candidates by thresholding the edge index (left). After applying the gradient-guidednon-maximum suppression (right). </p>

## TBD...
