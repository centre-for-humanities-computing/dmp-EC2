# EC2 Structured Data Specification

## Introduction

These table files document a series of data collections used in the European Cities Squeared (EC2) Project. The tables are designed to provide a structured overview of the data management practices, including metadata, access control, archiving, and provenance of the data collections. They are intended to be used as a reference for project team members and stakeholders involved in data management activities.

The tables serve as instruments for data management throughout the project and does also form the basis for the EC2 data management plan or reports required to meet project deliverables.

All table files are comma-separated. However, since they contain text fields, it could be argued that using a semicolon or tab character as a field separator would be more appropriate.

## The tables

| file                        | description                                                                |
|-----------------------------|----------------------------------------------------------------------------|
| data-collections.csv        | naming the collections and identifying with basic metadata                 |
| data-systems.csv            | naming the used infrastructure systems                                     |
| data-provenance.csv         | how are the collections collected                                          |
| data-access-control.csv     | who has access and when                                                    |
| org-data-access-control.csv | how are the data shared between organisations                              |
| data-archiving.csv          | how is the data archived and in applicable deposited                       |
| data-event-log.csv          | a log over events during the project in relation the these data colletions |


## How is FAIR attained

- *Findable*: Findable metadata of the collections are described in data-archiving.csv
- *Accessible*: Systems holding metadata and data are described in data-collections.csv and data-systems.csv
- *Interoperable*: Metadata schemas, data formats, and file types are described in data-collections.csv, data-achiving.csv, and data-systems.csv
- *Reusable*: In addition to the above, <data identifier>-provenence.csv contains technical information and scripts for reproducing and thereby reusing the data.