# VISUAL-PROMPTING-TECHNIQUES-FOR-ZERO--SHOT-GRAPHIC-LAYOUT-DESIGN

To run the experiments of your choice, put your OpenAI API Key in line number 14 and make changes to line number 16:  
`experiment_name = 'exp_name'`
by replacing exp_name with any of these options:                               
GPT4V, GPT4V-SOM, GPT4V-GRID, GPT4V-SLIC, GPT4V-WATER, GPT4V-REFERENCE

Then use the command: `python print_som1.py`

Folder Guide:
1. inpainted: contains the ground truth images
2. inpainted_768: contains the ground truth images resized to 768*768
3. reference: contains 5 reference images which represents ideal text positions to assist GPT4V
4. grid: contains the images segmented into uniform 3*3 grids 
5. slic: contains the images segmented based on SLIC (Simple Linear Iterative Clustering) by specifying number of clusters as 10
6. som: contains the images preprocessed by SOM(Set-of-Marks) prompting method 
7. watershed: contains the images segmented based on Watershed Segmentation algorithm by specifying number of clusters as 9
