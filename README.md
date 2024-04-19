# FEMA_EMD_DB

This repository contained the PostgreSQL scource code of FEMA Emergency Management dataset schema containing the information of the National Risk Index (NRI), Community Emergency Response Team (CERT), and Emergency Management Performance Grants (EMPG) datasets. 

For mining processes, this project chose the state level as our geographic unit. It mined the content, punctuation, and format from the raw datasets to accommodate the migration. Create schemas, tables, relations, and other components that are required for the construction of a relational database in PostgreSQL. Add a state abbreviation column for the EMPG table for joint connections.

### Data Resource
- [FEMA Emergency Management Dataset](https://www.fema.gov/about/openfema/data-sets#emergency)
- [FEMA National Risk Index Dataset](https://hazards.fema.gov/nri/data-resources#csvDownload)