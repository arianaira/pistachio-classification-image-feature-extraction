<h1><center>Pistachio Classification</center></h1>
In this implementation we followed three main approaches:    
<br>
<br>
1- transer learning : choosing a powerful pre-trained model (inceptionV3) to extract freatures from images using pytorch
<br>
2- extracting color based and texture based features from the dataset and concating them with already obtained shape and morphological features  
<br>
  1 - color based ---> average RGB method --->   
  features added : (1- Red avg 2- Blue avg 3- Green avg)  
  <br>
  2 - texture based ---> Gray level co-occurance matrices(GLCM)--->   
  features added : (1- contrast 2- dissimilarity 3- homogeneity 4- energy 5- correlation) 
<br>
3- hybrid method of 1 and 2  
