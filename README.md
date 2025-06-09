# GitHub Advanced Security Exam

## 📝 Structure

- You will have to answer 70 questions, all of which will be multiple-choice questions.


- For some questions, there will be only one correct answer, while for others, there may be multiple correct answers.
  You will have 2 hours to complete the exam, which should be sufficient to answer all 70 questions.


- In terms of difficulty level, it is intermediate. meaning it is not so tough.  
  While some questions may be challenging, overall, it is not overly difficult.  
  **However, some questions may be confusing**, so it’s important to have a good understanding of the overall exam
  structure.
  With a solid grasp of the exam format, you should be well-prepared.

## 📚 Exercises

1. Read the [Documentation](https://docs.github.com/en/code-security)

2. Go through [Microsoft Training](https://learn.microsoft.com/en-us/training/paths/github-advanced-security)

3. Watch [YouTube Video](https://www.youtube.com/watch?v=-6EdqFcPmfI) *(Optional)*

4. Complete GitHub Security Challenge
    1. [Introduction to Repository Management](https://github.com/skills/introduction-to-repository-management)
    2. [Secure Your Repository's Supply Chain](https://github.com/skills/secure-repository-supply-chain)
    3. [Introduction to Secret Scanning](https://github.com/skills/introduction-to-secret-scanning)

5. Do the [Quiz](https://ghcertified.com/questions/advanced_security/question-001/)

## 📖 Scope

- Differentiate the security features that come automatically for open source projects, and what features are available
  when GHAS is paired with GHEC or GHES
- Describe the features and benefits of Security Overview
- Describe the differences between secret scanning and code scanning
- Describe how secret scanning, code scanning, and Dependabot create a more secure software development life cycle
- Contrast a security scenario with isolated security review and an advanced scenario, with security integrated into
  each step of the software development life cycle

- Describe how vulnerable dependencies are identified (by looking at the manifest files and comparing with databases of
  known vulnerabilities)
- Choose how to act on alerts from GHAS
- Explain the implications of ignoring an alert
- Explain the role of a developer when they discover a security alert
- Describe the differences in access management to view alerts for different security features
- Identify where to use Dependabot alerts in the software development lifecycle

- Describe secret scanning
- Describe push protection
- Describe validity checks
- Contrast secret scanning availability for public and private repositories
- Enable secret scanning for private repositories
- Pick an appropriate response to a secret scanning alert
- Determine if an alert is generated for a given secret, pattern, or service provider
- Determine if a given user role will see secret scanning alerts and how they will be notified\

- Configure the recipients of a secret scanning alert (also includes how to provide access to members and teams other
  than admins)
- Exclude certain files from being scanned for secrets
- Enable custom secret scanning for a repository

- Define the dependency graph
- Describe how the dependency graph is generated
- Describe what a Software Bill of Materials (SBOM) is, and the SBOM format used by GitHub
- Define a dependency vulnerability
- Describe Dependabot alerts
- Describe Dependabot security updates
- Describe Dependency Review
- Describe how alerts are generated for vulnerable dependencies (driven from the dependency graph, sourced from the
  GitHub Advisory Database)
- Describe the difference between Dependabot and Dependency Review

- Identify the default settings for Dependabot alerts in public and private repositories
- Identify the permissions and roles required to enable Dependabot alerts
- Identify the permissions and roles required to view Dependabot alerts
- Enable Dependabot alerts for private repositories
- Enable Dependabot alerts for organizations
- Create a valid Dependabot configuration file to group security updates
- Create a Dependabot Rule to auto-dismiss low severity alerts until a patch is available
- Create a Dependency Review GitHub Actions workflow
- Configure license checks and custom severity thresholds in a Dependency Review workflow
- Configure notifications for vulnerable dependencies

- Identify a vulnerable dependency from a Dependabot alert
- Identify vulnerable dependencies from a pull request
- Enable Dependabot security updates
- Remedy a vulnerability from a Dependabot alert in the Security tab (could include updating or removing the dependency)
- Remedy a vulnerability from a Dependabot alert in the context of a pull request (could include updating or removing
  the dependency)
- Take action on any Dependabot alerts by testing and merging pull requests

- Enable code scanning for use with a third-party analysis
- Contrast the steps for using CodeQL versus third party analysis when enabling code scanning
- Contrast how to implement CodeQL analysis in a GitHub Actions workflow versus a third-party CI tool
- Upload 3rd party SARIF results via the SARIF endpoint

- Describe how code scanning fits in the software development life cycle
- Contrast the frequency of code scanning workflows (scheduled versus triggered by events)
- Choose a triggering event for a given development pattern (for example, in a pull request and for specific files)
- Edit the default template for Actions workflow to fit an active, open source, production repository
- Describe how to view code scanning results from CodeQL analysis
- Troubleshoot a failing code scanning workflow using CodeQL, including creating or changing a custom configuration in
  the CodeQL workflow
- Follow the data flow through code using the show paths experience
- Explain the reason for a code scanning alert given documentation linked from the alert
- Determine if and why a code scanning alert needs to be dismissed
- Describe potential shortfalls in CodeQL via model of compilation and language support
- Explain the purpose of defining a SARIF category


- Use a Common Vulnerabilities and Exposures (CVE) and Common Weakness Enumeration (CWE) to describe a GitHub Advanced
  Security alert and list potential remediation
- Describe the decision-making process for closing and dismissing security alerts (documenting the dismissal, making a
  decision based on data)
- Describe the default CodeQL query suites
- Describe how CodeQL analyzes code and produces results, including differences between compiled and interpreted
  language
- Determine the roles and responsibilities of development and security teams on a software development workflow
- Describe how the severity threshold for code scanning pull request status checks can be changed
- Explain how filters and sorting can be used to prioritize secret scanning remediation (validity:active)
- Explain how CodeQL & Dependency Review workflows can be enforced with Repository Rulesets
- Describe how code scanning can be configured to identify and remediate vulnerabilities earlier (scanning upon pull
  request)
- Describe how secret scanning can be configured to identify and remediate vulnerabilities earlier (enabling push
  protection)
- Describe how dependency analysis can be configured to identify and remediate vulnerabilities earlier (enable
  dependency review to scan upon pull request)