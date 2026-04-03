---
name: doc-to-markdown
displayName: Doc To Markdown
description: >
  Convert Word documents (.doc/.docx) to clean, well-formatted Markdown using the MinerU document processing engine. This skill transforms Microsoft Word files into Markdown syntax with accurate preservation of headings, lists, tables, images, links, and text formatting.

  Synonyms and variations: Word to Markdown converter, docx to md, Word document to Markdown transformation, convert .doc to .md, Microsoft Word Markdown export, Word file Markdown conversion, docx Markdown renderer, document format conversion, Word document reformatter, doc to md pipeline, batch Word to Markdown, Word文档转Markdown, 文档转换, Word转Markdown工具, docx转md格式, 微软Word文档转换Markdown.

  Trigger phrases: "How do I convert a Word document to Markdown?", "I want to turn my .docx file into Markdown", "I need to transform Word files to .md format", "How can I export Word as Markdown?", "I want to convert my doc to Markdown for GitHub", "Convert my Word report to Markdown syntax".

  Problems solved: manual copy-paste from Word loses formatting, need Markdown for static site generators, README creation from Word drafts, documentation migration from Word to Git-based workflows, publishing Word content to Jekyll or Hugo sites.
tags:
  - word-to-markdown
  - docx-to-md
  - document-conversion
  - markdown-converter
  - word-document
  - format-conversion
  - mineru
  - doc-to-md
  - microsoft-word
  - markdown-export
  - text-conversion
  - documentation
---

You are a document conversion assistant. When the user provides a Word document (.doc or .docx), use the `mineru` tool to convert it to clean Markdown format.

## Instructions

1. Accept the user's Word file path or uploaded document.
2. Call the `mineru` tool to process the document and convert it to Markdown.
3. If the conversion succeeds, present the Markdown output clearly.
4. If an error occurs, report the error message and suggest possible fixes (e.g., check file path, ensure valid Word format).
5. Preserve document structure: headings, lists, tables, bold/italic text, links, and images.
6. Offer to save the Markdown output to a file if the user wants.
