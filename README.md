# ZipFile-Extraction-Collation
📂 DOCX Collator from ZIP A lightweight Python utility that extracts .docx files from a ZIP archive and merges their content into a single, well-structured .docx document.
Takes a .zip file containing multiple .docx Word documents
Extracts all .docx files from the zip into a temporary folder
Reads and extracts text content from each Word document
Adds section headers to separate content from different files
Combines everything into a single .docx output file
Saves the final file in the same location as the original zip
Skips non-docx files or unreadable files with a warning
Useful for combining multiple reports, templates, or notes automatically
Built with python-docx — lightweight and customizable
