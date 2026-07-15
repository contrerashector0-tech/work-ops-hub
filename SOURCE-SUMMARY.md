# Curbside Reference — Source Summary

## Source files received

Received and extracted:
- `Copy_of_Curbside_1_Route.xlsx`
- `H.W.F.S---0cba8b41-103a-4727-bc20-0f56f56b02c6.xlsx` (confirmed by Hector as the Curbside 2 source)
- `Copy_of_Curbside_3_Route.xlsx`
- `Copy_of_PARTS_WASHERS.xlsx`
- `SAA_NRAP_Locations---828511ba-cd9f-4242-9e69-fbf97d5a0fad.xml` (Google Earth/KML export)

Extracted JSON output saved in:
- `C:\Users\Hector\Documents\Projects\curbside-reference\extracted\curbside1.json`
- `C:\Users\Hector\Documents\Projects\curbside-reference\extracted\curbside2.json`
- `C:\Users\Hector\Documents\Projects\curbside-reference\extracted\curbside3.json`
- `C:\Users\Hector\Documents\Projects\curbside-reference\extracted\parts-washers.json`
- `C:\Users\Hector\Documents\Projects\curbside-reference\extracted\saa_nrap_locations.json`
- `C:\Users\Hector\Documents\Projects\curbside-reference\extracted\saa_nrap_locations_summary.json`

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
- Curbside 2 is now loaded from `H.W.F.S---0cba8b41-103a-4727-bc20-0f56f56b02c6.xlsx`.
- The extracted Curbside 2 building set currently resolves to: `11108`, `13433`, `13430`, `13448`, and `2527`.
- In that workbook, values like `2450`, `1450`, and `8350` appear to be SAA/series values rather than building numbers, so they were not treated as buildings.
- The Earth export currently matches Curbside 2 buildings `13433`, `13430`, `13448`, and `2527`.
- `11108` is present in the Curbside 2 workbook but does not currently appear in the Earth export.
- Curbside 1 and Curbside 3 extracted files still appear to contain the same building set and should be verified later.

---

## Recommended next step
1. Verify whether Curbside 1 and Curbside 3 are truly different
2. Improve the Earth source over time so more route buildings move from "not found" to exact pin matches
3. Add parking, entrance, and reporting notes per building or route
4. Optionally add search and matched/unmatched counts directly in the live site
