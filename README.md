# New Zealand Research Information System (NZRIS) Codesets

* Version: 0.6
* Generated: 16 June 2022

This repository aims to collate all codesets used by NZRIS into a machine
readable format. NZRIS will be a national, online hub of information about the
Research Science and Innovation (RSI) sector. You can find out more about the
NZRIS project on [MBIE's website at
www.mbie.govt.nz/nzris](https://www.mbie.govt.nz/nzris) (active at 17 December
2021).
 
NZRIS uses a number of national and international standards, as well as codesets
used by the RSI sector, and those specifically developed for NZRIS in
consultation with the RSI sector.

This repository contains codesets in Excel (xlsx), Comma Separated Values (CSV)
format, Tab Separated Values (TSV) format, and JavaScript Object Notation (JSON)
and Excel (xlsx) format. If you intend to use the codesets with Excel, we
recommend that you use the Excel (xlsx) files, as some other formats such as CSV
are altered on opening.

Note that the **public sector financial resource codeset** is intended to aid in
filling out the "Public Sector Financial Resource" sub-entity. In this
codeset we have aimed to cover as many RSI appropriations as possible, however
there may be additional values that need to be added to this list. You can
notify us of the need to add additional appropriations through [raising an issue
on this
repository](https://github.com/new-zealand-research-information-system/nzris-codesets/issues).
Note also that the amounts listed are the maximum for the estimates of 
appropriations.

All codesets have `Version`, `Code`, and `Description` columns. Note that
either the `Code` or `Description` for a codeset can be used when submitting
information to NZRIS.

Note that where a codeset has multiple levels we have used the most detailed for
the "Code" and "Description" fields, and made the others available as additional
columns using upper snake case names such as `Two_Digit_Code` and
`Two_Digit_Description` for the Australian and New Zealand Standard Research
Classification (ANZSRC) Socio-Economic Objective codeset. Not all levels of each
codeset can be submitted to NZRIS. For more detail on which levels can be
submitted, see the [NZRIS Data
Specifications](https://www.mbie.govt.nz/dmsdocument/1275-nzris-data-specification-2-01)
(active at 17 December 2021). As at version 2.01 of the NZRIS Data Specifications,
ethnicity is the only field that can be submitted in either of two levels of the
same codeset; level two, or level four can be submitted.


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
* **Public Sector Financial Resource**: multi-category appropriations are listed
with their categories in the format "Appropriation: Category", to maintain a 
link between the Appropriation ID, and to better track appropriations over time.
The code has been created as a composite of identifier, year and type.
* **ANZSRC Socio-economic objective (ANZSRC SEO) 2020**: there are two codes
with the description "Insects", the four-digit description has been added in 
order to distinguish between these when data is attempted to be matched back
to a code.
* **ORCID Work Types**: a version has been added as the date published on the 
[ORCID fequently asked questions page](https://info.orcid.org/faq/what-work-types-does-orcid-support/).


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

|Name                                                                                                     |Version            |Released          |Updated          |Maintainer                                                                |URL                                                                                                                                                                        |
|:--------------------------------------------------------------------------------------------------------|:------------------|:-----------------|:----------------|:-------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Australian and New Zealand Standard Industrial Classification                                            |1.0.0              |28 February 2007  |8 September 2008 |Stats NZ                                                                  |http://aria.stats.govt.nz/aria/#ClassificationView:uri=http://stats.govt.nz/cms/ClassificationVersion/CARS5851                                                             |
|Australian and New Zealand Standard Research Classification (ANZSRC) Fields of Research, 2008            |1.0.0              |31 March 2008     |7 November 2016  |Stats NZ and the Australian Bureau of Statistics                          |'http://aria.stats.govt.nz/aria/#ClassificationView:uri=http://stats.govt.nz/cms/ClassificationVersion/CARS6108'                                                           |
|Australian and New Zealand Standard Research Classification (ANZSRC) Fields of Research, 2020            |2.0.0              |30 July 2020      |30 July 2020     |Stats NZ and the Australian Bureau of Statistics                          |https://www.abs.gov.au/statistics/classifications/australian-and-new-zealand-standard-research-classification-anzsrc/latest-release#data-download                          |
|Australian and New Zealand Standard Research Classification (ANZSRC) Socio-Economic Objective, 2008      |1.0.0              |31 March 2008     |22 February 2017 |Stats NZ and the Australian Bureau of Statistics                          |http://aria.stats.govt.nz/aria/#ClassificationView:uri=http://stats.govt.nz/cms/ClassificationVersion/CARS6163                                                             |
|Australian and New Zealand Standard Research Classification (ANZSRC) Socio-Economic Objective, 2020      |2.0.0              |30 July 2020      |30 July 2020     |Stats NZ and the Australian Bureau of Statistics                          |https://www.abs.gov.au/statistics/classifications/australian-and-new-zealand-standard-research-classification-anzsrc/latest-release#data-download                          |
|Australian and New Zealand Standard Research Classification (ANZSRC) Type of Activity, 2008              |1.0.0              |31 March 2008     |11 April 2008    |Stats NZ and the Australian Bureau of Statistics                          |http://aria.stats.govt.nz/aria/#ClassificationView:uri=http://stats.govt.nz/cms/ClassificationVersion/CARS6147                                                             |
|Australian and New Zealand Standard Research Classification (ANZSRC) Type of Activity, 2020              |2.0.0              |30 July 2020      |30 July 2020     |Stats NZ and the Australian Bureau of Statistics                          |https://www.abs.gov.au/statistics/classifications/australian-and-new-zealand-standard-research-classification-anzsrc/latest-release#data-download                          |
|Ethnicity New Zealand Standard Classification                                                            |2.0.0              |1 September 2017  |6 March 2018     |Stats NZ                                                                  |http://aria.stats.govt.nz/aria/#ClassificationView:uri=http://stats.govt.nz/cms/ClassificationVersion/l36xYpbxsRh7IW1p                                                     |
|Statistical classification of gender identity                                                            |2.0.0              |17 July 2015      |17 May 2017      |Stats NZ                                                                  |http://aria.stats.govt.nz/aria/#ClassificationView:uri=http://stats.govt.nz/cms/ClassificationVersion/LfWjOFK1NqtZCv5i                                                     |
|International Standard Classification of Education and Training (ISCED) Fields of Education and Training |ISCED-F 2013       |29 November 2014  |29 November 2014 |United Nations Educational, Scientific and Cultural Organization (UNESCO) |https://eqe.ge/res/docs/228085e.pdf, and https://ec.europa.eu/assets/eac/education/tools/iscedf/iscedcodes.xml                                                             |
|International Standard Classification of Education and Training (ISCED) Education Programmes             |ISCED-P 2011       |1 December 2012   |1 December 2012  |United Nations Educational, Scientific and Cultural Organization (UNESCO) |http://uis.unesco.org/sites/default/files/documents/international-standard-classification-of-education-isced-2011-en.pdf                                                   |
|Currency Codes (ISO 4217)                                                                                |4217:2015          |1 August 2015     |1 August 2015    |Swiss Association for Standardization                                     |https://www.currency-iso.org/en/home/tables/table-a1.html                                                                                                                  |
|Language codes (ISO 639-2)                                                                               |639-2              |21 December 2017  |21 December 2017 |US Library of Congress                                                    |https://www.loc.gov/standards/iso639-2/ISO-639-2_utf-8.txt                                                                                                                 |
|Iwi and iwi-related groups statistical classification                                                    |1.0.0              |29 September 2017 |12 April 2019    |Stats NZ                                                                  |http://aria.stats.govt.nz/aria/#ClassificationView:uri=http://stats.govt.nz/cms/ClassificationVersion/QjykuWT5BTJrGdVs                                                     |
|The New Zealand Qualifications Framework Qualification Level (NZREG)                                     |NZREG 1.0.0        |26 May 2003       |2 June 2017      |Stats NZ                                                                  |http://aria.stats.govt.nz/aria/?_ga=2.201158958.1898241935.1553828338-1963735472.1473022903#ClassificationView:uri=http://stats.govt.nz/cms/ClassificationVersion/CARS4808 |
|New Zealand Standard Classification of Education (NZSCED) Field of Study                                 |NZSCED.FIELD 2.0.0 |29 September 2009 |11 May 2008      |Ministry of Education                                                     |http://aria.stats.govt.nz/aria/?_ga=2.201158958.1898241935.1553828338-1963735472.1473022903#ClassificationView:uri=http://stats.govt.nz/cms/ClassificationVersion/CARS6497 |
|ORCiD Supported Work Types                                                                               |2020-01-15         |NA                |NA               |Open Researcher and Contributor ID                                        |https://info.orcid.org/faq/what-work-types-does-orcid-support/                                                                                                             |


### List of codesets developed for NZRIS, or used in the RSI sector

|Name                                      |Version |
|:-----------------------------------------|:-------|
|Access Type                               |1.0     |
|Allocation Method                         |1.0     |
|Application Decision                      |1.0     |
|Application or Award Type                 |1.0     |
|Application Phase                         |1.0     |
|Asset Pool Recipient ID Type              |1.0     |
|Benefiting Region                         |1.0     |
|Centres of Research Excellence Theme      |1.0     |
|Constraint Type                           |1.0     |
|Distribution Basis                        |1.0     |
|Distribution Period Type                  |1.0     |
|Health Research Council Theme             |1.0     |
|National Science Challenge Theme          |1.0     |
|Organisation Identifier Type              |1.0     |
|Organisation Name Type                    |1.0     |
|Organisation Project Role                 |1.0     |
|Organisation Type                         |1.0     |
|Output Identifier Type                    |1.0     |
|Person Career Stage                       |1.0     |
|Person Identifier Type                    |1.0     |
|Personnel (Project) Role                  |1.0     |
|Project Type                              |1.0     |
|Protection Pattern                        |1.0     |
|Public Sector Financial Resource          |1.0     |
|Public Sector Research Alignment          |1.0     |
|Resource Measure - Non-Currency           |1.0     |
|Resource Type                             |1.0     |
|Review Method                             |1.0     |
|Review Outcome                            |1.0     |
|Status                                    |1.0     |
|Tertiary Education Commission Output Type |1.0     |
|Vision Matauranga Theme                   |1.0     |
