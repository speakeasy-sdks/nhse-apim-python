# GetRelatedPeople200ApplicationFhirPlusJSONEntryResourcePatientIdentifier

Identifier and system of identification used for this Patient.

This is an optional field as related person details are either a reference to another NHS number, or the details, such as name and adress, stored directly on the resource.



## Fields

| Field                                                            | Type                                                             | Required                                                         | Description                                                      | Example                                                          |
| ---------------------------------------------------------------- | ---------------------------------------------------------------- | ---------------------------------------------------------------- | ---------------------------------------------------------------- | ---------------------------------------------------------------- |
| `system`                                                         | *Optional[str]*                                                  | :heavy_minus_sign:                                               | URL for the Patient retrieval API.                               | https://api.service.nhs.uk/personal-demographics/FHIR/R4/Patient |
| `value`                                                          | *Optional[str]*                                                  | :heavy_minus_sign:                                               | NHS number for the related person                                | 90000000009                                                      |