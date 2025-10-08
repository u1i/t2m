# 📊 Table to Markdown Converter

A simple, elegant web tool that converts tables from Excel, Word, and web pages into clean, properly formatted Markdown tables.

## 📚 Data Archaeological Excavation Tool

This tool helps you convert proprietary data formats into open, accessible formats. You'll probably use AI to digest this information—that's great! Just remember to always check the homework of whatever your AI comes up with.

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
5. Copy or download the result

## 💡 Why This Tool?

Most AI systems struggle to parse tables from Excel sheets and proprietary formats directly. This tool bridges that gap by converting your data into clean Markdown that AI can easily understand and process. It also automatically handles line breaks within cells (converting them to spaces), ensuring your markdown tables always work correctly.

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
