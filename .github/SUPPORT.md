# NCC-ZER0 Support Guide

Thank you for using NCC-ZER0. Please follow these guidelines to get help or report issues effectively.

## 🛠 Getting Help

### 1. Documentation & Roadmap
Before reaching out, please check:
- [ROADMAP.md](ROADMAP.md) for current status and planned milestones.
- The `docs/` directory for specific component guides.

### 2. GitHub Issues
For technical bugs, feature requests, or performance regressions:
- **Search existing issues** to see if your problem has already been reported.
- **Open a new issue** using the provided templates.

### 3. Security Concerns
**Do not open public issues for security vulnerabilities.**
Please refer to our [SECURITY.md](SECURITY.md) for the private disclosure process and response timeline.

---

## 📋 Before Filing an Issue

To help us resolve your issue quickly, please ensure you have:

1. **Reproduced on `main`**: Verify the issue persists on the latest commit of the `main` branch.
2. **Checked Feature Flags**: Identify which flags are active.
3. **Isolated the Environment**: Note if you are running in a container, local Linux environment, or specific CI runner.

---

## 📝 Issue Requirements

When filing a bug report, please include:

- **Environment Details**:
  - OS Version (e.g., Ubuntu 22.04)
  - Rust version (`rustc --version`)
  - Commit SHA (`git rev-parse HEAD`)
- **Reproduction Steps**:
  - Exact commands used (e.g., `ncc chat`)
  - Relevant configuration snippets (redact any secrets/keys)
- **Logs & Output**:
  - Full error messages and stack traces.
  - If applicable, the output of `ncc memory stats`.

---
*Note: This project is maintained by the community. Response times may vary based on contributor availability.*
