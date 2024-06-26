# Issue Templates

<pre align="center">Make issue tracking clear and consistent with structured issue templates for your contributors.</pre>

## Introduction

**Background**: Implementing issue templates in GitHub projects standardizes and clarifies the submission of bug reports, feature requests, and other types of issues. It guides contributors in providing essential details, helping developers understand and address issues more efficiently.

**Use Cases**:
- Enhancing clarity and consistency in issue or feature reporting.
- Streamlining the process for contributors to report bugs or request features so that a wide audience can switch between issues easily.
- Improving developers' understanding of issues for quicker resolution.

---

## Prerequisites

* Access to a GitHub repository with administrative permissions.
* Basic knowledge of Markdown for editing GitHub templates.

---

## Quick Start

**Bug Reports:**
- **[⬇️ Bug Report Template (Markdown)](bug-reports/bug_report)**
- **[⬇️ Bug Report Template (GitHub Form)](bug-reports/bug_report.yml)**

**New Features:**
- **[⬇️ New Feature Template (Markdown)](features/new_feature)**
- **[⬇️ New Feature Template (GitHub Form)](features/new_feature.yml)**

**[📔 GitHub Issue Template Documentation](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/about-issue-and-pull-request-templates)**

---

## Step-by-Step Guide

1. **Team Discussion**: Consult with your team about using GitHub issue templates. Reach a consensus on adopting this practice. Our suggested templates request the below information - see justification below. 

   - Bug Reports:
     1. **Checked for duplicates**: This section asks the contributor to verify if the issue has already been reported. It helps prevent duplication and streamlines the issue management process.
     2. **Describe the bug**: The contributor provides a clear, concise description of the bug. This section is critical for developers to understand the issue's nature and impact.
     3. **What did you expect?**: Understanding the contributor's expectations clarifies the disparity between expected and actual behavior, helping to pinpoint the issue more accurately.
     4. **Reproducible steps**: Step-by-step reproduction instructions are crucial for developers to replicate the issue, diagnose the problem, and test solutions effectively.
     5. **What is your environment?**: Providing details about the hardware, operating system, or other contextual factors helps in identifying if the bug is environment-specific and aids in troubleshooting.
   - New Features:
     1. **Checked for duplicates**: This section ensures the contributor has checked for existing feature requests, avoiding redundancy and streamlining the development process.
     2. **Alternatives considered**: Encourages the contributor to consider and document alternative solutions. This insight can guide the evaluation of the feature's necessity.
     3. **Related problems**: This helps identify if the feature request is a solution to an existing problem, adding context and justification for the request.
     4. **Describe the feature request**: A clear description from the contributor about the proposed feature. This clarity is essential for understanding the feature's purpose and scope.

2. **Setting Up Issue Templates**:
   - Create a `.github/ISSUE_TEMPLATE` folder in your repository.
   - Add [Bug Report](bug-reports/bug_report) and [New Feature](features/new_feature) templates to this folder.
   - For a form-like experience, use [GitHub Issue Forms](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository#creating-issue-forms). 
     - Place YAML formatted templates, like [Bug Report Form](bug-reports/bug_report.yml) and [New Feature Form](features/new_feature.yml), in the same folder.

3. **Commit and Use Templates**:
   - Commit these files to the `main` branch.
   - New issues in your repository will now offer these templates for contributors to fill.

---

## Frequently Asked Questions (FAQ)

- Q: Why are issue templates important in GitHub projects?
- A: They ensure that all necessary information is provided, leading to more effective issue tracking and resolution.

---

## Credits 

**Authorship**:
- [Rishi Verma](https://www.github.com/riverma)

**Acknowledgements**:
* GitHub for providing documentation for issue templates.

---

## Feedback and Contributions

Feedback and contributions are welcome to enhance these guidelines. See our [contribution guidelines](https://nasa-ammos.github.io/slim/docs/contribute/contributing/).
