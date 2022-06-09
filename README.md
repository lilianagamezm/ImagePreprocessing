# ImagePreprocessing
Return high throughput for image properties, resize, histogram visualizations 
Developed automated image preprocessing for large-scale image operations such as, images property description, image resize and histogram visualizations.
The script calculates:
1.	Properties (counts, data type, pixel number, image size, channels) of all images in directory. 
2.	Execution time 
3.	Resize all raw images to the same custom size
4.	Return histograms of individual raw and resized images, with intensity of pixels in the y-axis 
5.	Save image properties in csv format 
6.	Save histogram plots of raw and resized images

Real-world scenario applications for this script include pre-processing of high throughput for image analysis, large-scale screens for assays, and machine learning models.  The histograms are useful to visualize intensity distributions and provide features of the images 
The measurements of the image properties are accessible in several ways: using jupyter notebook built-in to printing the outputs and plotting individual histograms; exporting spreadsheet format that can be opened in Microsoft Excel, database like SQL and MySQL or other programming languages (MATLAB, Python). 
The script is flexible to work with many images format types (tif, jpg, png, etc) and can be customized by the user. 
The script was written with python and tested with socket pins captured and collected in manufacturing using optical system
