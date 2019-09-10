# New Zealand Research Information System Codesets

* Version: 0.3.2
* Generated: 2019-09-11

The New Zealand Research Information System (NZRIS) uses a number of codesets.
This zip file contains a collection of codesets, in Excel, Comma Separated Values 
(CSV) format, Tab Seperated Values (TSV) format, and JavaScript Object Notation 
(JSON).

If you intend to use the codesets with Excel, we recommend that you use the Excel 
(xlsx) files, as some other formats such as CSV are altered on opening.


## What is a codeset?

A codeset is a set of discrete, definite values. Codesets are used for any
property in NZRIS which must be one of a limited number of values. For example,
NZRIS recognises exactly four **types** of application or award:

* An **individual** award, where a single individual submits their application and
  will receive the award.
* An **organisation** award, where a single orgnisation submits their application
  and will receive the award.
* A **multi-organisation** award, where multiple organisations submit their
  application and will receive the award.
* An **asset pool** award, where the awarded resources are devolved into an asset
  pool rather than being directly awarded.

NZRIS won't recognise any other type of application award: these four **codes**
make up the application/award type **codeset**.

## Who maintains these codesets?

Where possible, we have sourced codesets from external agencies (eg Stats NZ,
UNESCO). Where this is not possible, NZRIS-specific codesets are developed and
maintained by the NZRIS team.

## Where can I find more information about these codesets?

For more information on these codesets, please refer to the NZRIS Data
Specification, available on the [MBIE website](https://www.mbie.govt.nz/science-and-technology/science-and-innovation/research-and-data/nzris/nzris-tools-resources)

## Note that characters in the codesets may display differently depending on the program used to open them

These codesets have been created using [UTF-8 Encoding](https://en.wikipedia.org/wiki/UTF-8) 
as this is seen by many as best practise for balancing character coverage and
space taken to store characters. Some systems have native support for UTF-8,
however many commonly used programs such as Microsoft Excel many not have the
ability to detect these characters and will convert them to another encoding.
See ["How to import CSV file that uses UTF-8 encoding"](https://excel.officetuts.net/en/examples/how-to-import-csv-file-that-uses-utf-8-encoding)
for a description of how to import files with UTF-8 encoding into Excel.

## Note that some codeset names may differ from their reference in the data specifications

In order to retain accurate descriptions of codesets, codeset names have been 
recorded as they are found at source, and abreviations have been expanded. Here
is a current summary of the differences:

| Reference in Data Specifications | Codeset Name                                                                                             |
| --------------------------------+-------------------------------------------------------------------------------------------------------- |
| HRC Theme                        | Health Research Council Theme                                                                            |
| NSC Theme                        | National Science Challenge Theme                                                                         |
| CoRE Theme                       | Centres of Research Excellence Theme                                                                     |
| TEC Output Type                  | Tertiary Education Commission Output Type                                                                |
| Gender Identity Classification   | Statistical Classification of gender identity                                                            |
| Iwi Classification               | Iwi and iwi-related groups statistical classification                                                    |
| Ethnicity Classification         | Ethnicity New Zealand Standard Classification                                                            |
| NZREG (v1.0)                     | The New Zealand Qualifications Framework Qualification Level (NZREG)                                     |
| ISCED-P                          | International Standard Classification of Education and Training (ISCED) Education Programmes             |
| NZSCEDFIELD                      | New Zealand Standard Classification of Education (NZSCED) Field of Study                                 |
| ISCED-F                          | International Standard Classification of Education and Training (ISCED) Fields of Education and Training |


## List of externally-sourced codesets

| Name                                                                                                     | Version   | Released          | Updated          | Maintainer                                                                |
| --------------------------------------------------------------------------------------------------------+---------+-----------------+----------------+------------------------------------------------------------------------- |
| Australian and New Zealand Standard Industrial Classification                                            | 1.0.0     | 28 February 2007  | 8 September 2008 | Stats NZ                                                                  |
| Australian and New Zealand Standard Research Classification (ANZSRC) Fields of Research                  | 1.0.0     | 31 March 2008     | 7 November 2016  | Stats NZ and the Australian Bureau of Statistics                          |
| Australian and New Zealand Standard Research Classification (ANZSRC) Socio-Economic Objective            | 1.0.0     | 31 March 2008     | 22 February 2017 | Stats NZ and the Australian Bureau of Statistics                          |
| Australian and New Zealand Standard Research Classification (ANZSRC) Type of Activity                    | 1.0.0     | 31 March 2008     | 11 April 2008    | Stats NZ and the Australian Bureau of Statistics                          |
| Ethnicity New Zealand Standard Classification                                                            | 2.0.0     | 1 September 2017  | 6 March 2018     | Stats NZ                                                                  |
| Statistical classification of gender identity                                                            | 2.0.0     | 17 July 2015      | 17 May 2017      | Stats NZ                                                                  |
| International Standard Classification of Education and Training (ISCED) Fields of Education and Training | 2013      | 29 November 2014  | 29 November 2014 | United Nations Educational, Scientific and Cultural Organization (UNESCO) |
| International Standard Classification of Education and Training (ISCED) Education Programmes             | 2011      | 1 December 2012   | 1 December 2012  | United Nations Educational, Scientific and Cultural Organization (UNESCO) |
| Currency Codes (ISO 4217)                                                                                | 4217:2015 | 1 August 2015     | 1 August 2015    | Swiss Association for Standardization                                     |
| Language codes (ISO 639-2)                                                                               | 639-2     | 21 December 2017  | 21 December 2017 | US Library of Congress                                                    |
| Iwi and iwi-related groups statistical classification                                                    | 1.0.0     | 29 September 2017 | 12 April 2019    | Stats NZ                                                                  |
| The New Zealand Qualifications Framework Qualification Level (NZREG)                                     | 1.0.0     | 26 May 2003       | 2 June 2017      | Stats NZ                                                                  |
| New Zealand Standard Classification of Education (NZSCED) Field of Study                                 | 2.0.0     | 29 September 2009 | 11 May 2008      | Ministry of Education                                                     |
| ORCiD Supported Work Types                                                                               | 2.0       |                   |                  | Open Researcher and Contributor ID                                        |

## List of internally-sourced codesets

| Name                                      |
| ----------------------------------------- |
|                               Access Type |
|                         Allocation Method |
|                      Application Decision |
|                 Application or Award Type |
|                         Application Phase |
|                         Benefiting Region |
|      Centres of Research Excellence Theme |
|                           Constraint Type |
|                        Distribution Basis |
|                  Distribution Period Type |
|             Health Research Council Theme |
|          National Science Challenge Theme |
|              Organisation Identifier Type |
|                    Organisation Name Type |
|                 Organisation Project Role |
|                         Organisation Type |
|                    Output Identifier Type |
|                       Person Career Stage |
|                    Person Identifier Type |
|                  Personnel (Project) Role |
|                              Project Type |
|                        Protection Pattern |
|          Public Sector Research Alignment |
|           Resource Measure - Non-Currency |
|                             Resource Type |
|                             Review Method |
|                            Review Outcome |
|                                    Status |
| Tertiary Education Commission Output Type |
|                   Vision Matauranga Theme |
|          Public Sector Financial Resource |
