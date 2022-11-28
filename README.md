# Oracle-Veridata

This tool converts all Veridata OOS Json files as CSV files, for insert, delete and update.

Running example : 

java -jar VeridataOos.jar "C:\Oracle\Middleware\Oracle_Home\user_projects\domains\base_domain\veridata\reports\oosxml"

All result files are created directly in the directory containing the OSS data files

Naming :
"Job Veridata" "Group Name" "Session Id" "Pair Name" Update.csv
"Job Veridata" "Group Name" "Session Id" "Pair Name" Insert.csv
"Job Veridata" "Group Name" "Session Id" "Pair Name" Delete.csv
