# New Zealand Research Information System (NZRIS) Label Schemes

* Version: 0.6
* Generated: 09 August 2022

This repository aims to collate all codesets used by NZRIS into a machine
readable format. NZRIS will be a national, online hub of information about the
Research Science and Innovation (RSI) sector. You can find out more about the
NZRIS project on [MBIE's website at
www.mbie.govt.nz/nzris](https://www.mbie.govt.nz/nzris) (active at 5 December
2025).
 
NZRIS uses a number of national and international standards, as well as codesets
used by the RSI sector, and those specifically developed for NZRIS in
consultation with the RSI sector.

This repository contains codesets and ingestion templates in Excel (xlsx), and Comma Separated Values (CSV)
format. If you intend to use the codesets with Excel, we
recommend that you use the Excel (xlsx) files, as some other formats such as CSV
are altered on opening.

Note that where a codeset has multiple levels we have used the most detailed for
the "Code" and "Description" fields, and made the others available as additional
columns using upper snake case names such as `Two_Digit_Code` and
`Two_Digit_Description` for the Australian and New Zealand Standard Research
Classification (ANZSRC) Socio-Economic Objective codeset. Not all levels of each
codeset can be submitted to NZRIS. 
### Some adjustments and assumptions have been made to fit the codesets into a standard model

* **ANZSRC Type of Activity (ToA) 2008 and 2020**: codes have been assigned (1-4) 
to each type of activity to align this structure with other codesets, however 
these are not part of the formal definition. 
* **International Standards Organisation (ISO) 639 Language Codes**: the three
letter code (ISO-639-2/T) has been used, as it provides good language coverage,
and the "a" in Māori has been macronised.
* **International Standards Organisation (ISO) 4217 Currency Codes**: the three
letter code has been used as the code rather than the numeric code due to wide
adoption, the numeric code is provided for reference only.
* **ANZSRC Socio-economic objective (ANZSRC SEO) 2020**: there are two codes
with the description "Insects", the four-digit description has been added in 
order to distinguish between these when data is attempted to be matched back
to a code.


### Characters in the codesets may display differently depending on the program used to open them

These codesets have been created using [UTF-8 Encoding](https://en.wikipedia.org/wiki/UTF-8) 
as this is seen by many as best practice for balancing character coverage and
space taken to store characters. Some systems have native support for UTF-8,
however many commonly used programs such as Microsoft Excel many not have the
ability to detect these characters and will convert them to another encoding.
See ["How to import CSV file that uses UTF-8 encoding"](https://excel.officetuts.net/en/examples/how-to-import-csv-file-that-uses-utf-8-encoding)
for a description of how to import files with UTF-8 encoding into Excel.


### Some codeset names may differ from their reference in the data specifications

In order to retain accurate descriptions of codesets, codeset names have been
recorded as they are found at source, and abbreviations have been expanded. This
means that there are some differences between the names of the codesets in the
NZRIS Data Specifications and the names used in this repository. Here is a
current summary of the differences between version 2.01 of the Data
Specifications and names used in this repository:

|Reference in Data Specifications |Codeset Name                                                                                             |
|:--------------------------------|:--------------------------------------------------------------------------------------------------------|
|HRC Theme                        |Health Research Council Theme                                                                            |
|NSC Theme                        |National Science Challenge Theme                                                                         |
|CoRE Theme                       |Centres of Research Excellence Theme                                                                     |
|TEC Output Type                  |Tertiary Education Commission Output Type                                                                |
|Gender Identity Classification   |Statistical Classification of gender identity                                                            |
|Iwi Classification               |Iwi and iwi-related groups statistical classification                                                    |
|Ethnicity Classification         |Ethnicity New Zealand Standard Classification                                                            |
|NZREG (v1.0)                     |The New Zealand Qualifications Framework Qualification Level (NZREG)                                     |
|ISCED-P                          |International Standard Classification of Education and Training (ISCED) Education Programmes             |
|NZSCEDFIELD                      |New Zealand Standard Classification of Education (NZSCED) Field of Study                                 |
|ISCED-F                          |International Standard Classification of Education and Training (ISCED) Fields of Education and Training |


### List of national and international codesets used by NZRIS

|Name                                                                                                     |Version           |Released          |Updated          |Maintainer                                                                |URL                                                                                                                                                                        |
|:--------------------------------------------------------------------------------------------------------|:-----------------|:-----------------|:----------------|:-------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Australian and New Zealand Standard Research Classification (ANZSRC) Fields of Research, 2008            |1.0.0             |31 March 2008     |7 November 2016  |Stats NZ and the Australian Bureau of Statistics                          |'http://aria.stats.govt.nz/aria/#ClassificationView:uri=http://stats.govt.nz/cms/ClassificationVersion/CARS6108'                                                           |
|Australian and New Zealand Standard Research Classification (ANZSRC) Fields of Research, 2020            |2.0.0             |30 July 2020      |30 July 2020     |Stats NZ and the Australian Bureau of Statistics                          |https://www.abs.gov.au/statistics/classifications/australian-and-new-zealand-standard-research-classification-anzsrc/latest-release#data-download                          |
|Australian and New Zealand Standard Research Classification (ANZSRC) Socio-Economic Objective, 2008      |1.0.0             |31 March 2008     |22 February 2017 |Stats NZ and the Australian Bureau of Statistics                          |http://aria.stats.govt.nz/aria/#ClassificationView:uri=http://stats.govt.nz/cms/ClassificationVersion/CARS6163                                                             |
|Australian and New Zealand Standard Research Classification (ANZSRC) Socio-Economic Objective, 2020      |2.0.0             |30 July 2020      |30 July 2020     |Stats NZ and the Australian Bureau of Statistics                          |https://www.abs.gov.au/statistics/classifications/australian-and-new-zealand-standard-research-classification-anzsrc/latest-release#data-download                          |
|Australian and New Zealand Standard Research Classification (ANZSRC) Type of Activity, 2008              |1.0.0             |31 March 2008     |11 April 2008    |Stats NZ and the Australian Bureau of Statistics                          |http://aria.stats.govt.nz/aria/#ClassificationView:uri=http://stats.govt.nz/cms/ClassificationVersion/CARS6147                                                             |
|Australian and New Zealand Standard Research Classification (ANZSRC) Type of Activity, 2020              |2.0.0             |30 July 2020      |30 July 2020     |Stats NZ and the Australian Bureau of Statistics                          |https://www.abs.gov.au/statistics/classifications/australian-and-new-zealand-standard-research-classification-anzsrc/latest-release#data-download                          |
|Currency Codes (ISO 4217)                                                                                |4217:2015         |1 August 2015     |1 August 2015    |Swiss Association for Standardization                                     |https://www.currency-iso.org/en/home/tables/table-a1.html                                                                                                                  |
|Language codes (ISO 639-2)                                                                               |639-2             |21 December 2017  |21 December 2017 |US Library of Congress                                                    |https://www.loc.gov/standards/iso639-2/ISO-639-2_utf-8.txt                                                                                                                 |


### List of codesets developed for NZRIS, or used in the RSI sector

|Name                                      |Version |
|:-----------------------------------------|:-------|

|Vision Matauranga Theme                   |1.0     |
