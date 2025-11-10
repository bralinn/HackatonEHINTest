# 8306 Hastegrad henvisning - LinnTest v0.0.1

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **8306 Hastegrad henvisning**

## CodeSystem: 8306 Hastegrad henvisning 

| | |
| :--- | :--- |
| *Official URL*:http://helsedir.no/fhir/CodeSystem/no-kodeverk-8306 | *Version*:0.0.1 |
| Active as of 2018-01-03 | *Computable Name*:NoKodeverk8306 |
| *Other Identifiers:*OID:2.16.578.1.12.4.1.1.8306 | |

 
Hastegrad for henvisning ifølge Nasjonal veileder for henvisninger til spesialisthelsetjenesten. 

 This Code system is referenced in the content logical definition of the following value sets: 

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "no-kodeverk-8306.codesystem",
  "url" : "http://helsedir.no/fhir/CodeSystem/no-kodeverk-8306",
  "identifier" : [
    {
      "system" : "urn:ietf:rfc:3986",
      "value" : "urn:oid:2.16.578.1.12.4.1.1.8306"
    }
  ],
  "version" : "0.0.1",
  "name" : "NoKodeverk8306",
  "title" : "8306 Hastegrad henvisning",
  "status" : "active",
  "date" : "2018-01-03",
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
  "description" : "Hastegrad for henvisning ifølge Nasjonal veileder for henvisninger til spesialisthelsetjenesten.",
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
  "caseSensitive" : true,
  "compositional" : false,
  "content" : "complete",
  "count" : 4,
  "concept" : [
    {
      "code" : "0",
      "display" : "Øyeblikkelig hjelp"
    },
    {
      "code" : "3",
      "display" : "Haster (elektiv)"
    },
    {
      "code" : "N",
      "display" : "Elektiv/Ordinær (elektiv)"
    },
    {
      "code" : "PK",
      "display" : "Pakkeforløp for kreft (elektiv)"
    }
  ]
}

```
