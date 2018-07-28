
## IAMHANDWRITING file: 

Within this file is the code needed to pad each image and parse through the xml document, as well as the MSER made for the images.

#### How to use:

Download data/words and data/xml from here.

http://www.fki.inf.unibe.ch/databases/iam-handwriting-database/download-the-iam-handwriting-database


Extract the images to a folder 'img'.
Extract the xml files to a folder 'xml'.

Place both folders within the folder containing the the python files.

Before padding the images, create a new folder called paddedImg.

#### The MSER:
The second cell block teaches one how to load a single image, and runs it through the MSER. 
The third cell block cycles through all the images in the padded images file and displays the result of the MSER for 1000 milleseconds.

###### Notes:

. Unfortunantly, the IAMHANDWRITING dataset would not have been useful for our end goal of creating a code parser due to the limited amount of symbols included (for example, 
it only included 8 '+'s. Also, the MSER could not parse cursive code, which would have been required read from the data. 

. I realized that the MSER would work better if all the images were padded in white.

. Even after padding the images, the MSER still couldn't parse cursive, as the connection between the letters was a barrier it couldn't bypass.


