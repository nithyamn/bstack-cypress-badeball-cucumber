# bstack-cypress-badeball-cucumber

## Pre-requisites
You can export the environment variables for the Username and Access Key of your BrowserStack account

  * For Unix-like or Mac machines:
  ```
  export BROWSERSTACK_USERNAME=<browserstack-username> &&
  export BROWSERSTACK_ACCESS_KEY=<browserstack-access-key>
  ```

  * For Windows Cmd:
  ```
  set BROWSERSTACK_USERNAME=<browserstack-username>
  set BROWSERSTACK_ACCESS_KEY=<browserstack-access-key>
  ```

  * For Windows Powershell:
  ```
  $env:BROWSERSTACK_USERNAME=<browserstack-username>
  $env:BROWSERSTACK_ACCESS_KEY=<browserstack-access-key>
  ```

## Integration
* Refer to our [cypress documentation](https://www.browserstack.com/docs/automate/cypress/integrate-your-test) for integration.

## Run tests
* Command - `browserstack-cypress run --sync`