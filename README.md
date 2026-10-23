# IoT Data Integration: Nursery Scenario
Integrated Dataset

File: integrated_nursery.csv

The integrated dataset combines records from the three source files into one CSV file. Each row represents an event or measurement from a source dataset. The record_type and source_file fields identify the type and origin of each record.

The dataset contains fields for timestamps, room information, access events, newborn vital measurements, and room sensor readings. Blank fields indicate that information was not supplied or does not apply to that particular record.

Data Dictionary

File: data_dictionary.md
File: data_dictionary.md

The data dictionary describes each field in the integrated dataset, including its data type, units where applicable, and meaning.

Project Report


File: report.md

The source datasets, why the data was integrated, the selected output format, the data cleaning process, possible uses, and the trade-offs and limitations of the project.

Repository Files

batch101Update.csv — access log source data

feed101Updated(1).xml — newborn vital records source data

stream101Updated.json — room sensor source data

integrated_nursery.csv — combined dataset

data_dictionary.md — field descriptions and definitions

report.md — project report

README.md — project overview and documentation

Conclusion:
This project contains files from different devices that have nurse access, newborn vitals, and room sensors into a file data set. The files, data dictionary and report explain how each file can be organized and how it can be used to have information on a certain patient.
