# My Resume

A repo to keep track of my JSON Resumes and maintain different versions for easy editing no matter how much time I spend away from them.

Built with JSON Resume: https://jsonresume.org/

## Editing the Theme

Open ```./node_modules/jsonresume-theme-paper/resume.template``` and edit handlebars/html (do not rename file ext or it will break)

## Commands
**Export:**

```bash
node node_modules/resume-cli/build/main.js export Resume-EthanBonsignori.pdf --theme paper;
```

**Serve:** (doesn't seem to work with custom template edits)
```bash
node node_modules/resume-cli/build/main.js serve --theme paper;
```

**Validate:**

```bash
node node_modules/resume-cli/build/main.js validate
```