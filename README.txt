
Install all the requirements,  
	

Then open in colab notebook

It might take some time to run the code and get the output.

We have imported images through the drive link and we get the output.
 
Then we take the inputs of distance, Method, template_size

Then, we do the SAD (Sum of Absolute difference Function) 

Later, We do SSD (Sum of Square difference Function)

Finally , we do the NCC (Normalized correlation) 

1)It is google colab file with .ipynb format.Go to the below link to open  google colab file 
https://colab.research.google.com/?utm_source=scs-index

2)upload the given file in the upload option.

3)upload the  files of stereo pair images to our drive .Import our google drive by running the below command.

from google.colab import drive
drive.mount('/content/drive')

4)run the each segment .Each one is loading the data files shared in the path and converts into numpy array.
Replace the paths with location file paths in your drive.

left='/content/drive/MyDrive/..../left.jpg'
right='/content/drive/MyDrive/...../..../right.jpg'

5)each disparity is found out by feature based or region based.
6)The methods to find correspondences is ssd ,sad,Ncc based on the user input.
7)Validity and averaging functions also implemeneted.