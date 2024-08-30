# Depth Image Based Rendering (DIBR)

Implement a Depth Image-Based Rendering (DIBR) algorithm in Python. This algorithm generate a new (virtual) 2D image that depicts 
the scene from a perspective different from the original image, when the program is provided with a 2D original image (V) and
a corresponding depth map (D). The generated image exhibits a natural perspective change,
i.e. the new view  presents scene objects that have been translated with different amounts
depending on how far away they are positioned from the camera.

Camera metadata - includes extrinsic [R|t] and intrinsic matrices K, and depth map normalization
factors Znear and Zfar. Znear and Zfar are needed to transform the dimensionless depth map D integerbased
value ranges into the floating point geometrical distance map Z. Znear corresponds to the
brightest gray scale value of the depth map and Zfar the darkest.
Image V – contains color, also known as texture, information.
Depth map D – contains the normalized depth information.

## 1. Requirements
	This project, contains 2 notebooks which which are in assignment_2 folder
	Run main to see results and outputs
	see lib.ipynb for functions and DIBR class
## 2. Running the code
1. Upload Assignment_2 Folder to googleDrive and Run Main.ipynb
2. 


## 3. Outputs
### 3.a. Generting Virtual Image
| Input RGB Image  |  Input Depth Image | Virtual Image | 
### 3.c. Generate N Virtual Images 
| Input RGB Image  |  Input Depth Image | N Virtual Image | 
### 3.c. Inpainting Generated Virtual Image
| Input RGB Image  | Output After python OpenCV's inbuild Telea inpainting algorithm | Filled Virtual Image

## 4. References
1. DIBR task.pdf in root path
2. DIBR background.pdf in root path
3. Habigt, Julian Albert. Hole-Filling Algorithms for Depth-Image-Based Rendering. Diss. Technische Universität München, 2020.
4. Computer Graphics: Principles and Practice by John F. Hughes, Andries van Dam, Morgan McGuire, David F. Sklar, James D. Foley, Steven K. Feiner, Kurt Akeley. Addison-Wesley, 2013

## 5. Notes
