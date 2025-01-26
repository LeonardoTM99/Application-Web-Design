# Application Web Design

## Project Information
- **Name**: Leonardo Torres Madrid
- **Registration Number**: 3028958
- **Degree**: IDS
- **Semester**: 6
- **Subject**: Application Web Design
- **Professor**: Aaron Heriberto Narváez Burciaga


## Markdown Tagging Options

Markdown provides simple ways to format text. Below are some common tagging options:

1. **Headings**: Use `#` for headings. The number of `#` symbols determines the heading level.
   - Example: `# Heading 1`, `## Heading 2`
2. **Bold**: Surround text with `**` or `__` to make it bold.
   - Example: `**Bold Text**` → **Bold Text**
3. **Italic**: Surround text with `*` or `_` to italicize it.
   - Example: `*Italic Text*` → *Italic Text*
4. **Lists**:
   - Unordered: Use `-`, `*`, or `+`.
   - Ordered: Use numbers followed by a period (`1.`).
5. **Links**: Use `[Text](URL)`.
   - Example: `[GitHub](https://github.com)`
6. **Code Blocks**: Use backticks (`) for inline code or triple backticks for block code.



## Common Git Commands

Below is a list of useful Git commands, their purposes, and examples:

### 1. Check the Status of a Local Repository
Command: `git status`  
Description: Displays the status of the working directory and staging area, showing any changes.

### 2. Add Files to Staging Area
- Individual file: `git add <filename>`  
  Example: `git add README.md`
- All files: `git add .`  
  Description: Stages all modified and untracked files.

### 3. Add Comments to a Commit
Command: `git commit -m "<message>"`  
Description: Records changes in the repository with a descriptive message.  
Example: `git commit -m "Updated README.md with new sections"`

### 4. Push Changes to Remote Repository
Command: `git push`  
Description: Uploads changes from the local repository to the remote repository.  

### 5. Branch Management
- Create a branch: `git branch <branch-name>`  
  Example: `git branch feature-branch`
- Switch branches: `git checkout <branch-name>`  
  Example: `git checkout main`
- Delete a branch: `git branch -d <branch-name>`  
  Example: `git branch -d feature-branch`

### 6. Roll Back to a Specific Commit
Command: `git reset --hard <commit-hash>`  
Description: Reverts the repository to a specific commit.  
Example: `git reset --hard abc1234`
