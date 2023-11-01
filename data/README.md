# data

-There are 895,941 observations and 58 variables.

## tri_data

- `year`: The calendar year in which the reported activities occurred.
- `facility_name`: Name of the reporting facility.
- `street_address`: Street address of the reporting facility.
- `city`: City in which the reporting facility is located.
- `county`: County in which the reporting facility is located.
- `state`: Two-letter state code of the reporting facility.
- `zip_code`: ZIP code of the reporting facility.
- `bia_code`: Three-letter Bureau of Indian Affairs (BIA) code indicating the tribal land the facility is on.
- `tribal_land`: The name of the tribe.
- `latitude`: The latitude value that best represents the facility according to EPA’s Facility Registry System (FRS).
- `longitude`: The longitude value that best represents the facility according to EPA’s Facility Registry System (FRS).
- `parent_co_name`: Name of the corporation or other business entity that controls the reporting facility.
- `standard_parent_co_name`: Standardized Parent Company Name assigned by TRI.
- `federal_facility`: Code indicating whether a facility is a federal facility or not. Reported by the facility.
- `industry_sector`: The industry or sector (e.g., Coal Mining, Metal Mining, Electrical Utilities, etc.) a facility belongs to. This categorization is primarily used to classify, analyze, and show industrial trends within TRI data.
- `chemical`: Name of the chemical or (generic name, if the chemical is claimed as a trade secret).
- `elemental_metal_included`: Indicates whether the facility submitted a combined reporting form for a metal compound and the corresponding elemental metal. VALUES: YES = combined reporting form submitted for both an elemental metal and a metal compound containing the same elemental metal; NO = only metal compound reported.
- `clean_air_act_chemical`: Indicates if the chemical is covered by the Clean Air Act.
- `classification`: Indicates if the chemical is classified as a dioxin or dioxin-like compound, a Persistent Bioaccumulative and Toxic chemical, or a general EPCRA Section 313 chemical.
Values: {TRI, PBT, DIOXIN} where:
TRI = General EPCRA Section 313 Chemical
PBT = Persistent Bioaccumulative and Toxic
DIOXIN = Dioxin or Dioxin-like compound.
- `metal`: Code indicating if the chemical is a metal or not.
- `metal_category`: Category of Metal. Values are either 1, 2, 3, or 4. See “Appendix A: Chemical Classifications: Metals” for a list of metals in each of the four categories.
- `carcinogen`: Indicates if the chemical is a carcinogen.
- `pbt`: Code indicating whether the chemical is a PBT.
- `pfas`: Code indicating whether the chemical is a PFAS.
- `form_type`: Indicates whether the facility submitted a Reporting Form R or Form A Certification Statement.
- `unit_of_measurement`: Indicates the unit of measure used to quantify the chemical. Dioxin and dioxin-like compounds are reported in grams, while all other TRI chemicals are reported in pounds. Values: {Pounds, Grams}.
- `fugitive_air`: An estimate of the total quantity of the toxic chemical released as fugitive air emissions at the reporting facility.
- `stack_air`: An estimate of the total quantity of the chemical released as stack air emissions at the reporting facility.
- `water`: An estimate of the total quantity of the chemical released on- site as surface water discharges.
- `underground`: An estimate of the total quantity of the chemical injected on site at the facility to underground injection wells.
- `underground_class_1`: An estimate of the total quantity of the chemical injected on site at the facility into Class I wells.
- `underground_class_2_through_5`: An estimate of the total quantity of the chemical injected on site at the facility into Class II-V wells.
- `landfills`: An estimate of the total quantity of the chemical released to on-site landfills.
- `land_treatment`: An estimate of the quantity of the chemical disposed of through on-site land treatment/application farming.
- `surface_impoundment`: An estimate of the total quantity of the chemical released on site into surface impoundments. 
- `other_disposal`: An estimate of the total quantity of the chemical disposed of on site by methods other than landfills, land treatment and surface impoundments.
- `on_site_release_total`: Total quantity of the toxic chemical released to air, water and land on-site at the facility.
- `public_treatment_total_transfer`: This is the total amount of the chemical that is transferred to a POTW.
- `off_site_release_total`: Total quantity of the toxic chemical reported as transferred to off-site locations for release or disposal.
- `off_site_recycled_total`: Total quantity of the toxic chemical reported as transferred to off-site locations for recycling. 
- `off_site_energy_recovery_total`: Total quantity of the toxic chemical reported as transferred to off-site locations for energy recovery. 
- `off_site_treated_total`: Total quantity of the chemical reported as transferred off site for treatment. 
- `total_transfer`: Total quantity of the chemical reported as transferred off site.
- `total_releases`: The total on and off-site releases from sections 5 and 6 of the Form R. This field equals On-site Release Total + Off- site Release Total.
- `releases`: Amount of Total On- and Off-site Releases as reported in Section 8, Source Reduction and Recycling Activities / Pollution Prevention.
- `on_site_contained`: Beginning in RY 2003, the total releases in Section 8 of the Form R were broken up into four subcategories. For this data element, facilities reported Total On-Site Disposal to Class I Underground Injection Wells, RCRA Subtitle C landfills and other landfills.
- `on_site_other`: Beginning in RY 2003, the total releases in Section 8 of the Form R were broken up into four subcategories. For this data element, facilities reported their other on-site disposal or releases not covered in 8.1a.
- `off_site_contain`: Beginning in RY 2003, the total releases in Section 8 of the Form R were broken up into four subcategories. For this data element, facilities reported Total off-site disposal to Class I Underground Injection Wells, RCRA Subtitle C landfills and other landfills.
- `off_site_other`: Beginning in RY 2003, the total releases in Section 8 of the Form R were broken up into four subcategories. For this data element, facilities reported their other off-site disposal or releases not covered in 8.1c.
- `energy_recover_on`: The total quantity of the toxic chemical used on site for energy recovery.
- `energy_recover_off`: The total quantity of the toxic chemical sent off site for energy recovery.
- `recycling_on_site`: The total quantity of the toxic chemical recycled o site at the facility.
- `recycling_off_site`: The total quantity of the toxic chemical sent off site for recycling.
- `treatment_on_site`: The total quantity of the toxic chemical treated on site at the facility.
- `treatment_off_site`: The total quantity of the toxic chemical sent off site for treatment (including transfers to POTWs).
- `one_time_release`: The total quantity of the toxic chemical released to the environment or transferred off site due to events not associated with routine production processes.

-...