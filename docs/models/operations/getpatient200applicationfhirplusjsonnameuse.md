# GetPatient200ApplicationFhirPlusJSONNameUse

How this name should be used.
* usual - Known as, conventional or the one patient normally uses. A patient always has a usual name.
* temp - An alias or temporary name. This may also be used for temporary names assigned at birth or in emergency situations.
* nickname - A name that the patient prefers to be addressed by, but is not part of their usual name.
* old - This name is no longer in use (or was never correct, but retained for records).
* maiden - Name changed for Marriage. A name used prior to changing name because of marriage. This term is not gender specific. The use of this term does not imply any particular history for a person's name.

The following use codes are included in the [name-use](https://www.hl7.org/fhir/valueset-name-use.html) value set, but should not be used and is not be returned as part of a retrieval.
* official - The formal name as registered in an official (government) registry, but which name might not be commonly used. May be called "legal name".
* anonymous - Anonymous assigned name, alias, or pseudonym (used to protect a person's identity for privacy reasons).



## Values

| Name       | Value      |
| ---------- | ---------- |
| `USUAL`    | usual      |
| `TEMP`     | temp       |
| `NICKNAME` | nickname   |
| `OLD`      | old        |
| `MAIDEN`   | maiden     |