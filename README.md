# AI PDF Document Summarizer

This is an n8n workflow designed to automate. The system processes uploaded PDF files, generates concise AI summaries, extracts supplementary contextual knowledge from Wikipedia, and automatically logs the structured results into a Google Sheet.

## Business & Productivity Benefits
- Accelerates Research and Reading: Saves hours of manual reading by distilling long PDF files into clear, actionable summaries in seconds.
- Enriched Knowledge Extraction: Automatically looks up related data on Wikipedia, giving you broader context and deeper insights without manual searching.
- Automated Data Archiving: Eliminates manual data entry by immediately logging the PDF title, its summary, relevant external data, and the submission date into a centralized spreadsheet.
- Organized Knowledge Base: Builds a clean, searchable history of your reading materials and research history automatically over time.

## Features
- PDF Text Parsing: Extracts raw text data efficiently from any uploaded document file.
- AI-Powered Summarization: Utilizes OpenAI to analyze complex document topics and draft high-quality overviews.
- Wikipedia API Integration: Programmatically queries external reference material to augment internal document data.
- Automated Spreadsheet Logging: Saves structured data rows directly into Google Sheets.

## How it Works
1. A PDF file is uploaded or sent into the n8n workflow.
2. The workflow reads the file content and uses OpenAI to generate a structured summary.
3. The workflow extracts key topics from the document and searches Wikipedia for additional relevant context.
4. n8n compiles the file name, generated summary, Wikipedia data, and the current submission date.
5. All compiled information is neatly appended as a new row in a target Google Sheet.

## Requirements
- An account with n8n.
- An OpenAI API key.
- A Google Workspace account (Google Sheets).
- Wikipedia
