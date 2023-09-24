# AttentiveSkin
Predict Skin Corrosion/Irritation Potential of Chemicals with Explainable Machine Learning  
Download: https://github.com/BeeBeeWong/AttentiveSkin/releases/tag/v1.0  
  
  
  
  
![alt text](https://github.com/BeeBeeWong/AttentiveSkin/blob/main/dependency/icon/startup.png)


# Tutorial
![alt text](https://github.com/BeeBeeWong/AttentiveSkin/blob/main/example/how_to_use.png)  
  
  
Basic:  
AttentiveSkin is a software used for predicting GHS-defined (the Globally Harmonized System of Classification and Labeling of Chemicals) Skin Corrosion/Irritation labels of chemicals.  
Download and unzip the "AttentiveSkin_v1.0.zip" at the URL above.  
Place the file "AttentiveSkin.exe" and dir "dependency" in the same directory.  
Launch the "AttentiveSkin.exe" and wait until the GUI being initialized.  
  
Input:  
The input SMILES can be listed to the first column in .txt or .tsv files.  
User can follow the manner of example in "./example/input.txt".  
Click the button "Input" to open the text file containing input SMILES.  
  
Output:  
The interpretable prediction containing attetion weights will be placed in .html files, while basic info will be written to .xlsx files.  
Results of the two binary tasks (Corr vs Neg, Irrit vs Neg) are generated separately.  
Click the button "Output" to select the directory to store the prediction results.


# Tools used for software building
Sun Valley ttk theme (https://github.com/rdbende/Sun-Valley-ttk-theme) for GUI button styles;  
DGL-LifeSci (https://github.com/awslabs/dgl-lifesci) for Attentive FP (https://github.com/OpenDrugAI/AttentiveFP) architecture;  
Nuitka (https://github.com/Nuitka/Nuitka) for packaging Python codes.


# Logo
The logo of AttentiveSkin (prohibited sign + rabbit + droplet + test tube) is the printing of Windows-supplied fonts.  
Segoe UI Emoji font family on Win 10 (https://learn.microsoft.com/en-us/typography/font-list/segoe-ui-emoji)


# Cite
Details about the models can be accessed through this work: DOI_XXX


# Contact
Developer: Zejun Huang, incorrectwong11@gmail.com  
Corresponding author (Prof.): Yun Tang, ytang234@ecust.edu.cn
