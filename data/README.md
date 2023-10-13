# data

Place data file(s) in this folder.

Then, include codebooks (variables, and their descriptions) for your data file(s)
using the following format.

## name of data file

- `variable1`: Description of variable 1
- `variable2`: Description of variable 2
- `variable3`: Description of variable 3


## 2011_us.csv

- 'YEAR': The calendar year in which the reported activities occurred.
- 'FACILITY NAME': Name of the reporting facility.
- 'STREET ADDRESS': Street address of the reporting facility.
- 'CITY': City in which the reporting facility is located.
- 'COUNTY': County in which the reporting facility is located.
- 'ST': Two-letter state code of the reporting facility.
- 'ZIP': ZIP code of the reporting facility.
- 'BIA': Three-letter Bureau of Indian Affairs (BIA) code indicating the tribal land the facility is on.
- 'TRIBE': The name of the tribe.
- 'LATITUDE': The latitude value that best represents the facility according to EPA’s Facility Registry System (FRS).
- 'LONGITUDE': The longitude value that best represents the facility according to EPA’s Facility Registry System (FRS).
- 'PARENT CO NAME': Name of the corporation or other business entity that controls the reporting facility.
- 'STANDARDIZED PARENT COMPANY NAME': Standardized Parent Company Name assigned by TRI.
- 'FEDERAL FACILITY': Code indicating whether a facility is a federal facility or not. Reported by the facility.
- 'INDUSTRY SECTOR': The industry or sector (e.g., Coal Mining, Metal Mining, Electrical Utilities, etc.) a facility belongs to. This categorization is primarily used to classify, analyze, and show industrial trends within TRI data.
- 'CHEMICAL': Name of the chemical or (generic name, if the chemical is claimed as a trade secret).
- 'ELEMENTAL METAL INCLUDED': Indicates whether the facility submitted a combined reporting form for a metal compound and the corresponding elemental metal. VALUES: YES = combined reporting form submitted for both an elemental metal and a metal compound containing the same elemental metal; NO = only metal compound reported.
- 'CLEAN AIR ACT CHEMICAL': Indicates if the chemical is covered by the Clean Air Act.
- 'CLASSIFICATION': Indicates if the chemical is classified as a dioxin or dioxin-like compound, a Persistent Bioaccumulative and Toxic chemical, or a general EPCRA Section 313 chemical.
Values: {TRI, PBT, DIOXIN} where:
TRI = General EPCRA Section 313 Chemical
PBT = Persistent Bioaccumulative and Toxic
DIOXIN = Dioxin or Dioxin-like compound.
- 'METAL': Code indicating if the chemical is a metal or not.
- 'METAL CATEGORY': Category of Metal. Values are either 1, 2, 3, or 4. See “Appendix A: Chemical Classifications: Metals” for a list of metals in each of the four categories.
- 'CARCINOGEN': Indicates if the chemical is a carcinogen.
- 'PBT': Code indicating whether the chemical is a PBT.
- 'PFAS': Code indicating whether the chemical is a PFAS.
- 'FORM TYPE': Indicates whether the facility submitted a Reporting Form R or Form A Certification Statement.
- 'UNIT OF MEASUREMENT': Indicates the unit of measure used to quantify the chemical. Dioxin and dioxin-like compounds are reported in grams, while all other TRI chemicals are reported in pounds. Values: {Pounds, Grams}.
- 'FUGITIVE AIR': An estimate of the total quantity of the toxic chemical released as fugitive air emissions at the reporting facility.
- 'STACK AIR': An estimate of the total quantity of the chemical released as stack air emissions at the reporting facility.
- 'WATER': An estimate of the total quantity of the chemical released on- site as surface water discharges.
- 'UNDERGROUND': An estimate of the total quantity of the chemical injected on site at the facility to underground injection wells.
- 'UNDERGROUND CLASS I': An estimate of the total quantity of the chemical injected on site at the facility into Class I wells.
- 'UNDERGROUND CLASS II-V': An estimate of the total quantity of the chemical injected on site at the facility into Class II-V wells.
- 'LANDFILLS': An estimate of the total quantity of the chemical released to on-site landfills.
- 'LAND TREATMENT': An estimate of the quantity of the chemical disposed of through on-site land treatment/application farming.
- 'SURFACE IMPNDMNT': An estimate of the total quantity of the chemical released on site into surface impoundments. 
- 'OTHER DISPOSAL': An estimate of the total quantity of the chemical disposed of on site by methods other than landfills, land treatment and surface impoundments.
- 'ON-SITE RELEASE TOTAL': Total quantity of the toxic chemical released to air, water and land on-site at the facility.
- 'POTW - TOTAL TRANSFERS': This is the total amount of the chemical that is transferred to a POTW.
- 'OFF-SITE RELEASE TOTAL': Total quantity of the toxic chemical reported as transferred to off-site locations for release or disposal.
- 'OFF-SITE RECYCLED TOTAL': Total quantity of the toxic chemical reported as transferred to off-site locations for recycling. 
- 'OFF-SITE ENERGY RECOVERY TOTAL': Total quantity of the toxic chemical reported as transferred to off-site locations for energy recovery. 
- 'OFF-SITE TREATED TOTAL': Total quantity of the chemical reported as transferred off site for treatment. 
- 'TOTAL TRANSFER': Total quantity of the chemical reported as transferred off site.
- 'TOTAL RELEASES': The total on and off-site releases from sections 5 and 6 of the Form R. This field equals On-site Release Total + Off- site Release Total.
- 'RELEASES': Amount of Total On- and Off-site Releases as reported in Section 8, Source Reduction and Recycling Activities / Pollution Prevention.
- 'ON-SITE CONTAINED RELEASES': Beginning in RY 2003, the total releases in Section 8 of the Form R were broken up into four subcategories. For this data element, facilities reported Total On-Site Disposal to Class I Underground Injection Wells, RCRA Subtitle C landfills and other landfills.
- 'ON-SITE OTHER RELEASES': Beginning in RY 2003, the total releases in Section 8 of the Form R were broken up into four subcategories. For this data element, facilities reported their other on-site disposal or releases not covered in 8.1a.
- 'OFF-SITE CONTAINED RELEASES': Beginning in RY 2003, the total releases in Section 8 of the Form R were broken up into four subcategories. For this data element, facilities reported Total off-site disposal to Class I Underground Injection Wells, RCRA Subtitle C landfills and other landfills.
- 'OFF-SITE OTHER RELEASES': Beginning in RY 2003, the total releases in Section 8 of the Form R were broken up into four subcategories. For this data element, facilities reported their other off-site disposal or releases not covered in 8.1c.
- 'ENERGY RECOVERY ON SITE': The total quantity of the toxic chemical used on site for energy recovery.
- 'ENERGY RECOVERY OFF SITE': The total quantity of the toxic chemical sent off site for energy recovery.
- 'RECYCLING ON SITE': The total quantity of the toxic chemical recycled o site at the facility.
- 'RECYCLING OFF SITE': The total quantity of the toxic chemical sent off site for recycling.
- 'TREATMENT ON SITE': The total quantity of the toxic chemical treated on site at the facility.
- 'TREATMENT OFF SITE': The total quantity of the toxic chemical sent off site for treatment (including transfers to POTWs).
- 'ONE-TIME RELEASE': The total quantity of the toxic chemical released to the environment or transferred off site due to events not associated with routine production processes.

## 2012_us.csv


## 2013_us.csv


## 2014_us.csv

-
- 
-

## 2015_us.csv

-
- 
-

## 2016_us.csv

-
- 
-

## 2017_us.csv

-
- 
-

## 2018_us.csv

-
- 
-

## 2019_us.csv

-
- 
-

## 2020_us.csv

-
- 
-

## 2021_us.csv

-
- 
-


- ...
