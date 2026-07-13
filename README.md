# Productivity Companion

A practical guide to reading, converting, creating, and managing everyday content.

**Version 3.5.1**

---

## Welcome

Productivity Companion is designed to work well with keyboard navigation and screen readers, including NVDA, JAWS, and Narrator. Use <kbd>Tab</kbd> and <kbd>Shift</kbd>+<kbd>Tab</kbd> to move between controls, <kbd>Enter</kbd> or <kbd>Space</kbd> to activate them, and the Application key (or <kbd>Shift</kbd>+<kbd>F10</kbd>) to open context menus where available.

## Contents

- [Getting started](#getting-started)
- [Settings and downloads](#settings-and-downloads)
- [Checking for updates](#checking-for-updates)
- [Document Reader](#document-reader)
- [Image and PDF OCR](#image-and-pdf-ocr)
- [Create and convert](#create-and-convert)
- [Productivity tools](#productivity-tools)
- [Weather and Wikipedia search](#weather-and-wikipedia-search)
- [Document Reader shortcuts](#document-reader-shortcuts)
- [Tips and troubleshooting](#tips-and-troubleshooting)

---

## Getting started

The home screen lists every tool. Select a feature and press <kbd>Enter</kbd> to open it. You can reorder the feature list: select an item, open its context menu, and choose to move it up, down, to the top, or to the bottom. Use **Reset feature order** to restore the default order.

Buttons with an ampersand in their label, such as **&Back**, have an access key. In most Windows configurations, press <kbd>Alt</kbd> plus the underlined letter to activate them.

The home screen also includes a **Check for update** button. See the [Checking for updates](#checking-for-updates) section for details.

## Settings and downloads

Open **Settings** from the home screen to tailor the application. Select **OK** to save your choices.

### General
Choose the application theme — Light, Dark, or System default — the display language (English or Nepali), and whether to automatically check for updates on startup.

### Text to speech
Select Google Text to Speech or Microsoft Edge voices. Choose a Google language or Edge voice as appropriate, and use **Fetch latest voices** when you need an updated Edge voice list.

### Audio transcription
Select a Whisper model and download it before using Audio Transcriber. Larger models can be more accurate but need more storage and processing time.

### Recorder
Set the default recording folder, channel count, and sample rate for Voice Recorder.

### Conversion
Download or remove Pandoc. Pandoc is needed for Word to EPUB and the Markdown/HTML conversion tools.

### More
Download additional Tesseract OCR languages and clear the Productivity Companion cache when needed.

> **Internet connection:** downloading resources, fetching voices, weather, currency conversion, Wikipedia search, online translation, Google text-to-speech, and checking for updates all require an internet connection.

## Checking for updates

Productivity Companion can check whether a newer version is available and download the installer for you.

### Manual check
Select **Check for update** on the home screen. A dialog will appear while the application contacts the update server. If a newer version is found, you will be asked whether to download it. The download dialog shows a progress bar and a **Cancel** button; you may close it at any time.

### Automatic check
When **Automatically check for updates on startup** is enabled in Settings > General (this is the default), the application silently checks for a newer version each time it starts. If one is found, you will be prompted to download it.

### Download and install
1. Confirm the download when prompted.
2. Wait for the progress bar to reach 100%.
3. When the download finishes, the installer launches automatically and the application closes so the installer can run.
4. Follow the installer instructions to complete the update.

Cancelling the download removes any partially downloaded file. You can also close the download dialog with <kbd>Alt</kbd>+<kbd>F4</kbd>, which cancels the download.

## Document Reader

Document Reader opens PDF, DOCX, EPUB, and PowerPoint (PPTX) documents. It provides a focused reading space with navigation, search, export, note-taking, read aloud, and document-management tools.

### Open and navigate a document
1. Open **Document Reader** and choose **Import document**.
2. Select the file you want to read. If you have previously read it, the reader can offer to resume from your last section.
3. Use **Previous**, **Next**, the section selector, or **Go** to move through the document.
4. Choose **Plain Text** or **Formatted** mode to suit the document and your reading preference.

### Read, search, and organise
- Use **Search** for text in the current section or the full document. The Edit menu also provides Find, Find Next, Find Previous, and Find and Replace where supported.
- Add bookmarks to return to important sections. Open Bookmarks or Bookmarks Manager to review, rename, delete, or export them.
- Use **TOC** to navigate by the table of contents or detected headings.
- Use **Add note** to attach a note to the current section.
- Use **Read** for read aloud. Playback options let you pause, resume, stop, and change speed.
- Use the View menu for zoom, high contrast, inverted colours, dark mode, and split view.

### Document Library
After opening a document, choose **Add to document library** to save it in your library. From the Document Reader start screen, open **Document library** to browse saved entries, open or remove them, and import or export the library data for backup or transfer.

### OCR, web viewer, and export
- **OCR:** Available for PDF files. Choose the current section, all sections, or a section range, then select the recognition language. When using Section range, enter both **From** and **To** before starting.
- **Web viewer:** Available for EPUB and PPTX. It opens the document in a browser-style reading view with previous, next, and page navigation. PPTX web viewing is experimental.
- **Export:** Export the current section or all sections in the formats offered by the Export dialog, including text, Word, audiobook, CSV, JSON, and HTML where available.

### PDF tools
PDF-specific tools include password protection and unlocking, text highlighting, annotations, link extraction, redaction, page rotation, deleting or extracting sections, splitting PDFs, extracting images, saving the current section as an image, and adding a watermark. Some operations modify or create files; save a copy first if you need to preserve the original.

### More reader tools
The Tools menu includes text-extraction profiles, section comparison, statistics, translating the current section, voice preview, and reader settings. Availability depends on the open document and installed components.

## Image and PDF OCR

### Image OCR
1. Open **Image OCR** and select an image.
2. Choose a primary language and, if useful, a secondary language.
3. Select **Start processing**.
4. Review the recognised text. Select **Copy** to place it on the clipboard, or **Save detected text** to save it as a UTF-8 `.txt` file in a location you choose.

For languages not already available, open Settings, switch to the More tab, and choose **Download additional languages for OCR**. OCR quality depends on the source image: sharp, high-contrast images generally give better results.

### PDF OCR
Open the PDF in Document Reader and select **OCR**. Select a scope and the language(s), then start OCR. OCR text is kept with the document reader session and can be viewed through an OCR text-extraction profile.

## Create and convert

### Audio to video converter
Choose an audio file, optionally add an image, select an aspect ratio and quality, then save the result as a video.

### Video to audio converter
Convert one video or import several videos for batch conversion. Choose MP3, WAV, or M4A as the output format.

### PDF to image converter
Select a PDF and export its pages as image files to a folder you choose.

### Word to EPUB converter
Select a Word document and save an EPUB version. Download Pandoc from Settings first if prompted.

### Markdown to HTML / HTML to Markdown
Open the source file and save the converted document. These converters use Pandoc.

### Image resizer
Open an image, then select Resize and choose where to save the smaller image.

### Text to image converter
Enter text and customise alignment, fonts, colours, background, frame, logo or watermark. Preview before saving the image.

### Text To Speech converter
Enter or load text, choose your configured speech engine and voice/language, then generate and save audio.

## Productivity tools

### Audio transcriber
Select an audio file to create a text transcription. Download a Whisper model in Settings before first use. Copy the completed transcription with the copy button.

### Voice recorder
Choose a folder, start recording, pause or resume as needed, then stop. You can play the saved recording. The app asks for confirmation if you go back while recording is in progress.

### Notes manager
Create categories, then add notes within them. Open, edit, or remove notes using the buttons or context menu. Export notes for backup and import a previous export when needed.

### Text translator
Type or load text, choose the target language, and select Translate. Copy the translated result from the output area.

### Currency converter
Enter an amount, choose source and target currencies, and select Convert to retrieve the current conversion result.

## Weather and Wikipedia search

### Weather
Enter a city name and choose **Fetch weather info**. The results include current conditions and forecasts. The **Copy weather info** button becomes available after successful retrieval; select it to copy the displayed weather report and receive a confirmation message.

### Wikipedia search
Enter a search term and select **Search**. Select a result and press <kbd>Enter</kbd> to open that article's summary. You can also use the result context menu to open its summary or full article.

## Document Reader shortcuts

| Shortcut | Action |
|---|---|
| <kbd>Ctrl</kbd>+<kbd>I</kbd> | Import document |
| <kbd>Ctrl</kbd>+<kbd>W</kbd> | Close document |
| <kbd>Ctrl</kbd>+<kbd>F</kbd> | Find |
| <kbd>F3</kbd> / <kbd>Shift</kbd>+<kbd>F3</kbd> | Find next / previous |
| <kbd>Ctrl</kbd>+<kbd>C</kbd> | Copy current section text |
| <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>C</kbd> | Copy all text (or compare sections, depending on menu context) |
| <kbd>Ctrl</kbd>+<kbd>B</kbd> | Bookmarks |
| <kbd>Ctrl</kbd>+<kbd>T</kbd> | Table of contents |
| <kbd>Ctrl</kbd>+<kbd>R</kbd> | Read aloud |
| <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>O</kbd> | OCR |
| <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>E</kbd> | Export |
| <kbd>Ctrl</kbd>+<kbd>+</kbd>, <kbd>Ctrl</kbd>+<kbd>-</kbd>, <kbd>Ctrl</kbd>+<kbd>0</kbd> | Zoom in, zoom out, reset zoom |

## Tips and troubleshooting

- If a download or online feature fails, first check your internet connection and try again.
- If an OCR language, Whisper model, Pandoc, or Edge voice is missing, use the relevant Settings tab to download or refresh it.
- Use clear source files for best results: high-resolution images for OCR, clean audio for transcription, and well-structured documents for conversion.
- Before using PDF editing tools, keep a backup of the original document.
- If the application seems to retain outdated temporary data, use **Clear productivity companion cache** in Settings.
- To enable or disable automatic update checks, use the checkbox in Settings > General.

Thank you for using Productivity Companion. Feedback, feature requests, and bug reports help make future versions better.

---

*Productivity Companion 3.5.1 — User Guide*
