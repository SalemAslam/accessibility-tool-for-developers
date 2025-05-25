# Web Accessibility GitHub Tool for Developers

**Automating Accessibility Reviews in GitHub Pull Requests using SWE-Agent**

Note: This repository is currently in active development. The codebase is incomplete and may undergo significant changes.

## 🌟 Overview

This repository hosts an automated tool in GitHub aimed at enhancing the accessibility of web projects by performing automated reviews directly within GitHub pull requests. Built upon **GitHub Actions** and the powerful **SWE-Agent**(https://github.com/princeton-nlp/SWE-agent), our solution helps developers quickly identify and address accessibility issues, streamlining compliance and inclusivity in the development process.

**Theme:**
*“Access for All: Building AI-Powered Tools to Make the Web Inclusive”*

## 🚀 Objective

Develop an AI-powered GitHub Pull Request (PR) Accessibility Tool designed specifically for web developers, focusing on enhancing accessibility compliance, improving code quality, and reducing manual review efforts.

## 💡 Why Accessibility Matters

* Ensures inclusivity by design.
* Meets legal and compliance standards.
* Enhances developer productivity and reduces manual review times.

## 🧑‍💻 Key Features

* **Automated Accessibility Review**: Triggered via GitHub workflows upon PR creation.
* **Direct PR Comments**: Automatically generates comments on the pull request highlighting accessibility issues and suggestions.
* **Context-Aware Analysis**: Utilizes the robust SWE-Agent to understand the entire codebase contextually, significantly surpassing standard code-assist tools.
* **Customizable and Extendable**: Easily modify prompts, include specific file extensions (`.html`, `.css`), and restrict directories using `.llmignore`.


## 📸 Workflow Diagram

The following diagram illustrates the complete workflow and implementation details of the Accessibility PR Tool using GitHub Actions and SWE-Agent:

![Accessibility Tool Workflow](https://github.com/user-attachments/assets/95f293e7-191e-476f-a3d3-df665365c53c)


## ⚙️ Project Structure

```bash
accessibility-tool-for-developers
├── .github
├── scripts
│   ├── swe-agent
│   ├── comment-to-pr.py        # Script for commenting directly on GitHub PRs.
│   └── pre-analysis.py         # Script for preliminary accessibility analysis.
├── README.md                   # Project documentation
└── .gitignore
```

## 📌 Getting Started

### 🚀 How to Use

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/SalemAslam/accessibility-tool-for-developers.git
   cd accessibility-tool-for-developers
   ```

2. **Setup the Workflow:**

   * Integrate this repository into your existing GitHub workflow. The accessibility review automatically triggers whenever a new pull request is opened or an existing pull request is updated.

3. **Automatic Accessibility Review:**

   * Upon triggering, the tool will perform a detailed analysis of the changes made in the pull request and will automatically comment with accessibility recommendations directly on your GitHub pull request.

4. **Review Recommendations:**

   * Examine the comments provided by the tool, make necessary changes, and ensure enhanced accessibility and compliance.


## 🛠 SWE-Agent: Why Use It?

* Proven effectiveness in solving GitHub issues, benchmarked by SWE-Bench.
* Open-source with active community support and extensive customization capabilities.

## 🚩 Limitations & Future Improvements

* This repository is currently in active development. The codebase is incomplete and may undergo significant changes.
* Future updates planned include extensive testing across diverse codebases and integration with caching mechanisms for performance optimization.


