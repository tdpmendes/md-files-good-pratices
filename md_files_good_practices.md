# Best Practices for Writing Markdown Files (.md)  

## Table of Contents  
- [1. Use Headings and Subheadings](#1-use-headings-and-subheadings)  
- [2. Use Lists to Organize Ideas](#2-use-lists-to-organize-ideas)  
- [3. Highlight Code Snippets](#3-highlight-code-snippets)  
- [4. Create Links and Images](#4-create-links-and-images)  
- [5. Use Emphasis Moderately](#5-use-emphasis-moderately)  
- [6. Keep Text Clear and Direct](#6-keep-text-clear-and-direct)  
- [7. Use Tables for Structured Data](#7-use-tables-for-structured-data)  
- [8. Separate Sections with Horizontal Lines](#8-separate-sections-with-horizontal-lines)  
- [9. Add a Table of Contents (Optional)](#9-add-a-table-of-contents-optional)  
- [10. Test Rendering](#10-test-rendering)  

## 1. Use Headings and Subheadings  
Use `#`, `##`, `###` to structure content hierarchically.  

# Main Heading  
## Section  
### Subsection  

## 2. Use Lists to Organize Ideas  
- Use `-`, `*`, or `1.` for bulleted or numbered lists.  

### Example of a Bulleted List:  
- Item 1  
- Item 2  
  - Subitem  

### Example of a Numbered List:  
1. First item  
2. Second item  
   1. Subitem  

### ✅ 3. Highlight Code Snippets  

- Use single backticks for inline code: `` `command` ``  
  Example: Use the command `npm install` to install dependencies.  

- Use triple backticks for code blocks:  

#### Example in JSON:  
```json  
{  
  "name": "John",  
  "age": 30  
}  
```  

### ✅ 4. Create Links and Images  

- **Links**: Use `[text](URL)` to create links.  

#### Example of a Link:  
Visit [Microsoft's website](https://www.microsoft.com).  

- **Images**: Use `![alt text](image URL)` to display images.  

#### Example of an Image:  
![Markdown Logo](https://markdownlogo.com)  

### ✅ 5. Use Emphasis Moderately  

- **Bold**: Use `**text**` or `__text__`  
  Example: **Important**  

- *Italic*: Use `*text*` or `_text_`  
  Example: *Slight emphasis*  

- ***Bold and Italic***: Combine them with `***text***`  
  Example: ***Very important***  

### ✅ 6. Keep Text Clear and Direct  

- Prefer short and objective sentences.  
- Avoid unnecessary technical jargon.  
- Use simple and accessible language.  
- Separate ideas into distinct paragraphs.  
- Highlight key points with lists or emphasis.  

> Clear text improves readability and understanding, especially in technical documentation.  

### ✅ 7. Use Tables for Structured Data  

- Use `|` to separate columns and `-` to create the header.  

#### Example of a Table:  

| Name      | Age  | City         |  
|-----------|------|--------------|  
| John      | 30   | Porto        |  
| Mary      | 25   | Lisbon       |  
| Anna      | 28   | Coimbra      |  

> Tip: Align columns for better readability, even if Markdown doesn’t require it.  

### ✅ 8. Separate Sections with Horizontal Lines  

- Use three hyphens (`---`), asterisks (`***`), or underscores (`___`) to create a horizontal line.  

#### Example:  

---  

This line visually separates content blocks.  

***  

It also works with asterisks.  

___  

Or with underscores.  

### ✅ 9. Add a Table of Contents (Optional)  

- A table of contents improves navigation, especially in long files.  
- Use anchor links for each section.  

#### Example of a Table of Contents:  

```markdown  
## Table of Contents  
- 1. Introduction  
- 2. Installation  
- 3. Usage  
```  

> Tip: Keep headings consistent so links work correctly.  

### ✅ 10. Test Rendering  

- Preview your `.md` file in an editor that supports Markdown (like VS Code, GitHub, Obsidian, etc.).  
- Check if links, lists, tables, and code blocks render correctly.  
- Fix line breaks, syntax errors, or incorrect formatting.  

> Good rendering enhances readability and improves the reader's experience.