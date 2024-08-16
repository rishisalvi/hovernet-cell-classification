# Using Hovernet for Cell Classification of Lung Cancer Tissue
Link: [https://github.com/vqdang/hover_net?tab=readme-ov-file](https://github.com/vqdang/hover_net)

Things done: 
1. Training the Hovernet model on the Pannuke dataset
2. Fixed the QuPath annotations (end up with only 7 classes, necrosis -> no label)
3. Importing images/annotations into QuPath
5. Manually ading two more classes to the annotations
6. Converting .geojson files to .mat files
7. Extracting patches from the .mat files
8. Changed dataset.py to have a Pannuke dataset class with 7 options
9. Changed nr_types in config.py
4. Fixed .geojson to .mat file conversion (check .mat file contents)
5. Fixed errors when training the model
10. Training the model on the updated dataset

Files changed from default: 
1. extract_patches.py: changed file paths, I/O, image resizing
2. config.py: changed file paths
3. opt.py: changed file paths
4. dataset.py: added a new class classification
5. image_alignment.ipynb: runs all of the code for the things mentioned
