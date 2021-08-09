# Application Rationalization Data Dictionary

## Table of Contents

 - [Introduction](https://github.com/AaronKoppel/AppRatDataDictionary/blob/main/README.md#introduction)
 - [Prerequisites](https://github.com/AaronKoppel/AppRatDataDictionary/blob/main/README.md#prerequisites)
 - [Usage](https://github.com/AaronKoppel/AppRatDataDictionary/blob/main/README.md#usage)
 - [Technical Schema](https://github.com/AaronKoppel/AppRatDataDictionary/blob/main/README.md#technical-schema)
 - [References](https://github.com/AaronKoppel/AppRatDataDictionary/blob/main/README.md#references)

## Introduction

Current Maintainer: GSA’s Data Center and Cloud Optimization Initiative (DCCOI) PMO at <dccoi@gsa.gov>

The Application Rationalization Data Dictionary is a supplement to the Application Rationalization Playbook to help agencies strategically and systematically identify business applications and determine which should be kept, replaced, retired, or consolidated. This resource establishes standards for data exchanges designed to manage application rationalization. Standards for data exchanges in turn allow users and agencies to explore and collaborate on their application rationalization data.

## Prerequisites

The Application Rationalization Data Dictionary is a spreadsheet in .csv format and is best viewed in spreadsheet software. It may also be viewed in GitHub directly.

## Usage

It consists of 10 columns:

**ID1**
- The unique integer, 1 to 176, associated with a given data element

**ID2**
- Structured in three parts: before the first decimal, between the first and second decimal, and after the second decimal
- Corresponds to the structure the Application Rationalization Playbook
- The number before the first decimal corresponds to the step in Application Rationalization Playbook
- The number between the first and second decimal corresponds to the sub-step in the Application Rationalization Playbook
- The number after the second decimal indicates its occurrence within a given sub-step in the Application Rationalization 
- 3.1.13 to 3.1.35 draw from the five Functions of NIST's Cybersecurity Framework
- 4.1.1 to 4.1.88 draw from the Finance and IT Layers of the TBM Taxonomy

**Name**
- Name of the data element

**Description**
- Description of the data element

**Type**
- Format of required/requested data: integer, floating point, or text

**Values**
- Possible categories for a given data element when numbers represent categories

**Codes**
- Numeric data when numbers represent categories

**Required?**
- Declaration (yes or no) if the data element is required 

**Example**
- Example of data element

**Notes**
- Additional information of interest for users

It consists of 176 data elements listed in columns.

## Technical Schema

A JSON schema for machine-readable data interchanges is provided, along with test data which can be used to validate it.

## References

Data Center and Cloud Optimization Initiative PMO, The Application Rationalization Playbook § (n.d.).

“TBM Taxonomy.” TBM Council, December 16, 2020. https://higherlogicdownload.s3.amazonaws.com/TBMCOUNCIL/c15d372f-9951-46c8-9c3f-213c696401b6/UploadedImages/TBM_Taxonomy_V4_0.pdf.
