Task 1 (organ AI segmentation):
in this project we have implemented 3 different AI models in organ segmentation to determine the strengths of each model and to explore the field of AI segmentation to further improve the Diagnostics field.
Our Project preforms the following:
•	Analysis of NIFTI files
•	AI segmentation of 4 organs into 3 different parts
•	2D visualization
•	3D visualization
•	Evaluation of accuracy using 3 metrics:
	Dice Coefficient (overlap accuracy)
	IoU/Jaccard Index (intersection over union)
	Hausdorff Distance (boundary accuracy)
To achieve such a task we went through some steps:
1.	Creating a high quality NIFTI 3d viewer
2.	Create the Data analyzer
3.	AI segmentation (2D) 2d
4.	3D visualization 
5.	Evaluation
How to use:
1.	Copy the 3D viewer code in a python file in VS code
2.	Download the necessary Imports in the terminal
3.	Open the google collab AI link of your choosing
4.	Run and upload you NIFTI files
5.	Choose which organ you would like to segment 
6.	Use the Evaluation option to measure the accuracy (requires ground Truth file)
7.	Save your Segmentation and Upload the file to the 3D viewer to visualize
AI models used:
•	MONAI
•	Huggingface
•	MedSAM
Tools used in Development:
•	Google Collab
•	Claude AI
•	VS Code


