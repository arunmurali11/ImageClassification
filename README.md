# ImageClassification

# Results

# Accuracy - 96.78%
Accuracy = (88+86+45+85+88+89)/497  = 96.78%

Pork

Correctly classified: 88

Incorrectly classified: 1



Bibimbop

Correctly classified: 86

Incorrectly classified: 6



BagelSandwich

Correctly classified: 45

Incorrectly classified: 0



FriedRice

Correctly classified: 85

Incorrectly classified: 3



ApplePie

Correctly classified: 88

Incorrectly classified: 5



Bread

Correctly classified: 89

Incorrectly classified: 1



# Incorrectly Classified Files:

Folder: Pork, File: B070220XX_11055.jpg

Folder: Bibimbop, File: B010316XX_02440.jpg

Folder: Bibimbop, File: B010316XX_02435.jpg

Folder: Bibimbop, File: B010316XX_02434.jpg

Folder: Bibimbop, File: B010316XX_02429.jpg

Folder: Bibimbop, File: B010316XX_02428.jpg

Folder: Bibimbop, File: B010316XX_02433.jpg

Folder: FriedRice, File: B010443XX_10244.jpg

Folder: FriedRice, File: B010443XX_10226.jpg

Folder: FriedRice, File: B010443XX_10200.jpg

Folder: ApplePie, File: A020511XX_02718.jpg

Folder: ApplePie, File: A020511XX_02717.jpg

Folder: ApplePie, File: A020511XX_02715.jpg

Folder: ApplePie, File: A020511XX_02631.jpg

Folder: ApplePie, File: A020511XX_02611.jpg

Folder: Bread, File: A020118XX_11009.jpg

# Steps to test the model

Model is designed in way, you provide root folder id, it will read all the image files in sub folders and classify images.
Say in our problem statement it was given FoodImage(folder id = 1fTBPKhOU5bTIo6gTmJmvzDXCT5fXUvTz) as root folder and Pork,FriedRice,BagelSandwich,BibimBop,Bread and ApplePie as sub folders with respective images. So test with similar folder, subfolder structure. Also you, should enter the classes in to classify as sub folder names, for example 

text_list = ["pork", "friedRice", "bagelSandwich", "bread", "bibimBop", "applePie"] 

Once you run the model go to the bottom of outputs, there it ll show the results how many images classified and missclassified in each class.Also the missclassified images with image ids

For any clarification reach me out to
# arunmurali11@gmail.com
