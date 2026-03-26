# Ajdin Husic - Professional CV

This repository contains my professional CV in Markdown format for maximum portability and reusability.

## Files

- `ajdin_husic_cv.md` - Main CV in Markdown format
- `README.md` - This file with conversion instructions

## Converting to PDF

### Method 1: Using Pandoc (Recommended)
```bash
# Install Pandoc if you haven't already
# macOS: brew install pandoc
# Ubuntu/Debian: sudo apt-get install pandoc
# Windows: Download from https://pandoc.org/installing.html

# Convert to PDF
pandoc ajdin_husic_cv.md -o ajdin_husic_cv.pdf

# For better formatting with custom CSS
pandoc ajdin_husic_cv.md -o ajdin_husic_cv.pdf --pdf-engine=wkhtmltopdf --css=style.css
```

### Method 2: Online Converters
1. Copy the content from `ajdin_husic_cv.md`
2. Use online Markdown to PDF converters:
   - [Markdown to PDF](https://www.markdowntopdf.com/)
   - [Dillinger](https://dillinger.io/) (export as PDF)
   - [StackEdit](https://stackedit.io/) (export as PDF)

### Method 3: Using VS Code
1. Open `ajdin_husic_cv.md` in VS Code
2. Install "Markdown PDF" extension
3. Right-click in the file and select "Markdown PDF: Export (pdf)"

### Method 4: Using GitHub/GitLab
1. Push to GitHub/GitLab
2. View the rendered Markdown
3. Print to PDF from browser

## Converting to Other Formats

### HTML
```bash
pandoc ajdin_husic_cv.md -o ajdin_husic_cv.html
```

### Word Document
```bash
pandoc ajdin_husic_cv.md -o ajdin_husic_cv.docx
```

### LaTeX
```bash
pandoc ajdin_husic_cv.md -o ajdin_husic_cv.tex
```

## Customization

The Markdown format makes it easy to:
- Update contact information
- Add new experiences
- Modify formatting
- Version control changes
- Collaborate with others

## Benefits of Markdown Format

✅ **Portable** - Works on any platform  
✅ **Version Control** - Track changes with Git  
✅ **Reusable** - Easy to update and maintain  
✅ **Convertible** - Multiple output formats  
✅ **Professional** - Clean, readable format  
✅ **Collaborative** - Easy to share and edit  

## Tips for PDF Conversion

1. **For best results**: Use Pandoc with a custom CSS file
2. **For quick conversion**: Use online tools
3. **For professional formatting**: Consider using LaTeX templates
4. **For collaboration**: Keep the Markdown as source, generate PDFs as needed

## Updating Your CV

1. Edit `ajdin_husic_cv.md` directly
2. Commit changes to version control
3. Regenerate PDF using your preferred method
4. Keep both formats synchronized

