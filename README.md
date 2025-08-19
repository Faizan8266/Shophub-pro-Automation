# ShopHub Pro – Selenium WebDriver + Cucumber (BDD) Framework

Ready-to-run UI automation for login on https://bugbash.syook.com/ using Java 17, Maven, Selenium 4, Cucumber 7, TestNG, and ExtentReports.

## Run
```bash
mvn clean test
```
Options:
- Headless: `mvn clean test -Dheadless=true`
- Browser: `mvn clean test -Dbrowser=firefox`
- Credentials override: `-Dapp.username=user@example.com -Dapp.password=user123`

## Reports
- Cucumber HTML: `target/cucumber-reports.html`
- Extent: `target/extent/extent.html`
