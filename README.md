# EDSMS3EventProcessor
Create a Lambda Function
1) Create a bucket and folder where the file lands: (Example:-  Bucket:edsm-dev-incoming; Folder:v1)
2) Create a Lambda s3 trigger on the above s3 location
3) Environmental variables required : PreProcessedBucket = bucket where the xml and unzipped gzip contents are pushed into
4) Create a r1le that should be used with this Lambda function - read/write access \\ to S3  required.
