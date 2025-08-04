# 🧾 Repo-Report

**Repo-Report** is a CLI tool that scans all GitHub repositories you have access to and generates a simple, readable configuration report. It gives you a quick snapshot of each repository’s settings and status — all in one place.

It’s useful for developers, maintainers, or anyone who wants an overview of **all their GitHub projects** without having to click through every repo manually.

---

## ⭐ Key Features (Default Output)

When you run `repo-report`, it checks every accessible GitHub repository and reports the following:

- ✅ **Issues Enabled** — Are GitHub Issues turned on?
- 🗂️ **Projects Enabled** — Are GitHub Projects turned on?
- 📜 **License Present** — Does the repository include a LICENSE file?
- 📖 **Wiki Enabled** — Is the GitHub Wiki feature turned on?
- 🔐 **Visibility** — Is the repository **public**, **private**, or **internal**?
- 🧪 **Has Actions** — Are GitHub Actions workflows present?
- 🧩 **Has Topics** — Does the repo have any tags or topics set?
- 🕒 **Last Push Date** — When was the last push made to the repository?
- 🧑‍🤝‍🧑 **Collaborators** — How many people have access to the repo?

> *Note: These are the default metrics. More options and filters may be added in future updates.*

---

## 🛠️ How It Works

1. Repo-report authenticates with GitHub using your personal access token (PAT).
2. It scans all repositories the token has access to — including personal, organizational, and collaborator repos.
3. It fetches metadata from GitHub’s API and compiles it into a structured, human-readable report.
4. Output can be viewed in your terminal or exported to a file (support coming soon).

This is great for:

- Auditing repos across an organization
- Spotting missing configuration details
- Keeping track of which repos are active or stale
- Quickly identifying which features are enabled or disabled

---

## 🚧 Coming Soon

- Export options (CSV, JSON)
- Support for advanced filtering (e.g. org-only, archived-only)
- Visual output formatting
- Summary dashboards

---

## 📬 Feedback

If you have suggestions or want to contribute, feel free to open an issue or pull request.

---

## 📄 License

MIT License
