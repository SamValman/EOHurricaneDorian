# EOHurricaneDorian
## PlanetScope section of the report.  


To process such a large quantity of imagery required Google Earth Engine, Google Cloud, and batch processing to carry out as little as possible on harddrive.   
  
   
batch tiles were created with explanation in the batchTiles folder 

01_PlanetAPICall can be used to extract imagery from the PS archive and put it in seperate GEE image collections - due to storage it is required to be removed at the end of the process for each batch

02_ExtractionToGoogleDrive carries out some analysis in GEE (to save it being done on hard drive), composites the images and downloads them to Google Drive 

From google drive the results were extracted and analysed. 

This section was carried out by Sam Valman; samuel.valman@nottingham.ac.uk