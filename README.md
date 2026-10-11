# Ultimate Converter

**Your files. Your device. Every feature free.**

Convert images, documents, audio, video, camera RAW files, and structured text locally on Windows. Pick a file, choose an available format, and save the result. Your original stays intact.

[**Download for Windows x64**](https://github.com/nilsenj/ultimate-converter/releases/tag/v0.1.0-beta.1) · [Report an issue](https://github.com/nilsenj/ultimate-converter/issues) · [Development updates](https://www.patreon.com/c/u4982665)

## Get started

1. Open the release page and download **Ultimate-Converter-0.1.0-beta.1-windows-x64.zip** under Assets.
2. Extract the entire ZIP to a folder you can write to. Keep the folders and DLLs together.
3. Run **ultimate_converter.exe**. No account or paid subscription is required.
4. Drop a file or choose one, select a supported output, convert, and save.

Windows 10/11 x64 is the target. This first public beta is tested on the developer's Windows machine; a clean-machine compatibility matrix is still pending. The executable is currently unsigned, so Windows may display a publisher/reputation warning. Code signing and an installer are planned.

## What you can convert

| Category | Available in this Windows beta |
| --- | --- |
| Images | Still PNG, JPEG, BMP, WebP, QOI, PNM and GIF input; PNG, JPEG, BMP, lossless WebP, QOI and PPM output |
| Documents | TXT, Markdown, HTML, RTF, DOCX, ODT and PDF, with text extraction and document reconstruction |
| Audio and video | Common FFmpeg-supported inputs, audio export/extraction, MP4/MKV/WebM routes; supported 4K/resize/shrink options |
| Camera RAW | Selected CR2, CR3, DNG, NEF and ARW variants, exported as standard images |
| Structured text | LOG exports, JSON/XML conversion, formatting and minification |

The app offers only routes available for the file and installed engines. Format families do not mean every codec or variant is supported.

## Built around local files

- Conversion runs on your device, without uploading files.
- All conversion features are free. Following the project or supporting development does not unlock features.
- Outputs are validated before saving; existing files are not overwritten by default.
- Open saved files and revisit recent conversions from the app.

PDF conversion reconstructs content: complex layouts can change. Scanned PDFs do not have an OCR path in this beta. Tables and headings are reconstructed where reliable. HDR, encrypted/unsupported documents, animated images and some RAW variants may be rejected. JSON/XML uses a documented typed mapping rather than guessing a conventional schema. Always review important converted documents.

## Releases and feedback

This repository hosts official downloads, release notes and issue reports. The application source-code license is still being decided. Third-party notices, LGPL library sources and build recipes are included with the download.

When reporting a problem, include the app version, Windows version, input/output formats and the error message. Only attach files you are comfortable publishing; use a minimal non-sensitive sample.

[Watch the app overview](https://youtube.com/shorts/-9uI7JuB4JE) · [Follow on Patreon](https://www.patreon.com/c/u4982665)

