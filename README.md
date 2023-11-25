# Face Recognition for attendance updation
This ia project requiring Machine Learning basic knowledge , python and its libraries numpy and opencv .

UPPER HAND : 
it can be helpful for any status updation( here attendance) by the facial data taken as input and is faster and more accurate than the typical manual way.

WORKING :
It works on python and its 2 libraries numpy and opencv ( do install these and import them while writing the code ).
Opencv has a cascade classifier for detection of objects in which there is a face cascade classifier that detects the face by the distance between the eyes the nose size and other facial features that distinguish  us.
it works as it takes the field inputs( can be name ,roll no. etc.) and facial data as the input (opencv fxns) in the form a matrix (2D array) and then stores the field values ina csv file and then  trains the system to detect the face by taking multiple samples.
After the data us stores in the file it takes the the face as the input and if the face is detected upto a certain percentage then it updates the values (specified in the code) and if not detected then other actions are done on the field values( specified  in the code).

FOR ACCURATE FACE DETECTION DO USE A DECENT CAMERA (MORE THAN 8 megapixels) AND THE BACKGROUND SHOULD BE WELL LIT( SHOULD HAVE DECENT LIGHTING ).
