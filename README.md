# pds-fhir

<!-- Start SDK Installation -->
## SDK Installation

```bash
pip install git+https://github.com/speakeasy-sdks/nhse-apim-python.git
```
<!-- End SDK Installation -->

## SDK Example Usage
<!-- Start SDK Example Usage -->
```python
import pds_fhir
from pds_fhir.models import operations

s = pds_fhir.PdsFhir()

req = operations.GetPatientRequest(
    nhsd_end_user_organisation_ods='Y12345',
    nhsd_session_urid='555254240100',
    x_correlation_id='11C46F5F-CDEF-4865-94B2-0EE0EDCC26DA',
    x_request_id='60E0B220-8136-4CA5-AE46-1D97EF59D068',
    id='9000000009',
)

res = s.get_patient(req)

if res.get_patient_200_application_fhir_plus_json_object is not None:
    # handle response
```
<!-- End SDK Example Usage -->

<!-- Start SDK Available Operations -->
## Available Resources and Operations

### [PdsFhir SDK](docs/pdsfhir/README.md)

* [get_patient](docs/pdsfhir/README.md#get_patient) - Get patient details
* [get_related_people](docs/pdsfhir/README.md#get_related_people) - Get a patient's related people
* [search_patient](docs/pdsfhir/README.md#search_patient) - Search for a patient
* [update_patient_partial](docs/pdsfhir/README.md#update_patient_partial) - Update patient details
<!-- End SDK Available Operations -->

### Maturity

This SDK is in beta, and there may be breaking changes between versions without a major version update. Therefore, we recommend pinning usage
to a specific package version. This way, you can install the same version each time without breaking changes unless you are intentionally
looking for the latest version.

### Contributions

While we value open-source contributions to this SDK, this library is generated programmatically.
Feel free to open a PR or a Github issue as a proof of concept and we'll do our best to include it in a future release !

### SDK Created by [Speakeasy](https://docs.speakeasyapi.dev/docs/using-speakeasy/client-sdks)
