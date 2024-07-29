# Text Summarization using bart-large-CNN

# Document Summarizer

## Overview

The Document Summarizer is a Python-based application that uses the `transformers` library to generate concise summaries of text documents. It supports various file formats, including `.txt`, `.docx`, and `.pdf`. The application provides a user-friendly interface built with `ipywidgets` for uploading documents, entering text, and displaying summaries.

## Features

- **Text Summarization**: Uses the `facebook/bart-large-cnn` model from the `transformers` library to generate summaries.
- **Multiple File Formats**: Supports summarization for `.txt`, `.docx`, and `.pdf` files.
- **User-Friendly Interface**: Provides a web-based interface for uploading documents, entering text, and viewing summaries.
- **File Upload**: Allows users to upload files directly for summarization.
- **Real-Time Feedback**: Displays the summarized text in an output area.

## Installation

To install the required libraries, run the following command:

```bash
!pip install transformers ipywidgets python-docx PyMuPDF
