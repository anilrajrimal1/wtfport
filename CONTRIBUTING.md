# Contributing to wtfport

Thank you for your interest in contributing to `wtfport`! We welcome contributions from the community to help improve this lightweight port-checking tool. Whether you're fixing bugs, adding features, or improving documentation, your efforts help make `wtfport` better for everyone.

## Getting Started

Before contributing, please take a moment to review this guide to ensure a smooth collaboration process.

### Prerequisites
- **Python**: Version 3.9 or higher
- **Dependencies**: `psutil` (install via `pip install psutil`)
- **Git**: For cloning and managing the repository
- A GitHub account to submit issues or pull requests

### Setting Up the Project
1. Fork the repository on GitHub.
2. Clone your fork:
   ```bash
   git clone https://github.com/your-username/wtfport.git
   cd wtfport
   ```
3. Copy requirements:
   ```bash
   cp requirements-dev.txt requirements.txt
   ```
4. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: venv\Scripts\activate
   ```
5. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## How to Contribute

We follow a standard GitHub workflow for contributions. Here’s how you can get involved:

### 1. Report Bugs or Suggest Features
- Check the [GitHub Issues page](https://github.com/anilrajrimal1/wtfport/issues) to ensure the bug or feature hasn’t already been reported.
- Open a new issue with a clear title and description, including:
  - For bugs: Steps to reproduce, expected behavior, and actual behavior.
  - For features: A detailed explanation of the proposed feature and its benefits.

### 2. Submit Code Changes
1. Create a new branch for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```
2. Make your changes, ensuring code quality and adherence to the project’s style.
3. Write or update tests to cover your changes (if applicable).
4. Commit your changes with a descriptive message:
   ```bash
   git commit -m "fear(feature-name): your feature description"
   ```
5. Push your branch to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```
6. Open a Pull Request (PR) on the main repository, referencing any related issues.

### 3. Testing
- Test your changes locally to ensure they don’t break existing functionality.

## Code of Conduct

We strive to maintain a welcoming and inclusive community. Please adhere to our [Code of Conduct](CODE_OF_CONDUCT.md) in all interactions, including issues, pull requests, and discussions.

## Recognition

All contributors are acknowledged in the [README.md](README.md) under the Acknowledgments section. Your contributions, whether code, documentation, or ideas, are greatly appreciated!

## Questions?

If you have questions or need help, feel free to:
- Open an issue on the [GitHub Issues page](https://github.com/anilrajrimal1/wtfport/issues).
- Reach out to the maintainers via the project’s discussion board (if available).

Thank you for contributing to `wtfport`! Let’s make port debugging awesome together! 🐞
```