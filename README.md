# 📚 Wiki Scraper & JSON Extractor

This notebook extracts structured content from any Wikipedia page, organizing it into clean sections and exporting the data into a ready-to-use JSON format — perfect for NLP training, search indexing, or lightweight knowledge bases. 🧠📄

---

## ✨ Features

- 🌐 Scrapes content from any Wikipedia URL
- 🧱 Splits content by headers and sections
- 🧼 Cleans and formats text for AI use
- 💾 Exports to clean, nested JSON format
- 🔍 Useful for RAG pipelines, chatbots, or educational datasets

---

## 🔧 How It Works

1. Paste your Wikipedia URL 🔗
2. The notebook:
   - Fetches page HTML
   - Parses section headers and content
   - Cleans markdown/HTML artifacts
   - Outputs a structured JSON with headings + body text

---

## 📂 Output Example

```json
{
  "title": "Machine learning",
  "sections": [
    {
      "header": "History and relationships to other fields",
      "text": "Machine learning grew out of statistics and AI..."
    },
    {
      "header": "Approaches",
      "text": "Machine learning tasks are typically classified into..."
    }
  ]
}
