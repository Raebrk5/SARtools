# SARtools

Tools attached were submitted as  partial fulfilment of a Master of Science in Geospatial Technologies. 

The .model3 tools have been built to supliment useage of QRealTime plugin interface which imports the submission of collected data from ODK Collect forms. 

To use the tools download the Tools_sar.zip. Unzip the contents once you have located your QGIS3>profiles>default>processing>models folder. 

For general use the plugin search from QGIS and trouble shooting https://github.com/shivareddyiirs/QRealTime

For TexSar members please download the TexSar specific version found within the TexSar Folder > "QRealTimeTexSAR.zip" 
Extract the resulting file to AppData>QGIS>QGIS3>profiles>default>python>plugins as QRealTime
For access to the Team's Google App Engine instance or troubleshooting please contact Brandee Knight via TexSar directory email (Austin Chapter)
________________________________________________________________________________________________________________________________________
.model3 Tools: 

Clue Density Raster: Runs a hot spot analysis based upon the attributed value of the points submitted through the ODK form. This analysis can help to identify clustering of reports in areas. Clustering will allow for assets to be deployed to the areas with the highest likelihood of a subject being located. 

Probability of Area Buffer: Buffer rings using Euclidean distance statistics specific to the missing person’s profile using IPP as center. Profiles are found in “Missing Person Behavior” by Robert Koester. The rings created will have a percent of historical finds within them. 25%, 50%, 75% and 95% areas will be created for the last known or last seen point feature. The feature can be a point or a line dependent on the information known. 

Find Location Density Raster: Runs a hot spot analysis based on historical find location from SAR data for the subject’s profile. This tool is dependent on data sets for roads, linears (ex. trails), waterbodies, drainage, woods, rocks, and more. Not all of the feature are required but as many as possible are recommended. The weight of the feature type is based on historical data. The analysis can help to locate areas with a higher probability of the subject being located. (These features should be restricted to the Probability of Area Buffers prior to being run.)

Coverage Buffer: Buffer based analysis set up to keep a record of the areas that have been searched. The goal of this tool is to buffer (dependent on line of sight) the hasty coverage of an area. 

________________________________________________________________________________________________________________________________________
Additional information can be found at: https://prezi.com/p/cvg4pcdqp6ut/ 

Capstone Text: https://docs.google.com/document/d/1h_DvaaY_TUgmJqx_aKenlOthbqDnddXmfH_J2Iv6tNU/edit?usp=sharing

Texsar Team page: https://www.texsar.org/

Subject Profiles: https://www.dbs-sar.com/LPB/lpb.htm 
