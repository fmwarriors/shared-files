# FMWarriors Shared Files Repository

A centralized repository for sharing files, resources, and code snippets across the FMWarriors organization. Similar to GitHub Gists but organized within our org for better collaboration and access control.

## 📁 Repository Structure

```
shared-files/
├── scripts/              # FileMaker scripts, automation tools
│   ├── filemaker/       # FileMaker-specific scripts
│   ├── python/          # Python utilities
│   └── shell/           # Bash and shell scripts
├── templates/           # Reusable templates
│   ├── filemaker/       # FM layouts, solutions
│   ├── documentation/   # Doc templates
│   └── configs/         # Configuration templates
├── snippets/            # Code snippets and examples
│   ├── filemaker/       # FM calculations, functions
│   ├── sql/             # SQL queries
│   ├── javascript/      # JS/web snippets
│   └── other/           # Other code samples
├── resources/           # Documentation, guides, assets
│   ├── guides/          # Tutorials and how-tos
│   ├── references/      # Reference materials
│   └── assets/          # Images, icons, etc.
├── solutions/           # Complete solutions (larger projects)
├── utilities/           # Standalone tools and utilities
└── archive/             # Deprecated or outdated files
```

## 🚀 How to Use This Repository

### Sharing a File

1. **Clone the repository** (if you haven't already):
   ```bash
   git clone https://github.com/FMWarriors/shared-files.git
   cd shared-files
   ```

2. **Create a branch** for your changes:
   ```bash
   git checkout -b add-my-file
   ```

3. **Add your file** to the appropriate folder

4. **Include a README** in your subfolder (if creating a new section):
   ```markdown
   ## File Name
   
   **Description:** Brief description of what this file does
   **Author:** Your name
   **Date:** YYYY-MM-DD
   **Dependencies:** Any requirements or prerequisites
   ```

5. **Commit and push**:
   ```bash
   git add .
   git commit -m "Add: [description of your file]"
   git push origin add-my-file
   ```

6. **Create a Pull Request** and let team members review before merging

### Downloading Files

- Browse the repository on GitHub directly
- Use GitHub's download feature for individual files
- Clone the entire repo and use what you need

## 📋 Contribution Guidelines

- **Organize files logically** - Use existing folders or create new ones with a clear purpose
- **Add descriptions** - Include a brief comment or README explaining what the file does
- **Version your files** - If uploading multiple versions, append a version number (e.g., `script-v1.0.fm`)
- **Keep it clean** - Remove or archive outdated files regularly
- **Respect licenses** - Only share files you have permission to share
- **Use clear naming** - Use descriptive filenames with proper extensions

## 🔒 Access & Permissions

- **Public files** - All files are visible to the public unless this repo is private
- **Organization members** - Can push changes (with appropriate branch protections)
- **Pull requests** - Recommended for any additions or modifications

## 📝 File Naming Convention

- Use **kebab-case** for file names: `my-script.fm`, `user-login-template.txt`
- Include the **date** for time-sensitive files: `backup-script-2025-01-15.fm`
- Include **version numbers** when applicable: `layout-builder-v2.3.fm`

## 🤝 Support

- Post issues or questions in the GitHub Issues section
- Use Pull Request discussions for file reviews
- Tag relevant team members with `@mention`

---

**Last Updated:** January 2025
**Repository Type:** Organization Shared Files
