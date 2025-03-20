# TD Integrity

TODO:  BETA DISCLAIMER (capture "as-is", Intel will best effort to keep refernce-values up-to-data, looking for feedback/contributions)
 

TD Integrity is feature of Intel® Tiber® Trust Authority that extends the chain-of-trust of confidential VMs from a TDX hardware-root-of-trust (HRoT) through the operating system.  For more information and instructions, please see the online documentation at https://docs.trustauthority.intel.com/main/articles/introduction.html (TODO:  LINK TO TDI PAGE).

![Details](diagrams/overview.drawio.svg)

This repository contains golden measurements and build automation that keep the TD Integrity appraisal policy (td-integrity.txt) and its reference-values up to date with Trust Authority supportes CSPs.

## Getting td-integrity.txt
Please use the "Actions" tab above to find the latest "main" build from this repository.  Each build will contain a "td-integrity" in the "Artifacts" section.  This zip file contains `tdx-integrity.txt` that can be uploaded to ITA.

## Local Builds and CI Automation
This repository uses scripts (make, bash, etc.) to generate the `td-integrity.txt` appraisal policy. This section contains an overview of those tools for developers that wish to contribute to this repository.

TODO...


## Code of Conduct and Contributing

See the [CONTRIBUTING](./CONTRIBUTING.md) file for information on how to contribute to this project. The project follows the [ Code of Conduct](./CODE_OF_CONDUCT.md).

## License

This library is distributed under the MIT license found in the [LICENSE](./LICENSE) file.

<br><br>
---
**\*** Other names and brands may be claimed as the property of others.