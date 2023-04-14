<!-- Start SDK Example Usage -->
```typescript
import {
  FindRequest,
  FindResponse
} from "person-v2/dist/sdk/models/operations";

import { AxiosError } from "axios";
import { SDK } from "person-v2";
const sdk = new SDK();

const req: FindRequest = {
  company: "Medhurst - Rau",
  companyDomain: "quibusdam",
  email: "Ryan.Little62@yahoo.com",
  facebook: "deserunt",
  familyName: "suscipit",
  givenName: "iure",
  ipAddress: "magnam",
  linkedin: "debitis",
  location: "ipsa",
  twitter: "delectus",
  webhookUrl: "tempora",
};

sdk.find(req).then((res: FindResponse | AxiosError) => {
   // handle response
});
```
<!-- End SDK Example Usage -->