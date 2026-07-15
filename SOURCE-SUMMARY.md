# Curbside Reference — Source Summary

## Source files received

Received and extracted:
- `Copy_of_Curbside_1_Route.xlsx`
- `Copy_of_Curbside_3_Route.xlsx`
- `Copy_of_PARTS_WASHERS.xlsx`

Still missing as uploaded file:
- `Copy_of_Curbside_2_Route.xlsx`

Extracted JSON output saved in:
- `C:\Users\Hector\Documents\Projects\curbside-reference\extracted\curbside1.json`
- `C:\Users\Hector\Documents\Projects\curbside-reference\extracted\curbside3.json`
- `C:\Users\Hector\Documents\Projects\curbside-reference\extracted\parts-washers.json`

---

## Initial findings

## Curbside 1
The uploaded Curbside 1 workbook contains weekday-based sheets:
- Monday
- Tuesday
- Wednesday
- Thursday
- Friday

The visible structure includes:
- unit names
- building numbers
- SAP references
- point-of-contact names
- phone numbers
- equipment series
- notes

Examples seen during extraction:
- 11TH ADA
- 32ND AAMDC
- 5/52 ADA
- 2/43 ADA
- TECHNICA
- MDRS
- MATES
- PDTE
- EAST BLISS CLINIC
- MENDOZA LAB
- PATHOLOGY
- PHARMACY
- ICU

## Curbside 3
The uploaded Curbside 3 workbook appears to have the same weekday structure and, from the initial extraction sample, currently looks very similar or identical to the uploaded Curbside 1 workbook.

This may mean one of these is:
- a duplicate copy
- an older/shared route template
- or a file that still needs verification against the intended route

This should be checked later with Hector.

## Parts Washers
The uploaded Parts Washers workbook contains multiple sheets and appears to track:
- washer type families
- building assignments
- DOE numbers
- serial numbers
- location initials
- quarterly service checkpoints

Sheet themes observed:
- BTC Parts Washers
- East Bliss Parts Washers
- Main Bliss Parts Washers
- CAB / Airfield / Border Patrol / Raytheon / Railhead
- Off Base Partswashers

Examples seen during extraction:
- BLDG 20105/20107
- BLDG 20115
- BLDG 21235
- BLDG 21245
- BLDG 1655
- BLDG 1050 MPs
- BLDG 13405
- BLDG 13425
- BLDG 2042 Marines
- BLDG 6995 Reserves

---

## Notes
- Curbside 2 has not yet been uploaded as an XLSX file in this chat.
- Once Curbside 2 is uploaded, it should be extracted and compared against Curbside 1 and 3.
- Before building the actual website, the files should be checked for:
  - duplicate routes
  - naming consistency
  - whether each sheet really maps to the intended team

---

## Recommended next step
1. Upload `Copy_of_Curbside_2_Route.xlsx`
2. Verify whether Curbside 1 and Curbside 3 are truly different
3. Build a normalized reference structure from all extracted files
4. Then start the real website design
