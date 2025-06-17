# Contributing to Business Intelligence Laboratory - SPPU

📈 Thank you for considering contributing to the BI Lab repository! 📉

Your contributions are valuable in enhancing this resource for students learning about Business Intelligence, data warehousing, and data analytics. We encourage participation from everyone interested in these topics.

This document provides guidelines for contributing to this project.

## How Can I Contribute?

There are several ways you can contribute:

*   **🐞 Reporting Issues/Bugs:** If you find an error in an SQL script, a problem with a practical setup, a mistake in the documentation, or a bug in any provided code, please [open an issue](https://github.com/kunalPisolkar24/BI_Lab/issues) on GitHub.
    *   Clearly describe the issue.
    *   Include steps to reproduce it if it's a technical bug.
    *   Specify the practical number or file involved.
*   **✨ Suggesting Enhancements or New Examples:** If you have ideas for improving an existing practical (e.g., using a different tool, a more efficient ETL process, a new visualization technique) or suggesting a new relevant BI scenario, please [open an issue](https://github.com/kunalPisolkar24/BI_Lab/issues) to discuss it first.
*   **📝 Improving Documentation:** If you find parts of the READMEs (main or for individual practicals) unclear, or think they could be improved with more detail or better explanations, feel free to suggest changes or submit a pull request.
*   **🛠️ Code/Script Contributions (Pull Requests):** If you've fixed an issue, implemented an enhancement, or added new scripts/code related to the lab assignments, please submit a pull request!

## Making Code/Script Contributions (Pull Requests)

If you'd like to contribute code, SQL scripts, or other resources, please follow these general steps:

1.  **Fork the Repository:**
    Click the "Fork" button at the top right of the [BI_Lab repository page](https://github.com/kunalPisolkar24/BI_Lab). This creates your own copy of the project.

2.  **Clone Your Fork:**
    Clone your forked repository to your local machine:
    ```bash
    git clone https://github.com/YOUR_USERNAME/BI_Lab.git
    cd BI_Lab
    ```
    Replace `YOUR_USERNAME` with your actual GitHub username.

3.  **Create a New Branch:**
    Create a descriptive branch for your changes:
    ```bash
    # For a new feature, script, or example
    git checkout -b feature/your-descriptive-feature-name

    # For a fix or correction
    git checkout -b fix/brief-description-of-fix
    ```

4.  **Make Your Changes:**
    *   Implement your fix, feature, or improvement.
    *   Ensure your SQL scripts are well-commented and your code is clear.
    *   If you're working on a specific practical, make changes within the relevant directory (e.g., `Practical_1/`, `Practical_3_ROLAP/`).
    *   **Test your changes thoroughly.** For BI tasks, this might involve verifying data integrity after ETL, ensuring cube functionality, or checking the correctness of machine learning model outputs.

5.  **Commit Your Changes:**
    Write clear and concise commit messages:
    ```bash
    git add .
    git commit -m "feat: Add alternative ETL script using SSIS for Practical 2"
    # or
    git commit -m "fix: Correct dimension attribute in MOLAP cube script (Practical 3)"
    # or
    git commit -m "docs: Clarify data source setup for Practical 1"
    ```

6.  **Push to Your Fork:**
    Push your committed changes to your forked repository on GitHub:
    ```bash
    git push origin feature/your-descriptive-feature-name
    ```

7.  **Open a Pull Request (PR):**
    *   Go to the original `kunalPisolkar24/BI_Lab` repository on GitHub.
    *   You should see a prompt to "Compare & pull request" for your recently pushed branch. Click it.
    *   If not, go to the "Pull requests" tab and click "New pull request." Choose your fork and branch to compare with the original repository's `main` branch.
    *   **Fill out the PR template:**
        *   Provide a clear and descriptive title for your PR.
        *   In the description, explain the changes you've made and why they are beneficial.
        *   If your PR addresses an open issue, link to it using `Closes #issue_number`.

## Pull Request Guidelines

To help us review your PR efficiently, please ensure:

*   **Clear Purpose:** Your PR should address a specific issue or add a well-defined feature/improvement.
*   **Descriptive Title & Description:** Make it easy to understand your contribution.
*   **Working Scripts/Code:** Your contributions should execute correctly and achieve the intended results.
*   **Readability:** Write clean, well-commented SQL scripts and code. Follow the existing style of the project where possible.
*   **Focused Changes:** Keep PRs focused. If you have multiple unrelated changes, submit them as separate PRs.

## Style Guidelines

While there isn't a strict automated linter enforced for this lab repository:

*   Maintain a consistent style with the existing scripts and code.
*   Write clear, readable, and adequately commented SQL, Python, or other relevant code.
*   Use meaningful names for tables, columns, variables, and functions.
*   For SQL, consider standard formatting practices (e.g., capitalizing keywords).

## Questions or Discussions

If you're unsure about something or want to discuss a potential contribution before starting work, please feel free to [open an issue](https://github.com/kunalPisolkar24/BI_Lab/issues) and tag the repository maintainer (`@kunalPisolkar24`).

---

Thank you for contributing to the Business Intelligence Lab! Your efforts help create a valuable learning resource for data-driven decision-making.