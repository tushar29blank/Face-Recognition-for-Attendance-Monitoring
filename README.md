# Face Recognition for attendance updation
This is a project requiring Machine Learning basic knowledge , python and its libraries numpy and opencv .

UPPER HAND : 
it can be helpful for any status updation( here attendance) by the facial data taken as input and is faster and more accurate than the typical manual way.

WORKING :
It works on python and its 2 libraries numpy and opencv ( do install these and import them while writing the code ).
Opencv has a cascade classifier for detection of objects in which there is a face cascade classifier that detects the face by the distance between the eyes ,the nose size and other unique facial details .

It takes the field inputs( can be name ,roll no. etc.) and facial data through(opencv fxns) in the form a matrix (2D array) and then stores the field values in a csv file, then it trains the system to detect the face by taking multiple samples.
After the data is stored in the file it takes facial images as input, if those images are detected upto a certain percentage(confidence value) the details are updated and if not then no updation is done( other actions can be performed too if needed).

FOR ACCURATE FACE DETECTION DO USE A DECENT CAMERA (MORE THAN 8 megapixels) AND THE BACKGROUND SHOULD BE WELL LIT( SHOULD HAVE DECENT LIGHTING ).
