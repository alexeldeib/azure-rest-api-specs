
## NodeJS
These settings apply only when `--nodejs` is specified on the command line.
Please also specify `--node-sdks-folder=<path to the root directory of your azure-sdk-for-node clone>`.

``` yaml $(nodejs)
nodejs:
  package-name: azure-applicationinsights
  package-version: 0.1.0
  output-folder: $(node-sdks-folder)/lib/services/applicationinsightsClient
  generate-license-txt: false
  generate-package-json: false
  generate-readme-md: false
```