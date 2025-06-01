# End-to-End-Selenium-Test-Automation-Framework-Java-TestNG-Maven-Cucumber

✅ Key Features
🧱 Framework Architecture
The framework follows the Page Object Model (POM), abstracting all locators and UI actions into dedicated page classes for maintainability and scalability. Object creation is encapsulated within these classes, ensuring clean and modular test logic. A Base Test class manages centralized setup/teardown processes, including browser configuration, WebDriver initialization, and loading of global properties.

🧪 Test Strategy & Execution
Tests are executed through a single TestNG runner, providing unified control. Test categorization is implemented using TestNG groups (e.g., smoke, regression, sanity), defined within testng.xml for selective execution. Custom TestNG Listeners automatically capture screenshots on failure and log test details. A retry analyzer mechanism is in place to automatically rerun flaky or intermittent failures.

📊 Reporting
Integrated with Extent Reports, the framework generates rich HTML reports that include test logs, pass/fail status, and screenshots, offering a complete view of the execution cycle.

📂 Data-Driven Testing
Supports parameterized testing using TestNG DataProviders, leveraging HashMap and external JSON file readers to inject dynamic test data at runtime.

⚙️ Parallel Execution & Thread Safety
Enables parallel execution by using thread-safe WebDriver management and configuring test concurrency in testng.xml. This improves execution speed while maintaining test independence.

🔧 Maven Integration
Tests can be triggered via Maven commands, with TestNG plugin integration. The framework supports runtime parameterization, allowing test data or environment configs to be passed dynamically during execution.

🧪 BDD with Cucumber
Includes a Cucumber wrapper alongside TestNG for hybrid support. Feature files and step definitions are neatly organized to support BDD-style testing, enhancing readability and collaboration.

🛠️ CI/CD Integration
Fully integrated with Jenkins, supporting parameterized pipelines, scheduled jobs, and environment-specific test executions to enable automated regression runs.

📂 Tech Stack
Language: Java

Frameworks: Selenium WebDriver, TestNG, Cucumber

Build Tool: Maven

CI/CD: Jenkins

Reporting: Extent Reports

Data Sources: JSON, HashMap

Version Control: Git + GitHub
