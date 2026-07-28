# Productivity Companion

A comprehensive guide to reading, converting, editing, and managing everyday digital content.

**Version 4.0.1 — Major Release**

## Table of Contents

- [Getting Started](#getting-started)
- [Settings & Configurations](#settings--configurations)
- [Accessible Document Reader](#accessible-document-reader)
- [AI & Vision Assistants](#ai--vision-assistants)
- [Audio & Video Editor](#audio--video-editor-new-feature)
- [Create & Convert Tools](#create--convert-tools)
- [Productivity & Utilities](#productivity--utilities)
- [Document Reader Keyboard Shortcuts](#document-reader-keyboard-shortcuts)
- [Tips & Troubleshooting](#tips--troubleshooting)

> **Keyboard Accessibility Welcome.**
> Productivity Companion has been built from the ground up to be fully accessible for keyboard navigators and screen readers (NVDA, JAWS, Narrator). Use `Tab` and `Shift+Tab` to move through interface controls, `Enter` or `Space` to execute operations, and the `Application key` (or `Shift+F10`) to trigger contextual menus.

## Getting Started

The main screen presents a clean, list-based catalog of all 24 tools. Scroll or press arrow keys to highlight a tool, and press `Enter` to launch it.

**Customizing features order:** You can reorganize the tools on your main home screen to match your workflow. Highlight any tool in the list, trigger the context menu (`Application key`, `Shift+F10`, or right-click), and choose to move it up, down, to the top, or to the bottom of the list. Click **Reset features order** (or press `Alt+R`) to sort them alphabetically.

**Access Keys:** Controls with underlines in their text, such as **Sett_i_ngs** or **_E_xit**, support quick access keys. Hold `Alt` and press the underlined letter (e.g. `Alt+I` for Settings, `Alt+E` for Exit) to activate them immediately.

## Settings & Configurations

Open the **Settings** dialog from the main screen (`Alt+I`) to configure speech options, audio formats, download files, and clear caches. Press `Tab` to cycle pages or click a tab:

### General
Select your user interface theme (Light, Dark, or System Default), configure the display language (English or Nepali), and toggle whether the app should automatically check for newer updates on startup.

### Text to speech
Cycle speech engines between Google TTS and Microsoft Edge. Select speech voices or languages, and click **Fetch latest voices** to refresh Edge natural online voices.

### Audio transcription
Toggle the Audio Transcriber mode between **Online** (cloud-based fast AI model) and **Offline** (uses local Whisper engine). Download or remove offline Whisper models (Tiny, Base, Small, Medium, Large) from this tab.

### Recorder
Select default paths for audio recording output. Configure channels (Mono - 1 or Stereo - 2), select sample rates (44100Hz / 48000Hz), and choose default recording formats (**WAV** or **MP3**).

### Conversion
Manage **Pandoc** installations. Pandoc is the conversion engine required for Word to EPUB, Markdown to HTML, and HTML to Markdown conversions. Download or remove it in one click.

### More
Manage additional languages for Tesseract OCR. Select languages from the list to download them. You can also clear the app cache to free up temporary space.

## Accessible Document Reader

The Document Reader provides a highly accessible, features-rich workspace for reading, manipulating, and analyzing PDF, DOCX, EPUB, and PPTX (PowerPoint) documents.

### Reading & Navigation

- **Import:** Import any supported file using the File menu (`Ctrl+I`). If a file was read previously, you will be prompted to resume reading from your last viewed section.
- **Reading Modes:** Cycle between **Plain Text** (optimized layout for screen readers) and **Formatted** mode.
- **Navigating:** Use previous (`Alt+PageUp`) and next (`Alt+PageDown`) buttons to cycle sections, click **Go** (`Ctrl+G`) to jump to a specific section, or open the Table of Contents (`Ctrl+T`) to navigate via headers.
- **Contrast Options:** Toggle high contrast themes (`Ctrl+H`), inverted colors (`Ctrl+Shift+I`), dark reading layout, and Split View (`Ctrl+Shift+V`).

### Interactive AI Reading Features

- **Ask AI Assistant** *(new feature)*: Click the "Ask AI assistant" button to open the AI Chat Frame with the active document pre-loaded. Ask questions, request summaries, or query data directly from the document.
- **Deep Insight with AI** *(new feature)*: Designed specifically for PDFs. Click "Deep inside with AI" to analyze the current page. The app runs a visual analysis using AI to render a clean, semantic HTML viewport. Highly useful for structured reading of complex tables, visual diagrams (with alt texts), and mathematical equations (rendered as clean, screen-reader accessible **MathML** code).

### Document library

Add any open document to your permanent reading archive by clicking **Add to document library**. On launch, select **Document library** to browse archived docs, manage library listings, and import/export library databases.

### PDF Manipulations & Tools

A suite of native tools under the **Manipulations** and **Tools** menus allows you to alter PDFs (it is recommended to work on copies):

- Lock files with PDF password protection, or decrypt/unlock secure PDFs.
- Highlight selected text blocks (`Ctrl+Shift+L`) or insert annotations (`Ctrl+Shift+N`).
- Redact sensitive text, rotate pages, delete sections, or extract section ranges.
- Extract links from documents, split PDFs into smaller files, export pages as images, or insert page-wide watermarks.
- Calculate reading statistics (`Ctrl+Shift+S`) and translate section content using online translators (`Ctrl+Shift+T`).

## AI & Vision Assistants

Productivity Companion integrates advanced AI models to assist you with chats, online searches, and visual descriptions.

### AI Assistant *(new feature)*
An accessible chat interface to ask questions, write content, and get coding or reasoning answers. Features a **Web search** toggle: turn it on to search the web for up-to-date real-time online search details.

### Image Describer *(new feature)*
Analyze and describe images using AI. Select **Open Image** to import a local image file, or select **Take Picture** to activate a camera framework and take a snapshot via webcam, then query the describer for layout, brightness, texts, and objects list.

### Image Generator *(new feature)*
Generate beautiful graphics or visual concepts using text prompts. Powered by online AI systems. View a preview inside the app and click save to export the output as PNG, JPG, or BMP files.

## Audio & Video Editor *(new feature)*

A completely keyboard-accessible, screen-reader friendly editor for audio and video files. Select **Open audio or video file** to upload a track and choose from 7 editing tools:

### Cut & Trim
**Cut:** Delete a selected portion of the file, joining the remaining segments together. **Trim:** Crop the file down, keeping only the selected range and deleting everything else.

### Split
Divide the audio or video track at a specific time marker and export the segments as separate files.

### Volume & Echo
**Change Volume:** Boost or lower the volume of the entire track or a custom segment. **Change Echo:** Add or customize echo feedback effects on your audio.

### Background Music
Overlay a secondary background audio track onto a video file, with control over background mixing volumes. (Videos only)

### Add Watermark
Apply text or image overlays onto your video files at custom positions (top-left, top-right, bottom-left, bottom-right). (Videos only)

## Create & Convert Tools

A collection of batch converters and creators to convert documents, audio/video formats, and images.

### Audio to video
Convert audio files (MP3/WAV/etc.) to video files. Customize output by adding background images, selecting aspect ratios (16:9, 4:3, 1:1), and configuring rendering quality.

### Video to audio
Extract audio streams from videos. Import a single video or select multiple files for batch processing. Output tracks can be saved as MP3, WAV, or M4A.

### Image to PDF *(new feature)*
Convert lists of images into a single PDF document. Select multiple image files and use the list context menu to rearrange files (Move up, down, top, bottom) before exporting.

### PDF to image
Extract and export pages of any PDF document as individual image files inside a folder of your choosing.

### Word to EPUB
Convert Microsoft Word (DOCX) files to EPUB documents. Requires Pandoc (downloadable from Settings > Conversion).

### Markdown & HTML Converters
Convert Markdown text files to HTML documents, or HTML files to Markdown formatting. Requires Pandoc.

### Image Resizer
Import an image and quickly scale down its dimensions to save storage space or optimize for web uploads.

### Text to Image
Create visual banners or card images from text blocks. Adjust fonts, font sizing, colors, background styling, frame borders, and add custom logos/watermark overlays.

### Text to Speech
Render text files or text inputs into spoken audio files. Choose speech engines, natural voices, adjustment speeds, and save outputs locally.

## Productivity & Utilities

Manage notes, links, translations, currency, weather, and reference searches.

### Links Saver *(new feature)*
Organize and store your important web URLs. Add, edit, delete, and categorize links. Featuring import and export of JSON directories (similar to the Notes Manager).

### Notes Manager
Add and edit text notes grouped under custom categories. Features JSON backup import/export. *V4.0 update:* Rename categories directly from the categories list context menu.

### Audio Transcriber
Convert spoken audio tracks into readable text transcripts. Supports *Online AI mode* (no setup required) and *Offline mode* (requires downloading local Whisper models in settings).

### Voice Recorder
Record voice memos and audio notes. Supports Mono/Stereo, sample rates (44100/48000Hz), and MP3/WAV formats. Warns you if you try to navigate back while recording is in progress.

### Text Translator
Translate paragraphs of text between a wide variety of global languages using online translation services.

### Currency Converter
Check real-time conversion rates and calculate currency conversions between dozens of world currencies.

### Weather
Search real-time weather conditions and 3-day weather forecasts for any city. Features a copy button to quickly copy forecast logs.

### Wikipedia Search
Search Wikipedia terms and view matching lists. Open summaries, or open full wiki pages in your default browser.

## Document Reader Keyboard Shortcuts

Use these keyboard shortcuts in the Document Reader window to optimize your speed and accessibility:

| Shortcut | Action Description |
|---|---|
| `Ctrl+I` | Import Document |
| `Ctrl+W` | Close Active Document / Window |
| `Ctrl+M` | View Document Properties |
| `Ctrl+F` | Find Text |
| `F3` | Find Next Match |
| `Shift+F3` | Find Previous Match |
| `Ctrl+C` | Copy Current Page / Section Text |
| `Ctrl+Shift+C` | Copy All Text / Compare Sections |
| `Ctrl+Shift+L` | Highlight Selection |
| `Ctrl+Shift+V` | Split View Panel |
| `Ctrl+Shift+O` | Run OCR Recognition |
| `Ctrl+Shift+P` | Select Text Extraction Profile |
| `Ctrl+R` | Read Aloud Text to Speech |
| `Ctrl+Shift+S` | Show Reading Statistics |
| `Ctrl+Shift+T` | Translate Current Section |
| `Ctrl+B` | Add Bookmark |
| `Ctrl+Shift+B` | Bookmarks Manager Window |
| `Ctrl+T` | Show Table of Contents |
| `Ctrl+Shift+N` | Manage Annotations |
| `Ctrl+Shift+H` | Manage Highlights |
| `Ctrl+G` | Go To Section Range |
| `Alt+PageUp` | Navigate to Previous Section |
| `Alt+PageDown` | Navigate to Next Section |
| `Ctrl++` | Zoom In |
| `Ctrl+-` | Zoom Out |
| `Ctrl+0` | Reset Zoom Level |

## Tips & Troubleshooting

- **Internet dependencies:** Features like Online AI transcription, AI Assistant (with or without Web Search), Image Generator/Describer, Weather, Wikipedia, Online Translation, Edge Voice retrieval, Google TTS, Currency Converter, and update checking require a stable internet connection.
- **Offline capabilities:** If you are working offline, utilize Offline OCR (download languages first in Settings > More) and Offline Transcription (download Whisper models in Settings > Audio transcription).
- **PDF manipulations:** When using watermarks, splits, redacts, or deletions on PDF files, always perform the operations on a copy of the file to preserve the original.
- **Clearing caches:** If the application feels slow or contains stale preview images/sessions, navigate to Settings > More and click **Clear productivity companion cache**.
- **Feedback GUI:** Click **Send feedback** (or press `Alt+K`) on the main home screen to open the feedback form. Enter your suggestions and submit them directly from the app interface.

---

*Productivity Companion 4.0.1 — User Guide • Built with accessibility in mind.*
