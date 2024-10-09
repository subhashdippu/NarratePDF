# PDF Text-to-Speech (TTS) App

## 📌 Introduction

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This Python-based application allows you to select a PDF file from your system and have the content of the PDF read aloud using text-to-speech (TTS). You can specify the starting page, and the app will read from that page onward using the `pyttsx3` text-to-speech library.

## 🚀 Features

- Allows you to select a PDF file via a file dialog.
- Reads the content of the PDF aloud starting from the page of your choice.
- Supports voice narration using the `pyttsx3` library.
- Automatically handles multi-page reading and skips empty or non-readable pages.

## 👨‍💻 Prerequisites

- **Python 3.x** installed on your machine.
- The following Python libraries:
  - `pyttsx3`: For text-to-speech functionality.
  - `PyPDF2`: For reading the PDF file.
  - `tkinter`: For the file selection dialog (comes pre-installed with most Python distributions).

## 🛠️ Installation Steps

Star and Fork the Repo 🌟 and this will keep us motivated.

1. Clone the repository

```bash
git clone https://github.com/subhashdippu/NarratePDF.git
```

2. Change the working directory

```bash
cd NarratePDF
```

3. Install dependencies

```bash
npm install
```

4. Run the app

```bash
npm run start
```
