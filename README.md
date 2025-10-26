SDTM Conversion and Standardisation of Hypertension Study Data – Valsartan Hydrochlorothiazide

Project Overview

This project demonstrates the conversion of raw clinical trial data into CDISC SDTM-compliant datasets using SAS.
The study represents a Phase II hypertension trial involving adult subjects treated with CO-DIOVAN (Valsartan-Hydrochlorothiazide) across multiple investigational sites in India.

The objective of this project was to transform, validate, and standardise clinical data according to CDISC SDTM (Study Data Tabulation Model) specifications.


Domains Created

The following 14 SDTM domains were successfully created:
DM, EX, DS, MH, CM, SU, SC, VS, TA, TV, TI, AE, QS, SV, SE
Each dataset was programmed and validated in SAS, following SDTM IG (Implementation Guide) standards.


Key Activities

Derived unique subject identifiers, sequence numbers, and baseline flags using SAS DATA step programming.
Applied SAS functions such as CATX, SUBSTR, INPUT, PUT, and conditional logic (IF-THEN-ELSE) for data manipulation.
Merged and aligned datasets using PROC SQL, MERGE, and BY-group processing to maintain data consistency.
Imported and exported datasets using LIBNAME, INFILE, PROC IMPORT, and PROC EXPORT.
Implemented SAS Macros to automate repetitive tasks and ensure standardisation across domains.
Standardised variable names, formats, and controlled terms according to CDISC SDTM standards.


Tools & Technologies

SAS Base Programming
SAS Macros
PROC SQL
CDISC SDTM (v3.2)
Clinical Data Management Concepts


PROJECT STRUCTURE:

📁 SDTM_Hypertension_Study/
├── 📄 README.md
├── 📂 Raw_Data/
│   └── (Original CSV or TXT files)
├── 📂 SDTM_Specifications/
│   └── (Define.xml, Variable Specs)
├── 📂 SAS_Programs/
│   ├── DM.sas
│   ├── EX.sas
│   ├── AE.sas
│   └── ... (other domain programs)
├── 📂 SDTM_Output/
│   └── (Final SDTM XPT or SAS7BDAT files)
└── 📂 Validation/
    └── (Log files, QC programs)



Outcome

This project provided hands-on experience in:
Applying CDISC SDTM standards
Mapping and transforming raw data
Using SAS for clinical programming and automation
Preparing regulatory-compliant datasets



Author
Dr ALTHAF SHAIK 
PHARM.D
Clinical SAS Programmer (Trainee)
letsmailalthafsk@gmail.com
www.linkedin.com/in/dr-althaf-shaik-546322311
