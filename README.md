# JATS conversion and validation

Check an XML file against:
 * [JATS Article Publishing DTD](http://jats.nlm.nih.gov/publishing/tag-library/1.1d1/)
 * [PMC Style Checker](http://www.ncbi.nlm.nih.gov/pmc/tools/stylechecker/)

Convert and validate against:
 * [CrossRef Deposit Schema](http://help.crossref.org/#deposit_schema)
 * [DataCite Deposit Schema](http://schema.datacite.org/)
 * [DOAJ Deposit Schema](http://www.doaj.org/doaj?func=loadTempl&templ=uploadInfo)

## Usage

* Run ```cd schema && make fetch``` to fetch all the resources.
* Run ```tests/validate.sh filename``` to validate a JATS XML file.
* Output: any validation errors; NLM style report; HTML article preview.

## TODO

* JS rules for validating the HTML
* Microdata extraction tests
