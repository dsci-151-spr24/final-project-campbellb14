# data

Place data file(s) in this folder.

Then, include codebooks (variables, and their descriptions) for your data file(s)
using the following format.

US Customs and Border Protection Encounter Data: 
cbp_resp

- `fiscal_year`: The fiscal year the encounter took place.
- `month_grouping`: Allows for comparisons between completed FY months vs. those remaining.
- `month_abbv`: The month the encounter took place (abbreviated, eg "APR").
- `component`: Which part of CBP was involved in the encounter ("Office of Field Operations" or "U.S. Border Patrol").
- `land_border_region`: The border region in which the encounter occurred ("Northern Land Border", "Southwest Land Border", or "Other"); border regions are defined by each component. Nationwide numbers are calculated by adding together Northern Land Border, Southwest Land Border, and Other regions.
- `area_of_responsibility`: The field office or sector where the encounter occurred.
- `aor_abbv`: The field office or sector where the encounter occurred (abbreviated).
- `demographic`: Categories under which individuals were encountered based on factors such as age, admissibility, and relationship (FMUA = Individuals in a Family Unit; UC = Unaccompanied Children).
- `citizenship`: Citizenship of the individual encountered.
- `title_of_authority`: The authority under which the noncitizen was processed (Title 8: The standard U.S. immigration law governing the processing of migrants, including deportations, asylum procedures, and penalties for unauthorized border crossings. Title 42: A public health order used during the COVID-19 pandemic to rapidly expel migrants at the border without standard immigration processing, citing health concerns.).
- `encounter_type`: The category of encounter based on Title of Authority and component (Title 8 for USBP = Apprehensions; Title 8 for OFO = Inadmissibles; Title 42 = Expulsions).
- `encounter_count`: The number of individuals encountered.
