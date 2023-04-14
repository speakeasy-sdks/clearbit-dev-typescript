# person-v2

<!-- Start SDK Installation -->
## SDK Installation

### NPM

```bash
npm add https://github.com/speakeasy-sdks/clearbit-dev-typescript
```

### Yarn

```bash
yarn add https://github.com/speakeasy-sdks/clearbit-dev-typescript
```
<!-- End SDK Installation -->

## SDK Example Usage
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

<!-- Start SDK Available Operations -->
## Available Resources and Operations

### SDK SDK

* `find` - Look up a person by their email address
<!-- End SDK Available Operations -->

### Maturity

This SDK is in beta, and there may be breaking changes between versions without a major version update. Therefore, we recommend pinning usage
to a specific package version. This way, you can install the same version each time without breaking changes unless you are intentionally
looking for the latest version.

### Contributions

While we value open-source contributions to this SDK, this library is generated programmatically.
Feel free to open a PR or a Github issue as a proof of concept and we'll do our best to include it in a future release !

### SDK Created by [Speakeasy](https://docs.speakeasyapi.dev/docs/using-speakeasy/client-sdks)

