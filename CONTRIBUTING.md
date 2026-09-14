# Contributing to FMWarriors Shared Files

Thank you for wanting to contribute to the FMWarriors shared repository! This guide will help you add your files in a way that's organized and easy for everyone to find.

## Before You Start

1. Make sure you have access to the FMWarriors organization on GitHub
2. Clone the repository locally: `git clone https://github.com/FMWarriors/shared-files.git`
3. Ensure you have write permissions to the repository

## Step-by-Step: Adding Your File

### 1. Create a Feature Branch

```bash
git checkout -b add/your-descriptive-branch-name
```

**Branch naming conventions:**
- `add/` - for new files or features
- `update/` - for improvements to existing files
- `fix/` - for bug fixes or corrections
- `docs/` - for documentation updates

### 2. Choose the Right Folder

| Folder | Use for |
|--------|---------|
| `scripts/` | Automated scripts, automation tools, executables |
| `templates/` | Reusable templates and boilerplates |
| `snippets/` | Small code samples and examples |
| `resources/` | Guides, documentation, and reference materials |
| `solutions/` | Complete, self-contained projects |
| `utilities/` | Standalone tools and helpers |
| `archive/` | Old or deprecated files |

### 3. Add Your File(s)

Place your file in the appropriate subfolder. Create a new subfolder if needed.

### 4. Add Context

Create or update a **README.md** in your subfolder with:

```markdown
# [Your File/Project Name]

## Description
Brief explanation of what this file does and its purpose.

## Details
- **Author:** Your Name (@github-handle)
- **Last Updated:** YYYY-MM-DD
- **Version:** X.Y.Z
- **License:** [MIT/Apache/GPL/Other/None]

## Requirements
- Requirement 1
- Requirement 2

## Usage
```
Example code or instructions
```

## Notes
Any additional information, caveats, or considerations.

## Related Files
- Link to related files
```

### 5. Commit Your Changes

Write clear, descriptive commit messages:

```bash
git add .
git commit -m "Add: FileMaker authentication template - v1.0"
```

**Commit message format:**
- `Add: [description]` - for new files
- `Update: [description]` - for modifications
- `Fix: [description]` - for corrections
- `Docs: [description]` - for documentation

### 6. Push and Create a Pull Request

```bash
git push origin add/your-descriptive-branch-name
```

Then create a Pull Request on GitHub with:
- Clear title: "Add FileMaker authentication template"
- Description of what you're adding
- Any relevant context or links

### 7. Wait for Review

A team member will review your contribution. Be ready to make adjustments if requested.

## File Guidelines

### ✅ Do's
- Use clear, descriptive filenames
- Include file headers/comments explaining the purpose
- Add dependencies and requirements
- Use consistent formatting and style
- Keep files focused and single-purpose
- Document your code/scripts

### ❌ Don'ts
- Don't include personal credentials or sensitive data
- Don't upload extremely large files (>50MB) without discussion
- Don't commit node_modules, .env files, or other generated artifacts
- Don't overwrite others' files without discussion
- Don't include absolute paths in documentation

## Naming Conventions

**Files:**
```
script-name-v1.0.fm          # FileMaker file with version
calculation-example.txt      # Text snippet
helper-functions.js          # JavaScript file
config-template.json         # Configuration template
```

**Folders:**
```
use-kebab-case-for-folders/
include-context-in-folder-names/
```

## Questions?

- Open an Issue with your question
- Tag `@FMWarriors/maintainers` for help
- Check existing issues for similar questions

## License

By contributing to this repository, you agree that your contributions can be shared with the FMWarriors organization members under the repository's license terms.

---

Thank you for contributing! 🎉
