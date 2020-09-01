# Karate DSL samples for UI funtional/browser based testing
## How to run the samples test in Headless mode
- `java -jar karate-0.9.6.jar tests/test-headless.feature`
## How to run the samples test in non-Headless mode
- `java -jar karate-0.9.6.jar tests/test.feature`

## How to view tests results
- after running the tests there will be a `target` folder created with test reports
- open the file `target/surefire-reports/karate-summary.html` in broswer to see the test results
![Karate Tests Report](/karate-tests-report.gif)