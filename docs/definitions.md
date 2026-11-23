# Supplementary table interpretation

## eTable 1: NICU units
SOR codes are strings (not numbers). Counts for admissions involving multiple NICUs may be recorded under more than one unit and should not be summed to derive the overall number of admissions. A unit at Regionshospitalet Gødstrup became separately identifiable after restructuring in 2022 (SOR 899021000016000); the dash for earlier years means not separately identifiable, **not zero admissions**.

## eTable S2: chronic comorbidity
The supplied CSV preserves ICD-10 ranges exactly as written. Range expansion and the definition of inclusion boundaries require separate, validated code.

## eTable S3: diagnostic domains
Chapter/domain lookup table, not a patient-level dataset.

## eTable S4: treatments
An asterisk means all subcodes. Mechanical ventilation is `BGDA*` **excluding** non-invasive ventilation `BGDA1*`. Non-invasive ventilation is `BGDA1*` or `BGFC32M`. Do not treat the raw text as an executable regular expression.

## eTable S5: major neonatal morbidity
An asterisk means all subcodes. Morbidity ascertainment in the manuscript covers birth through PMA 43+6 weeks or death, whichever occurs first, for eligible infants born at 22–31 weeks' gestation.

## Publication alignment
The original supplement is retained as the source of record. Verify all CSV values, naming, and code definitions against the final published supplement before release.
