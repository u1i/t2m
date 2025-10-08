# 📊 Table to Markdown Converter

A simple, elegant web tool that converts tables from Excel, Word, and web pages into clean, properly formatted Markdown tables.

## ✨ Features

- **Line Break Handling** - Automatically removes line breaks within cells (a common issue with other converters)
- **Consistent Column Widths** - Creates readable, well-aligned markdown tables
- **Smart Formatting** - First row automatically becomes the header
- **Pipe Escaping** - Handles pipe characters (`|`) in cell content
- **One-Click Copy** - Copy the result directly to your clipboard
- **Modern UI** - Clean, responsive design that works on all devices

## 🚀 Usage

1. Open `index.html` in your web browser
2. Copy a table from Excel, Word, Google Sheets, or any webpage
3. Paste it into the input area
4. Click "Convert to Markdown"
5. Click "Copy to Clipboard" to copy the result

## 💡 Why This Tool?

Many markdown table converters struggle with line breaks inside table cells, which breaks the markdown syntax. This tool automatically converts line breaks to spaces, ensuring your markdown tables always work correctly.

### Example

**Input:** A table with multi-line cells from Excel

**Output:**
```markdown
| Name    | Description                      | Status |
| ------- | -------------------------------- | ------ |
| Project | A multi-line description here    | Active |
| Task    | Another description with spaces  | Done   |
```

## 🛠️ Technical Details

- Pure HTML, CSS, and JavaScript - no dependencies
- Works completely offline
- Processes tables client-side (your data never leaves your browser)
- Compatible with all modern browsers

## 📝 License

Free to use and modify as needed.

## 🤝 Contributing

Feel free to fork, modify, and improve this tool!
