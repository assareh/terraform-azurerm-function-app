# Azure Function App Request

This module is supplied by the cloud platforms team for all Function App instances on Azure.
Please note that all requests for Function App instances that bypass this module will be blocked by default.

If this module does not do what you need, please raise an issue or even better a pull request!

## Usage

The following inputs are required for this module:
- Project name
    - This is used as a unique identifier for your application in our Azure tenancy
- Location
    - The Azure location where your application should reside
- OS
    - Windows or Linux
- Hosting Plan
    - Consumption or Premium
- Archive File
    - Zip archive of function app to deploy


## Source
* https://github.com/maximivanov/publish-az-func-code-with-terraform