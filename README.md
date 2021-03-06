# DATA FOR UNIFI
*Creating data for Unifi platform with PUFs*

## NPPES
- Downloaded from https://download.cms.gov/nppes/NPI_Files.html on July 28, 2020. This file contains information from 2005-05-23 to 2020-07-12
- Note: This data set is updated every month with a full replacement file.
- Limit data to the following taxonomy codes:
### PEDIATRICS
    208000000X - Pediatrics
    2080A0000X - Adolescent Medicine
    2080C0008X - Child Abuse Pediatrics
    2080I0007X - Clinical & Laboratory Immunology
    2080P0006X - Developmental - Behavioral Pediatrics
    2080H0002X - Hospice and Palliative Medicine
    2080T0002X - Medical Toxicology
    2080N0001X - Neonatal-Perinatal Medicine
    2080P0008X - Neurodevelopmental Disabilities
    2080B0002X - Obesity Medicine
    2080P0201X - Pediatric Allergy/Immunology
    2080P0202X - Pediatric Cardiology
    2080P0203X - Pediatric Critical Care Medicine
    2080P0204X - Pediatric Emergency Medicine
    2080P0205X - Pediatric Endocrinology
    2080P0206X - Pediatric Gastroenterology
    2080P0207X - Pediatric Hematology-Oncology
    2080P0208X - Pediatric Infectious Diseases
    2080P0210X - Pediatric Nephrology
    2080P0214X - Pediatric Pulmonology
    2080P0216X - Pediatric Rheumatology
    2080T0004X - Pediatric Transplant Hepatology
    2080S0012X - Sleep Medicine
    2080S0010X - Sports Medicine
    
  ### Addiction Specific Care
    208A0401X - Pyschiatry & Neurology: Addiction Medicine
    2084P0802X - Pyschiatry & Neurology: Addiction Psychiatry
    101YA0400X - Addiction (Substance Use Disorder)
    207LA0401X - Anesthesiology: Addiction Medicine
    207PT0002X - Emergency Medicine: Medical Toxicology
    207QA0401X - Family Medicine: Addiction Medicine
    207RA04001X - Internal Medicine: Addiction Medicine
    2080T0002X - Pediatrics: Medical Toxicology
    2083A0300X - Preventive Medicine: Addiction Medicine
    2083T0002X - Preventive Medicine: Medical Toxicology
    103TA0400X - Psychologist: Addiction (Substance Use Disorder)
    
  ### Pyschologist, Psychiatrist, Mental Health
     Starts with 103T, 2084, 101Y
     
   - Aggregated count of providers by Zipcode
   - Used python package, uszipcode, to add County and Population
   - Calculated Number of Providers per 100,000 residents (Zipcode level)
   - Aggregated count of providers by County
   - Calculated Number of Providers per 100,000 residents (County level)
  
