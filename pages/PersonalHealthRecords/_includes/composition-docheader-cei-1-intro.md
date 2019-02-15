## Consumer Entered Information Document Header

This profile defines common header requirements for consumer authored documents associated with a patient in an Australian healthcare context. 

##### **Usage Scenarios**
The following are the usage scenarios expected:
* An individual or their authorised representative authors content to be stored in the My Health Record system

##### **Each Composition SHALL have**
* a language with fixed value of 'en-AU'
* a single author
* a custodian

#####  **Must Support**
In the context of this profile [Must Support](http://hl7.org/fhir/STU3/conformance-rules.html#mustSupport) SHALL be interpreted as follows.
* The system SHALL be able to store and retrieve the following elements:
    * identifier
    * status
    * date
    * author
    * custodian
* The system SHALL be able to take the following elements into account when performing processing:
    * identifier
    * subject