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