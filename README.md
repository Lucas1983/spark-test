Command to run spark script: spark-submit /opt/bitnami/spark/jobs/process.py

The original CSV file is split into two because GitHub doesn't allow files> 100 MB. 

Make sure to merge both CSV files into a single file before processing. 

The original file size referred to in the code is: demographic_dividend.csv

Try merging these files using the command.

cat first-half.csv second-half.csv > demographic_divident.csv
