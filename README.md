# ImagePreprocessing

I developed automated image pre-processing for large-scale image operations such as image property description, image resizes, and histogram visualizations. The script returns high throughput for image properties, resize, and histogram visualizations. 

The script calculates:
1.	Properties (counts, data type, pixel number, image size, channels) of all images in the directory. 
2.	Execution time 
3.	Resize all raw images to the same custom size
4.	Return histograms of individual raw and resized images, with the intensity in pixels on the y-axis 
5.	Save image properties in CSV format 
6.	Save histogram plots of raw and resized images

Real-world applications of this script are pre-processing high-throughput images, large-scale screens for assays, and machine learning.  
The histograms visualize intensity distributions and provide image features.

The measurements of the image properties are accessible in several ways: using a Jupyter notebook built-in to print the outputs and plot individual histograms; exporting spreadsheet format that is open in Microsoft Excel, SQL and MySQL databases or other programming languages (MATLAB, Python). 

The script is flexible to work with many image format types (gif, jpg, png) and customized by the user. 
It was written with python and tested with socket pins captured and collected in manufacturing using an optical system.
