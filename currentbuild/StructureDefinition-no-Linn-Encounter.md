# Linns Test Encounter - LinnTest v0.0.1

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **Linns Test Encounter**

## Resource Profile: Linns Test Encounter 

| | |
| :--- | :--- |
| *Official URL*:http://hl7.no/fhir/ig/LinnTest/StructureDefinition/no-Linn-Encounter | *Version*:0.0.1 |
| Draft as of 2025-11-10 | *Computable Name*:LinnsEncounter |

 
The encounter associated with Linns test. 

**Usages:**

* This Profile is not used by any profiles in this Implementation Guide

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/hl7.fhir.no.LinnTest|current/StructureDefinition/no-Linn-Encounter)

### Formal Views of Profile Content

 [Description of Profiles, Differentials, Snapshots and how the different presentations work](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](StructureDefinition-no-Linn-Encounter.csv), [Excel](StructureDefinition-no-Linn-Encounter.xlsx), [Schematron](StructureDefinition-no-Linn-Encounter.sch) 



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "no-Linn-Encounter",
  "url" : "http://hl7.no/fhir/ig/LinnTest/StructureDefinition/no-Linn-Encounter",
  "version" : "0.0.1",
  "name" : "LinnsEncounter",
  "title" : "Linns Test Encounter",
  "status" : "draft",
  "date" : "2025-11-10T13:37:27+00:00",
  "publisher" : "Linn Brandt",
  "contact" : [
    {
      "name" : "Linn Brandt",
      "telecom" : [
        {
          "system" : "url",
          "value" : "https://github.com/bralinn"
        }
      ]
    }
  ],
  "description" : "The encounter associated with Linns test.",
  "jurisdiction" : [
    {
      "coding" : [
        {
          "system" : "urn:iso:std:iso:3166",
          "code" : "NO",
          "display" : "Norway"
        }
      ]
    }
  ],
  "fhirVersion" : "6.0.0-ballot3",
  "mapping" : [
    {
      "identity" : "workflow",
      "uri" : "http://hl7.org/fhir/workflow",
      "name" : "Workflow Pattern"
    },
    {
      "identity" : "w5",
      "uri" : "http://hl7.org/fhir/fivews",
      "name" : "FiveWs Pattern Mapping"
    },
    {
      "identity" : "rim",
      "uri" : "http://hl7.org/v3",
      "name" : "RIM Mapping"
    },
    {
      "identity" : "v2",
      "uri" : "http://hl7.org/v2",
      "name" : "HL7 V2 Mapping"
    }
  ],
  "kind" : "resource",
  "abstract" : false,
  "type" : "Encounter",
  "baseDefinition" : "http://hl7.org/fhir/StructureDefinition/Encounter",
  "derivation" : "constraint",
  "differential" : {
    "element" : [
      {
        "id" : "Encounter",
        "path" : "Encounter"
      },
      {
        "id" : "Encounter.priority",
        "path" : "Encounter.priority",
        "short" : "Hastegrad i henvisningen til oppholdet"
      }
    ]
  }
}

```
