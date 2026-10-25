# Vehicle Data Test Automation

A Selenium/TestNG framework that reads vehicle-registration fixtures, searches a vehicle-information website, and compares displayed details with expected results.

## What is implemented

Page objects, data providers, reusable browser actions, reporting, and screenshot utilities.

## Build and run

Use JDK 23 or newer and Maven from the repository root. The Maven file is the source of truth for any lower compiler target.

~~~sh
mvn -B test-compile
~~~

## Scope and limitations

Live tests require a supported browser, compatible drivers, and access to the target website. The sample registration files are in src/test/resources/testData. Confirm the path and fixtures before running testng.xml. Compilation does not verify live website behaviour.

## Verification

See [verification notes](docs/verification.md) for the exact checks performed. A compile result is not an end-to-end test result.

Local configuration, credentials, browser drivers, generated reports, IDE metadata, and personal data are excluded from new source commits. Existing source notices are retained.