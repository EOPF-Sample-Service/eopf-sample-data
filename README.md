# eopf-sample-data-request
This is the repo for handling the EOPF sample data requests.

#### It will focus on below topics:
- **request new datasets**
- report **errors of the converted dataset**. This type of issues are focusing on conversion processing itself, which make sure that conversion processing is run correctly and output data are completely uploaded to the bucket. 
- present **issues or errors during converting certain type of scenes**
- other wishes regarding sample datasets.  i.e. uploading datasets of SAFE format for comparison

#### but exclude below topics:
 - issues are found in the converted dataset but **stem from CPM package**. They should be reported at  "https://gitlab.eopf.copernicus.eu/cpm/eopf-cpm/-/issues".
 - EOPF-ZARR **format related issues**: missing metadata, wrong metadata, or other suggestions, which should also go to eopf-cpm repo. 


## Request sample data

To request sample data for your use case, please create an issue following below steps:
- Add name of your user case into issue title
- Provide CDSE S3Path of requested scenes.
- Add expected date when you would like have the data


## S3Path of scene

The S3Path is path to S3 object of the scene at copernicus data space ecosystem, which you can find in the Prodcut metadata section. For example, S3Path for the Sentinel-2 L2A scene "S2A_MSIL2A_20180601T102021_N0500_R065_T32UPC_20230902T045008.SAFE" is

/eodata/Sentinel-2/MSI/L2A_N0500/2018/06/01/S2A_MSIL2A_20180601T102021_N0500_R065_T32UPC_20230902T045008.SAFE
