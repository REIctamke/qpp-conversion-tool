# Error messages
Current list of all error messages being output by the converter.
Any text in the following format `(Example)` are considered variables to be filled in.

### Format - Error Code : Error Message
* 1 : CT - Failed to find an encoder
* 2 : CT - The file is not a valid XML document. The file you are submitting is not a properly formatted XML document. Please check your document to ensure proper formatting.
* 3 : CT - Unexpected exception occurred during conversion. Please contact the Service Center for assistance via phone at 1-866-288-8292 or TTY: 1-877-715-6222, or by emailing QPP@cms.hhs.gov
* 4 : CT - Unexpected exception occurred during encoding. Please contact the Service Center for assistance via phone at 1-866-288-8292 or TTY: 1-877-715-6222, or by emailing QPP@cms.hhs.gov
* 5 : CT - The file is not a QRDA-III XML document. Please ensure that the submission complies with the `(Submission year's)` implementation guide. `(Implementation guide link)`
* 6 : CT - The measure GUID supplied `(Provided measure id)` is invalid. Please see the `(Submission year's)` IG https://ecqi.healthit.gov/sites/default/files/2021-CMS-QRDA-III-Eligible-Clinicians-and-EP-IG-v1.3.pdf#page=40 for valid measure GUIDs.
* 7 : CT - The measure reference results must have at least one measure. Please review the measures section of your file as it cannot be empty.
* 8 : CT - The `(Parent element)` has `(number of aggregate counts)` aggregate count values. A single aggregate count value is required.
* 9 : CT - Aggregate count value must be an integer
* 11 : CT - This PI Reference and Results is missing a required Measure Performed child
* 12 : CT - This PI Measure Performed Reference and Results requires a single Measure ID
* 13 : CT - Denominator count must be less than or equal to Initial Population count for the measure population `(measure population id)`
* 14 : CT - The electronic measure id: `(Current eMeasure ID)` requires `(Number of Subpopulations required)` `(Type of Subpopulation required)`(s) but there are `(Number of Subpopulations existing)`
* 15 : CT - PI Numerator Denominator element should have a PI Section element as a parent
* 16 : CT - PI Numerator Denominator element does not contain a measure name ID
* 17 : CT - PI Numerator Denominator element does not have any child elements
* 18 : CT - This PI Numerator Denominator element requires exactly one `(Denominator|Numerator)` element child
* 22 : CT - The PI Section must have one Reporting Parameter Act. Please ensure the Reporting Parameters Act complies with the Implementation Guide (IG). Here is a link to the IG Reporting Parameter Act section: https://ecqi.healthit.gov/sites/default/files/2021-CMS-QRDA-III-Eligible-Clinicians-and-EP-IG-v1.3.pdf#page=17
* 23 : CT - Clinical Document element must have at least one child element of type PI, IA, or Measure section
* 24 : CT - Clinical Document must have one and only one program name. Valid program names are `(list of valid program names)`
* 25 : CT - The Clinical Document program name `(program name)` is not recognized. Valid program names are `(list of valid program names)`.
* 26 : CT - Clinical Document contains duplicate PI sections
* 27 : CT - Clinical Document contains duplicate IA sections
* 28 : CT - Clinical Document contains duplicate Measure sections
* 29 : CT - Must have one and only one performance period start. Please see the Implementation Guide for information on the performance period here: https://ecqi.healthit.gov/sites/default/files/2021-CMS-QRDA-III-Eligible-Clinicians-and-EP-IG-v1.3.pdf#page=17
* 30 : CT - Must have one and only one performance period end. Please see the Implementation Guide for information on the performance period here: https://ecqi.healthit.gov/sites/default/files/2021-CMS-QRDA-III-Eligible-Clinicians-and-EP-IG-v1.3.pdf#page=17
* 31 : CT - Must have a performance year. Please see the Implementation Guide for information on the performance period here: https://ecqi.healthit.gov/sites/default/files/2021-CMS-QRDA-III-Eligible-Clinicians-and-EP-IG-v1.3.pdf#page=17
* 32 : CT - The Quality Measure Section must have exactly one Reporting Parameter Act. Please ensure the Reporting Parameters Act complies with the Implementation Guide (IG). Here is a link to the IG Reporting Parameter Act section: https://ecqi.healthit.gov/sites/default/files/2021-CMS-QRDA-III-Eligible-Clinicians-and-EP-IG-v1.3.pdf#page=17
* 33 : CT - The Performance Rate `(supplied value)` is invalid. It must be a decimal between 0 and 1.
* 34 : CT - CPC+/PCF submissions must contain a practice site address. Please refer to the `(Submission year's)` IG for more details https://ecqi.healthit.gov/sites/default/files/2021-CMS-QRDA-III-Eligible-Clinicians-and-EP-IG-v1.3.pdf#page=25 regarding practice site addresses.
* 35 : CT - One and only one Alternative Payment Model (APM) Entity Identifier should be specified. Here is a link to the IG section on identifiers: https://ecqi.healthit.gov/sites/default/files/2021-CMS-QRDA-III-Eligible-Clinicians-and-EP-IG-v1.3.pdf#page=15
* 36 : CT - CPC+/PCF submissions must contain one Measure section
* 37 : CT - CPC+/PCF submissions must contain correct number of performance rate(s). Correct Number is `(Expected value)` for measure `(Given measure id)`
* 39 : CT - This PI `(Numerator or Denominator)` element has an incorrect number of Aggregate Count children. A PI `(Numerator or Denominator)` must have exactly one Aggregate Count element
* 41 : CT - This PI `(Numerator or Denominator)` element Aggregate Value '`(value)`' is not an integer
* 42 : CT - This PI `(Numerator or Denominator)` element Aggregate Value has an invalid value of '`(value)`'
* 43 : CT - The IA Section must have at least one Improvement Activity
* 44 : CT - The IA Section must have one Reporting Parameter Act. Please ensure the Reporting Parameters Act complies with the Implementation Guide (IG). Here is a link to the IG Reporting Parameter Act section: https://ecqi.healthit.gov/sites/default/files/2021-CMS-QRDA-III-Eligible-Clinicians-and-EP-IG-v1.3.pdf#page=17
* 45 : CT - The IA Section must contain only Improvement Activities and a Reporting Parameter Act
* 48 : CT - Missing strata `(Reporting Stratum UUID)` for `(Current subpopulation type)` measure `(Current subpopulation UUID)`. Here is a link to the IG valid Measure Ids section: https://ecqi.healthit.gov/sites/default/files/2021-CMS-QRDA-III-Eligible-Clinicians-and-EP-IG-v1.3.pdf#page=40
* 49 : CT - Amount of stratifications `(Current number of Reporting Stratifiers)` does not meet expectations `(Number of stratifiers required)` for `(Current subpopulation type)` measure `(Current Subpopulation UUID)`. Expected strata: `(Expected strata uuid list)`. Please refer to the Implementation Guide for correct stratification UUID's here: https://ecqi.healthit.gov/sites/default/files/2021-CMS-QRDA-III-Eligible-Clinicians-and-EP-IG-v1.3.pdf#page=40
* 50 : CT - An IA performed measure reference and results must have exactly one measure performed child
* 51 : CT - A single measure performed value is required and must be either a Y or an N.
* 52 : CT - The measure data with population id '`(population id)`' must have exactly one Aggregate Count.
* 53 : CT - Measure data with population id '`(population id)`' must be a whole number greater than or equal to 0
* 55 : CT - A `(Program name)` Performance period start must be 01/01/2021. Please refer to the IG for more information here: https://ecqi.healthit.gov/sites/default/files/2021-CMS-QRDA-III-Eligible-Clinicians-and-EP-IG-v1.3.pdf#page=14
* 56 : CT - A `(Program name)` Performance period end must be 12/31/2021. Please refer to the IG for more information here: https://ecqi.healthit.gov/sites/default/files/2021-CMS-QRDA-III-Eligible-Clinicians-and-EP-IG-v1.3.pdf#page=14
* 57 : CT - The measure reference results must have a single measure population
* 58 : CT - The measure reference results must have a single measure type
* 59 : CT - The electronic measure id: `(Current eMeasure ID)` requires a `(Subpopulation type)` with the correct UUID of `(Correct uuid required)`. Here is a link to the IG containing all the valid measure ids: https://ecqi.healthit.gov/sites/default/files/2021-CMS-QRDA-III-Eligible-Clinicians-and-EP-IG-v1.3.pdf#page=40
* 61 : CT - A Performance Rate must contain a single Numerator UUID reference.
* 62 : CT - The Alternative Payment Model (APM) Entity Identifier must not be empty. Here is a link to the IG section on identifiers: https://ecqi.healthit.gov/sites/default/files/2021-CMS-QRDA-III-Eligible-Clinicians-and-EP-IG-v1.3.pdf#page=15
* 63 : CT - The Alternative Payment Model (APM) Entity Identifier is not valid.  Here is a link to the IG section on identifiers: https://ecqi.healthit.gov/sites/default/files/2021-CMS-QRDA-III-Eligible-Clinicians-and-EP-IG-v1.3.pdf#page=15
* 64 : CT - CPC+ Submissions must have at least `(CPC+ measure group minimum)` of the following `(CPC+ measure group label)` measures: `(Listing of valid measure ids)`
* 66 : CT - Missing the `(Supplemental Type)` - `(Type Qualification)` supplemental data for code `(Supplemental Data Code)` for the measure id `(Measure Id)`'s Sub-population `(Sub Population)`
* 67 : CT - Must have one count for Supplemental Data `(Supplemental Data Code)` on Sub-population `(Sub Population)` for the measure id `(Measure Id)`
* 68 : CT - Your `(Program name)` submission was made after the CPC+/PCF Measure section submission deadline of `(Submission end date)`. Your CPC+ QRDA III file has not been processed. Please contact CPC+ Support at `(CPC+ contact email)` for assistance.
* 69 : CT - `(Performance period start or end date)` is an invalid date format. Please use a standard ISO date format. Example valid values are 2019-02-26, 2019/02/26T01:45:23, or 2019-02-26T01:45:23.123. Please see the Implementation Guide for information on the performance period here: https://ecqi.healthit.gov/sites/default/files/2021-CMS-QRDA-III-Eligible-Clinicians-and-EP-IG-v1.3.pdf#page=17
* 70 : CT - The measure section measure reference and results has an incorrect number of measure GUID supplied. Please ensure that only one measure GUID is provided per measure.
* 71 : CT - Two or more different measure section measure reference and results have the same measure GUID. Please ensure that each measure section measure reference and results do not have the same measure GUID.
* 72 : CT - The Performance Rate is missing
* 78 : CT - The Program 'Mips Virtual Group' was found. The required entity id for this program name was missing. Please provide a virtual group identifier with the 'Mips Virtual Group' program name.
* 79 : CT - There is no TIN validator present, so NPI/Alternative Payment Model (APM) combinations cannot be verified
* 80 : CT - NPI `(npi)` and TIN `(tin)` are not reported as expected. This NPI/TIN combination is missing from the QRDA III file or is not in the CPC+ Practitioner Roster for `(apm)`. Please ensure your submission contains all required NPI/TIN combinations and your CPC+ Practitioner Roster is up-to-date.
* 81 : CT - At least one measure is required in a measure section
* 82 : CT - There are too many errors associated with this QRDA-III file. Showing 100 out of `(Error amount)` errors. Please fix the given errors and re-submit
* 84 : CT - `(Program name)` QRDA-III Submissions require at least one TIN to be present.
* 85 : CT - `(Program name)` QRDA-III Submission TINs require a 9 digit numerical value
* 86 : CT - This `(Program name)` QRDA-III submission is missing a TIN. Please ensure there is a TIN associated with every NPI submitted
* 87 : CT - `(Program name)` QRDA-III Submissions require at least one NPI to be present
* 88 : CT - `(Program name)` QRDA-III Submission NPIs require a 10 digit numerical value
* 89 : CT - This `(Program name)` QRDA-III submission is missing a NPI. Please ensure there is an NPI associated with every TIN submitted
* 90 : CT - `(Program name)` QRDA-III submissions must not contain an IA or PI section
* 91 : CT - The performance rate `(performanceRateUuid)` has an invalid null value. A performance rate cannot be null unless the performance denominator is 0
* 92 : CT - The performance denominator for measure `(measureId)` was less than 0. A performance rate cannot be null unless the performance denominator is 0
* 93 : CT - The numerator id `(numeratorUuid)` has a count value that is greater than the denominator and/or the performance denominator (Denominator count - Denominator exclusion count - Denominator Exception count)
* 94 : CT - The denominator exclusion id `(denexUuid)` has a count value that is greater than the denominator. The Denominator exclusion cannot be a greater value than the denominator.
* 95 : CT - The Clinical Document must contain one Measure Section v4 with the extension 2017-06-01
* 96 : CT - The APM to TIN/NPI Combination file is missing.
* 97 : CT - `(Program name)` QRDA-III Submissions require a valid Cehrt ID (Valid Format: XX15EXXXXXXXXXX)
* 98 : CT - The performance rate cannot have a value of 0 and must be of value Null Attribute (NA).
* 100 : CT - More than one Cehrt ID was found. Please submit with only one Cehrt id.
* 101 : CT - Denominator count must be equal to Initial Population count for CPC Plus measure population `(measure population id)`.
* 102 : CT - A PI section cannot contain PI_HIE_5 with PI_HIE_1, PI_LVOTC_1, PI_HIE_4, or PI_LVITC_2
* 103 : CT - PCF Submissions must have at least `(PCF Measure minimum)` of the following measures: `(Listing of valid measure ids)`
* 104 : CT - The file contains Promoting Interoperability (PI) data; PI data must not be reported for CPC+
* 105 : CT - If multiple TINs/NPIs are submitted, each must be reported within a separate performer
* 106 : CT - PI submissions are not allowed within PCF
