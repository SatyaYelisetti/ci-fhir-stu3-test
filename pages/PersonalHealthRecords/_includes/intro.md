# Personal Health Records FHIR Implementation Guide 
{:.no_toc}

{% include publish-box.html %}


<!-- TOC  the css styling for this is \pages\assets\css\project.css under 'markdown-toc'-->

* Do not remove this line (it will not be displayed)
{:toc}


<!-- end TOC -->


This implementation guide is an Australian realm implementation guide of the HL7<sup>TM</sup> FHIR<sup>&reg;</sup> specification to PLACEHOLDER-TEXT

This [implementation guide](http://hl7.org/fhir/STU3/implementationguide.html) is based on [FHIR<sup>&reg;</sup> version 3.0.1](http://hl7.org/fhir/STU3/index.html).

## Scope

### Use Cases
The following is the expected scenario:
* An individual or their authorised representative authors content to be stored in the My Health Record system

### Profiles
The FHIR<sup>&reg;</sup> profiles that form part of this implementation guide are shown below. The profiles defined in this implementation guide do not include profile-specific mappings to another format. The base FHIR<sup>&reg;</sup> STU3 mapping content for each of the resources referenced in this implementation guide can be found on the applicable resource documentation in the [FHIR Release 3 (STU)](http://hl7.org/fhir/STU3/index.html).

A profile that defines a representation of common header constraints for consumer entered aka Personal Health documents:
 * [Consumer Entered Information Document Header](StructureDefinition-composition-docheader-cei-1.html)

And supported documents:
* [Personal Health Notes](StructureDefinition-composition-phn-1.html)
* [Personal Health Summary](StructureDefinition-composition-phs-1.html)