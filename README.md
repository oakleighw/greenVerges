# greenVergesRouteOCR
Contains code to extract useful location information from particular dashcam frames using PyTesseract
- Latitude, Longitude, Speed

## OCR ExtractVariables.ipynb
A notebook showing how tesseract can extract information from one particular frame, with the help of image processing and string formatting.

## Route_OCR_ExtractVariables.ipynb
A notebook showing how extracted frame data can be used to plot a route on a folium map - 
includes more robust string formatting and filtering to remove incorrect pyTesseract predictions. 

![](routeOCR.jpg?raw=true)
