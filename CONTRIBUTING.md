# Contributing to Awesome CodeGen

Thank you for your interest in contributing to Awesome CodeGen! This guide will help you add tools, platforms, and resources to this curated list.

## Table of Contents

- [How to Contribute](#how-to-contribute)
- [Submission Guidelines](#submission-guidelines)
- [Quality Standards](#quality-standards)
- [Categories](#categories)
- [Pull Request Process](#pull-request-process)

## How to Contribute

There are several ways to contribute:

1. **Add a new tool** - Submit a tool, platform, or service
2. **Update existing entries** - Fix broken links, update descriptions, or add missing information
3. **Suggest new categories** - Propose new categories for better organization
4. **Report issues** - Flag outdated, broken, or incorrect entries

## Submission Guidelines

### Before Submitting

- **Search existing entries** - Make sure the tool isn't already listed
- **Verify the tool is active** - The tool should be actively maintained (updated within the last 12 months)
- **Test the URL** - Ensure the link works and points to the correct resource
- **Confirm it fits the scope** - The tool must use AI or automation for code generation

### What to Include

Each entry should follow this format:

```markdown
- [Tool Name](https://example.com) - Brief, clear description of what the tool does (one sentence preferred).
```

**Example:**
```markdown
- [Cursor](https://cursor.com) - AI-first code editor (VS Code fork) with multi-file editing, agent mode, and deep codebase understanding.
```

### Writing Good Descriptions

- Keep it concise (ideally one sentence, max two)
- Focus on what makes the tool unique
- Mention key features or technology
- Avoid marketing language and superlatives
- Don't use phrases like "the best," "amazing," or "revolutionary"
- Be factual and informative

**Good descriptions:**
- "AI-powered code completion with support for 40+ languages"
- "Converts Figma designs into React components with Tailwind CSS"
- "Open-source CLI tool for generating REST APIs from database schemas"

**Avoid:**
- "The world's best AI coding assistant"
- "Amazing tool that will revolutionize your workflow"
- "Incredible platform for building apps"

## Quality Standards

### Required Criteria

To be included, a tool must meet ALL of the following:

1. **Actively Maintained** - Updated within the last 12 months
2. **Working URL** - Link must be accessible and correct
3. **CodeGen Focus** - Must use AI/automation for code generation
4. **Production-Ready** - Not a prototype or abandoned project
5. **Accessible** - Publicly available (free, freemium, or paid)

### Nice to Have

- Open-source or has a free tier
- Well-documented
- Active community or user base
- Unique features or approach

### Not Accepted

- Dead or abandoned projects
- Broken links
- Tools without code generation features
- Duplicate entries
- Non-English tools (unless they have English documentation)
- Personal projects without public releases

## Categories

Current categories include:

- **Full-Stack AI App Builders** - Complete app generation from prompts
- **AI Code Editors & IDEs** - Full editors with integrated AI
- **AI Coding Assistants** - IDE extensions and plugins
- **CLI & Terminal Tools** - Command-line AI coding tools
- **Frontend & UI Code Generators** - UI and component generation
- **Backend & API Generators** - Server-side and API generation
- **Mobile App Generators** - Mobile application builders
- **Database & Schema Tools** - Database design and schema generation
- **Design-to-Code Tools** - Convert designs to code
- **Testing & Quality Tools** - AI-powered testing tools
- **Documentation Generators** - Automated documentation
- **No-Code/Low-Code Platforms** - Visual development platforms
- **Cloud Platforms & Deployment** - BaaS and deployment with codegen
- **Snippet Management & Utilities** - Code snippet tools
- **GraphQL Tools** - GraphQL-specific generators

### Suggesting New Categories

If you believe a new category is needed:

1. Ensure you have at least **3 tools** that fit the category
2. Verify the category is distinct from existing ones
3. Propose a clear, descriptive category name
4. Include justification in your pull request

## Pull Request Process

### Step 1: Fork & Clone

```bash
# Fork the repository on GitHub
# Then clone your fork
git clone https://github.com/YOUR_USERNAME/codegen-awesome-list.git
cd codegen-awesome-list
```

### Step 2: Create a Branch

```bash
git checkout -b add-tool-name
```

### Step 3: Make Your Changes

1. Open `README.md`
2. Find the appropriate category
3. Add your entry in alphabetical order (if applicable)
4. Follow the format exactly

### Step 4: Commit Your Changes

```bash
git add README.md
git commit -m "Add [Tool Name] to [Category]"
```

Use clear commit messages:
- ✅ "Add Cursor to AI Code Editors"
- ✅ "Update Bolt.new description"
- ✅ "Fix broken link for Replit"
- ❌ "Update README"
- ❌ "Add stuff"

### Step 5: Push and Create PR

```bash
git push origin add-tool-name
```

Then create a pull request on GitHub with:

- **Title**: Clear description (e.g., "Add Cursor to AI Code Editors")
- **Description**:
  - Brief explanation of the tool
  - Why it should be included
  - Confirmation that it meets the quality standards
  - Any additional context

### Step 6: Respond to Feedback

- Be patient - reviews may take a few days
- Respond to any questions or requested changes
- Make updates if needed

## Style Guide

### Capitalization

- Tool names: Use official capitalization (e.g., "GitHub Copilot", "v0", "Bolt.new")
- Categories: Title Case (e.g., "AI Code Editors & IDEs")
- Descriptions: Sentence case

### Links

- Use HTTPS when available
- Link to the main product page, not blog posts or documentation
- Avoid referral links or tracking parameters
- Remove trailing slashes unless necessary

### Formatting

- Use standard Markdown
- No HTML unless absolutely necessary
- Maintain consistent spacing (see existing format)
- One line break between entries

## Questions?

If you have questions about contributing:

1. Check if it's already answered in this guide
2. Look at existing entries for examples
3. Open an issue for discussion
4. Reach out to the maintainers

## Code of Conduct

- Be respectful and constructive
- Focus on the quality and accuracy of information
- No spam or self-promotion without merit
- Respect the maintainers' decisions

## Thank You!

Your contributions help make this list valuable for the developer community. We appreciate your time and effort!
