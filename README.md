# Neonatal Intensive Care Unit Utilization and Outcomes in Denmark

## Overview

This repository accompanies the research article *Neonatal Intensive Care Unit Utilization and Outcomes in Denmark* by Buchardt, Farooqi, and Stensballe.

The study is a nationwide population-based cohort study describing neonatal intensive care unit (NICU) utilization, patient characteristics, treatments, and outcomes in Denmark from 2020 through 2025. Using Danish national health registers, the study examines temporal trends in NICU admissions, including age-specific admission rates, clinical characteristics, major neonatal morbidity, and mortality.

The repository provides the organizational identifiers, diagnostic classifications, and procedure code lists used to operationalize key study definitions. Its purpose is to facilitate transparency, interpretation, and reuse of the definitions applied in the study.

## Repository contents

The repository contains five supplementary tables, provided in CSV format.

### 1. Identification of neonatal intensive care units (eTable 1)

**File:** `data-dictionaries/etable1_nicu_units_counts_2020_2025.csv`

Contains the healthcare institutions, neonatal units, and corresponding identifiers from the Danish Register of Healthcare Organization (*Sundhedsvæsenets Organisationsregister*, SOR) used to identify NICU admissions.

The table also provides annual numbers of admissions by unit from 2020 through 2025.

NICUs were identified based on organizational affiliation rather than treatment intensity. Consequently, the study includes neonatal units providing different levels of care, ranging from observation and supportive treatment to highly specialized intensive care.

An organizational restructuring in 2022 affected the identification of neonatal admissions at one hospital. Before restructuring, neonatal care was provided within a broader pediatric unit and could not be distinguished using organizational affiliation. This change was addressed in a sensitivity analysis in the study.

### 2. Identification of chronic comorbidities (eTable S2)

**File:** `code-lists/etable_s2_chronic_comorbidity_icd10.csv`

Contains the ICD-10 codes used to identify chronic comorbidities, organized by diagnostic domain.

Chronic comorbidity was defined using a previously established algorithm for potentially life-threatening conditions in children. A qualifying diagnosis recorded before NICU admission was used to identify underlying chronic comorbidity.

### 3. Classification of diagnostic domains (eTable S3)

**File:** `code-lists/etable_s3_icd10_domains.csv`

Provides the correspondence between ICD-10 chapters and diagnostic domains used to classify diagnoses in the study.

These classifications support the descriptive presentation of diagnoses recorded during NICU admissions.

### 4. Identification of neonatal treatments (eTable S4)

**File:** `code-lists/etable_s4_neonatal_treatment_codes.csv`

Contains the procedure codes used to identify selected neonatal treatments, including:

- Mechanical ventilation
- Non-invasive ventilation
- Dialysis
- Pharmacological cardiac therapy
- Extracorporeal membrane oxygenation (ECMO)
- Continuous positive airway pressure (CPAP)
- Surfactant treatment
- Therapeutic hypothermia

The code lists include relevant subcode specifications and exclusions.

### 5. Identification of major neonatal morbidity (eTable S5)

**File:** `code-lists/etable_s5_major_neonatal_morbidity_codes.csv`

Contains the ICD-10 codes used to identify components of major neonatal morbidity among infants born at 22–31 weeks of gestation.

The conditions include intraventricular hemorrhage, periventricular leukomalacia, hydrocephalus, neonatal convulsions, retinopathy of prematurity, primary pulmonary hypertension, bronchopulmonary dysplasia, necrotizing enterocolitis, spontaneous intestinal perforation, and bacterial sepsis.

Major neonatal morbidity was ascertained from birth until postmenstrual age 43+6 weeks or death, whichever occurred first.

## Data sources and availability

The study used individual-level data from Danish nationwide health registers, including the Danish National Patient Register, the Danish Civil Registration System, and the Danish Medical Birth Register.

Individual-level register data cannot be made publicly available. Access is restricted to authorized researchers through the secure research environment at Statistics Denmark.

This repository contains study definitions, organizational identifiers, and diagnostic and procedure code lists. It does not contain individual-level register data.

## Use and interpretation

The materials document the operational definitions applied in the accompanying study. They are intended to support methodological transparency and facilitate reuse in other register-based studies.

Users should consider differences in register coverage, coding practices, organizational structures, and study populations before applying these definitions in other settings.

In particular, organizational identifiers may change over time, and the identification of NICU admissions based on organizational affiliation should not be interpreted as a direct measure of intensive treatment or illness severity.

The code lists document the study definitions but do not, by themselves, reproduce the complete data processing and statistical analyses.

## Citation

When using these materials, please cite the accompanying research article:

Buchardt AS, Farooqi NNU, Stensballe LG. *Neonatal Intensive Care Unit Utilization and Outcomes in Denmark*. [Publication details to be added.]

## Contact

For questions regarding the study definitions or supplementary materials, please contact the corresponding author through the contact information provided in the accompanying publication.
