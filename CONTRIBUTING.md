# Contributing to Awesome AI Coding

Thank you for your interest in contributing to this awesome list! This document provides guidelines to help make the contribution process smooth and effective.

## Table of Contents

- [How to Contribute](#how-to-contribute)
- [Submission Guidelines](#submission-guidelines)
- [Quality Standards](#quality-standards)
- [Pull Request Process](#pull-request-process)
- [Content Guidelines](#content-guidelines)
- [Formatting Rules](#formatting-rules)

## How to Contribute

There are several ways you can contribute:

1. **Add a new tool/resource** - Submit tools that fit the quality standards
2. **Update existing entries** - Fix broken links, update descriptions, or add missing information
3. **Improve organization** - Suggest better categorization or structure
4. **Fix typos/errors** - Help maintain quality documentation
5. **Add new categories** - Propose new sections if there's sufficient content

## Submission Guidelines

### Before Submitting

- **Search first**: Check if the tool is already listed
- **Relevance**: Ensure the tool is related to AI-assisted coding
- **Quality**: The tool should be well-maintained and functional
- **Availability**: Tools should be publicly accessible (open-source, freemium, or commercial with free trials)

### What to Include

Each submission should have:

1. **Name** - The official name of the tool/resource
2. **Link** - A working URL to the official website or repository
3. **Description** - A concise (one-sentence) description of what it does
4. **Category** - Place it in the appropriate section

### What NOT to Submit

- Tools that are no longer maintained (abandoned for 2+ years)
- Paid-only tools without free trials or tier
- Tools that are not AI-powered or AI-related
- Duplicate entries
- Personal projects without significant adoption or unique features
- Promotional content without real value
- Tools requiring invasive permissions or with security concerns

## Quality Standards

### For Tools & Software

✅ **Include if:**
- Actively maintained (updates within the last year)
- Has clear documentation or README
- Serves a specific purpose in AI coding workflow
- Open-source OR commercial with free tier/trial
- Has a reasonable user base or unique innovative features
- Works as advertised

❌ **Exclude if:**
- Abandoned or unmaintained
- Closed-source without free access
- Primarily promotional or marketing material
- Low quality or unreliable
- Requires extensive setup with poor documentation
- Known security issues

### For Research Papers

✅ **Include if:**
- Published in reputable venues (ACL, ICML, NeurIPS, ICLR, EMNLP, etc.) or arXiv
- Significant impact or novel contributions
- Relevant to code generation, understanding, or AI-assisted development

### For Datasets & Benchmarks

✅ **Include if:**
- Publicly available
- Well-documented
- Used in research or industry
- Maintained and versioned

## Pull Request Process

1. **Fork the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/awesome-ai-coding.git
   cd awesome-ai-coding
   ```

2. **Create a new branch**
   ```bash
   git checkout -b add-new-tool
   ```

3. **Make your changes**
   - Add your entry in the appropriate section
   - Maintain alphabetical order within sections (unless there's a good reason not to)
   - Follow the formatting rules below

4. **Test your links**
   - Ensure all URLs work correctly
   - Check that formatting is correct

5. **Commit your changes**
   ```bash
   git add README.md
   git commit -m "Add [Tool Name] to [Category]"
   ```

6. **Push to your fork**
   ```bash
   git push origin add-new-tool
   ```

7. **Create a Pull Request**
   - Use a clear, descriptive title
   - Explain what you're adding and why
   - Reference any related issues

### PR Title Format

Use one of these formats:

- `Add [Tool Name] to [Category]`
- `Update [Tool Name] description`
- `Fix broken link for [Tool Name]`
- `Reorganize [Category] section`
- `Add new category: [Category Name]`

### PR Description Template

```markdown
## What

Brief description of what you're adding/changing.

## Why

Why this addition/change is valuable to the list.

## Checklist

- [ ] Entry follows the formatting guidelines
- [ ] Link is working and points to the official source
- [ ] Description is concise and accurate
- [ ] Entry is in the appropriate category
- [ ] Entry maintains alphabetical order (if applicable)
- [ ] No duplicate entries exist
- [ ] Tool/resource meets quality standards
```

## Content Guidelines

### Descriptions

Good descriptions are:

- **Concise**: One to two sentences maximum
- **Informative**: Clearly explains what the tool does
- **Objective**: Factual, not promotional
- **Specific**: Highlights unique features or capabilities

**Examples:**

✅ Good:
```markdown
- **[Cursor](https://cursor.com)** - AI-first code editor built on VS Code with Claude Sonnet 4, GPT-4, and other models. Features Tab completion, Cmd+K inline editing, and Agent mode for autonomous coding.
```

❌ Too promotional:
```markdown
- **[Tool]** - The best and most amazing AI coding tool ever created! Revolutionary and game-changing!
```

❌ Too vague:
```markdown
- **[Tool]** - Helps with coding using AI.
```

### Links

- Always use official sources (main website or official GitHub)
- Use HTTPS when available
- Prefer main product pages over blog posts or documentation
- For papers, link to arXiv, ACL Anthology, or publisher site

### Formatting

Follow this exact format:

```markdown
- **[Tool Name](https://example.com)** - Brief description of what it does and key features.
```

Elements:
- Hyphen and space at start: `- `
- Tool name in bold with link: `**[Name](url)**`
- Space, hyphen, space: ` - `
- Description with period at end
- Capitalize first word of description

## Formatting Rules

### Section Headers

```markdown
## Main Category

*Subcategory description*

### Subcategory (if needed)
```

### Lists

- Use hyphens (`-`) for list items
- One entry per line
- Blank line between different tools
- Maintain alphabetical order within sections (generally)

### Emphasis

- **Bold** for tool names: `**Name**`
- *Italic* for section descriptions or emphasis
- `Code` for technical terms, commands, or parameters

### Links

```markdown
[Link Text](https://example.com)
```

Always check:
- [ ] URLs don't have trailing slashes (unless required)
- [ ] Links open to the correct page
- [ ] HTTPS is used when available

## Additional Notes

### Updating Existing Entries

When updating existing entries:
- Preserve the original intent unless it's incorrect
- Update version numbers or feature lists if changed
- Mark deprecated tools appropriately
- Add archive links if tools are shut down

### Removing Entries

Tools should be removed or marked if:
- Project is archived/abandoned (2+ years)
- Website/repository is no longer accessible
- Tool has been superseded by something better
- Major security issues discovered

Instead of removing, consider adding a note:
```markdown
- ~~**[Old Tool](link)**~~ - **[Deprecated]** Description. Replaced by [New Tool](link).
```

### Categories

If you think a new category is needed:
1. Gather at least 3-5 tools that would fit
2. Propose a clear category name and description
3. Explain why existing categories don't fit
4. Submit as a separate PR with discussion

## Style Guide

### Capitalization

- Tool names: Use official capitalization
- Descriptions: Capitalize first word only (standard sentence case)
- Acronyms: All caps (e.g., IDE, CLI, API, LLM)

### Abbreviations

Use common abbreviations but spell out on first use in sections:
- IDE (Integrated Development Environment)
- CLI (Command Line Interface)  
- LLM (Large Language Model)
- API (Application Programming Interface)

### Punctuation

- End descriptions with a period
- Use Oxford commas in lists
- Use em dashes (—) for parenthetical statements

## Review Process

Maintainers will review PRs for:

1. **Relevance** - Is it AI coding-related?
2. **Quality** - Does it meet our standards?
3. **Formatting** - Does it follow the guidelines?
4. **Uniqueness** - Is it already listed?
5. **Accuracy** - Is the description correct?

Reviews typically happen within 1-7 days. Please be patient and responsive to feedback.

## Questions?

If you have questions or need clarification:

1. Check existing issues for similar questions
2. Open a new issue with the "question" label
3. Provide context and be specific

## Code of Conduct

Be respectful, constructive, and professional. We're all here to make this resource better for the developer community.

---

Thank you for contributing! Your efforts help developers worldwide discover and use the best AI coding tools available.
