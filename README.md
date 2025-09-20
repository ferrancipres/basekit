<!-- ======================================================================
README TEMPLATE — FRONTEND BOILERPLATE
Scope: HTML + CSS + Prettier
----------------------------------------------------------------------
WARNINGS
- Avoid placeholders. If Demo/Changelog not ready, write "Not available".
- Add live-server as a dev dependency (not global).
- TypeScript is optional. Add tsconfig.json if really needed.
- Do not duplicate badges and plain text for the same info.
- If Changelog will not be updated, use GitHub Releases instead.
- Be careful when updating the Project Status once the project is finished.
- Always include references to the original project or platform.

====================================================================== -->

<p align="center">
  <img src="https://img.shields.io/badge/README-.md-blue?style=flat&labelColor=2f2f2f&logo=markdown&logoColor=white" alt="README badge" width="170">
</p

## 📌 Quick Access

- [README.md](README.md)
- [LICENSE](LICENSE)
- [config/.gitignore](config/.gitignore)
- [config/.prettierrc.json](config/.prettierrc.json)
- [config/.prettierignore](config/.prettierignore)
- [config/.gitattributes](config/.gitattributes)
- [config/.editorconfig](config/.editorconfig)
- [src/](src/)

---

📋 Table of Contents

1. [Description](#description)
2. [Demo](#demo)
3. [Goals](#goals)
4. [Technologies](#technologies)
5. [Prerequisites](#prerequisites)
6. [Installation & Usage](#installation--usage)
7. [Project Structure](#project-structure)
8. [Useful Scripts](#useful-scripts)
9. [Features](#features)
10. [Environment Variables](#environment-variables)
11. [Known Issues](#known-issues)
12. [Roadmap](#roadmap)
13. [Project Status](#project-status)
14. [Contributing](#contributing)
15. [License](#license)
16. [Contact](#contact)
17. [Credits](#credits)
18. [Changelog](#changelog)

---

#### Description

Project Name is a minimal boilerplate for static websites using HTML + CSS, with Prettier for code formatting.

---

#### Demo

Screenshot or live example of the app:

[🔗 Live Demo](https://your-deploy-link.com)
_Not yet available_

---

#### Goals

- Provide a professional starter template.
- Maintain code quality via **Prettier**.
- Document the project with a clean README.

---

#### Technologies

- HTML5
- CSS3
- Prettier

---

#### Prerequisites

- Git
- VSCode with extensions:
  - Prettier
  - Live Server

---

#### Installation & Usage

```sh
# Clone the repository

git clone https://github.com/<user>/<repo>.git
cd <repo>
```

**📝 Notes**

- Open `src/index.html` in your browser or run with **Live Server** in VSCode.

---

#### Project Structure*

```sh
project-name/                       # Root directory of the project
├─ .github/                         # GitHub-specific configurations and templates
│  └─ ISSUE_TEMPLATE/               # Directory containing issue templates
│     └─ bug_report.md              # Template for reporting bugs (predefined structure)
│     └─ feature_request.md         # Template for suggesting new features or improvements
│  └─ CODEOWNERS                    # Defines repository code owners who must review changes
│  └─ FUNDING.yml                   # Configures sponsor links (GitHub Sponsors, BuyMeACoffee, etc.)
│  └─ PULL_REQUEST_TEMPLATE.md      # Template for standardizing Pull Requests
├─ .vscode/                         # Visual Studio Code project-specific settings
│  └─ settings.json                 # VSCode preferences (formatting, extensions, editor rules)
├─ config/                          # Project configuration files
│  └─ .editorconfig                 # Enforces consistent coding style across different editors
│  └─ .gitignore                    # Defines which files/folders Git should ignore
│  └─ .gitattributes                # Normalizes line endings and marks binary files
│  └─ .prettierrc.json              # Prettier configuration file (code formatting rules)
│  └─ .prettierignore               # Files/folders excluded from Prettier formatting
├─ img/                             # Folder for image assets used in the project
├─ src/                             # Source code directory
│  └─ index.html                    # Main HTML entry file (project entry point)
│  └─ styles.css                    # Base CSS stylesheet for styling
├─ .degitignore                     # Defines which files/folders Git should ignore
├─ LICENSE                          # License file specifying usage terms (e.g., MIT)
├─ README.md                        # Main documentation file with project description and usage
└─ SECURITY.md                      # Main documentation file with project security

```

---

#### Useful Scripts

```bash
npm init -y
npm install -D prettier
npx prettier --write .

```

---

#### Features

- ✅ Minimal, no dependencies
- ✅ Prettier formatting included
- ✅ Clear modular structure (`src/`, `img/`, `.vscode/`)
- 🚧 Pending: UI framework integration (React/Tailwind)

---

#### Roadmap

- [ ] Add JavaScript support (optional)
- [ ] Add deployment with GitHub Pages
- [ ] Extend styles with a CSS framework

---

#### Project Status

Version: **0.1.0-beta**

<p>
  <img src="https://img.shields.io/badge/version-0.1.0--beta-orange" alt="version">
</p>

Status: In progress

<p>
  <img src="https://img.shields.io/badge/status-in%20progress-yellow" alt="status">
</p>

---

#### Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'feat: add feature'`)
4. Push the branch (`git push origin feature/your-feature`)
5. Open a **Pull Request**

⚠️ Guidelines: Conventional Commits + small, well-documented PRs.

---

#### License

This project is licensed under the MIT License. <br>
See [LICENSE](./LICENSE) for details.

<p>
  <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="license">
</p>

---

#### Contact

- GitHub: [ferran-cipres](https://github.com/ferran-cipres)
- LinkedIn: [Ferran Ciprés](https://www.linkedin.com/in/ferrancipres/)
- Email: ferrancipres@gmail.com

---

#### Credits

- [FreeCodeCamp Guide](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/?utm_source=chatgpt.com)
- Adapted by **Ferran Ciprés**

---

#### Changelog
All notable changes to this project will be documented here.
[1.0.0] - 2025-09-20

- Initial release of html-css-template
- Base project structure (src/, img/, .vscode/, config/)
- Prettier configuration (.prettierrc.json, .prettierignore)
- Git settings (.gitignore, .gitattributes)
- Editor settings (.editorconfig)
- Documentation (README.md)
- License (MIT)
- GitHub templates for Issues and Pull Requests
