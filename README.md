# AttentiveSkin
Predict Skin Corrosion/Irritation Potential of Chemicals with Explainable Machine Learning  
  
  
  
  
![alt text](https://github.com/BeeBeeWong/AttentiveSkin/blob/main/dependency/icon/startup.png)  
  
  
  
  
Download: https://github.com/BeeBeeWong/AttentiveSkin/releases/tag/v1.0


# Tutorial
![alt text](https://github.com/BeeBeeWong/AttentiveSkin/blob/main/example/how_to_use.png)  
  
  
Basic:  
AttentiveSkin is a software used for predicting GHS-defined (the Globally Harmonized System of Classification and Labeling of Chemicals) Skin Corrosion/Irritation potential of chemicals.  
Download and unzip the "AttentiveSkin_v1.0.zip" at the URL above.  
Place the file "AttentiveSkin.exe" and dir "dependency" in the same directory before launch.  
Please do not alter the files in dir "dependency".  
Open the "AttentiveSkin.exe" and wait like 10~30 seconds (sorry about that), and you will see the GUI initialized.  
  
Input:  
The input SMILES can be listed to the first column in .txt or .tsv files.  
User can simply follow the manner of example in "./example/input.txt".  
Click the button "Input" to open the text file containing input SMILES.  
  
Output:  
.html files contain attetion weight plots and the basic info in .xlsx files.  
Results of two binary tasks (Corr vs Neg, Irrit vs Neg) are generated separately.  
Click the button "Output" to select the directory to store the prediction results.


# Some tools used for software building
Sun Valley ttk theme (https://github.com/rdbende/Sun-Valley-ttk-theme) for GUI button styles;  
DGL-LifeSci (https://github.com/awslabs/dgl-lifesci) for Attentive FP (https://github.com/OpenDrugAI/AttentiveFP) architecture;  
Nuitka (https://github.com/Nuitka/Nuitka) for packaging Python codes.


# Logo design
The logo of AttentiveSkin (prohibited sign + rabbit + droplet + test tube) is the printing of Windows-supplied fonts.  
Segoe UI Emoji font family on Win 10 (https://learn.microsoft.com/en-us/typography/font-list/segoe-ui-emoji)


# Published article
Details about the tool can be accessed through our paper: DOI_XXX


# Contact
Developer: Zejun Huang, incorrectwong11@gmail.com  
Corresponding author (Prof.): Yun Tang, ytang234@ecust.edu.cn
