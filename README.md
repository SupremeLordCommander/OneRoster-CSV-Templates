# Overview:
This project aims to provide a place to pull basic CSV files for OneRoster v1.1. Want to contribute feel free to make a pull request. We are begining to build out the v1.2 version that is currently in a development branch.

# OneRoster 1.1 CSV Files Overview.

Many school districts currently provide student information to tool providers and LMS/LOR vendors as '.csv' formatted files. For those districts that must continue to use CSV files to exchange roster information with vendors, the format defined in the Tables in Section 3 should be used: this format corresponds to the data model in the OneRoster [OneRoster, 20a] standard. Districts can choose to upload class rosters/gradebooks by preparing up to fourteen (14) files in CSV format outlined in this document. The rosters/gradebooks could be available for both import and export. A summary of the set of files is given in Table 2.1.

| CSV File Name | Req | Description | Notes |
| --- | --- | --- | --- |
| manifest.csv | Yes  | A control file. The manifest contains the version (set as 1.1) and the list of files that are supplied in this data set. | A new file added in V1.1. |
 | academicSessions.csv | No | A data file. The 'academic sessions' data model content. | Data model revised in v1.1. |
 | categories.csv | No | A data file. The definition for a set of lineItems. | A new file added in V1.1. |  | classResources.csv | No | A data file. The set of resources assigned to classes. | A new file added in V1.1. |
 | classes.csv | No | A data file. The 'classes' data model content. | Data model revised in v1.1. |
 | courseResources.csv | No | A data file. The set of resources assigned to courses. | A new file added in V1.1. |
| courses.csv| No| A data file. The 'courses' data model content.| Data model revised in v1.1. |
| demographics.csv | No | A data file. The 'demographics' data model content.| Data model revised in v1.1. |
| enrollments.csv | No | A data file. The 'enrollments' data model content. | Data model revised in v1.1.|
| lineItems.csv | No | A data file. The set of lineItems. | A new file added in V1.1. |
| orgs.csv | No | A data file. The' orgs' data model content. | N/A |
| results.csv | No | A data file. The set of results. | A new file added in V1.1.|
| resources.csv | No | A data file. The 'resources' data model content. | A new file added in V1.1. | 
| users.csv | No | A data file. The 'users' data model content. | Data model revised in v1.1. | 


## Key:

- CSV File Name - the name of the CSV file;
- Req - denotes whether or not the CSV file MUST be supplied (Yes or No);
- Description - a statement of the content in the file;
- There MUST NOT be more than one of each of the data CSV files. When the set of files are for bulk processing they must be semantically consistent, i.e., every object referenced in a file must also be defined in either the same, or one of the other files.