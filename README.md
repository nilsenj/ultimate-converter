# Ultimate Converter

**Your files. Your device. Every feature free.**

[**Explore the app website**](https://nilsenj.github.io/ultimate-converter/)

Convert images, documents, audio, video, camera RAW files, and structured text locally on Windows. Pick a file, choose an available format, and save the result. Your original stays intact.

[**Download Windows installer**](https://github.com/nilsenj/ultimate-converter/releases/download/v0.1.0-beta.5/Ultimate-Converter-0.1.0-beta.5-windows-x64-setup.exe) · [Portable ZIP and release notes](https://github.com/nilsenj/ultimate-converter/releases/tag/v0.1.0-beta.5) · [Report an issue](https://github.com/nilsenj/ultimate-converter/issues) · [Development updates](https://www.patreon.com/c/u4982665)

## New in Beta 5

WebM AV1 GPU encoding with supported HDR and shrinking, explicit CPU/GPU controls, AVI output, offline archives, and opt-in repair of short damaged-audio sections. Audio repair replaces up to five seconds with silence and warns before Save; originals stay untouched.

Improved PDF/HTML compatibility and bundled fallback fonts, less repeated video preparation, shorter fresh-export validation when completion timing is consistent, cancellation cleanup and session recovery. Interrupted encoding restarts from zero. GPU routes remain gated to verified device/driver/build configurations; RTX 4060 Laptop was tested, not every NVIDIA installation. All conversion features remain free. [Release notes and limits](https://github.com/nilsenj/ultimate-converter/releases/tag/v0.1.0-beta.5).

## Get started

1. Download and run **Ultimate-Converter-0.1.0-beta.5-windows-x64-setup.exe**.
2. Follow Setup. It installs for your account without administrator access, creates a Start menu shortcut, and offers an optional desktop shortcut.
3. Open **Ultimate Converter** from Start. No account or paid subscription is required.
4. Drop a file or choose one, select a supported output, convert, and save.

All engines and runtime libraries are included, so installation works offline. Uninstall from **Windows Settings → Apps → Installed apps**.

Prefer a portable copy? Download the Windows ZIP from the release page, extract the entire archive, and run **ultimate_converter.exe**, keeping all DLLs and folders together.

Windows 10/11 x64 is the target. This public beta is tested on the developer's Windows machine; a clean-machine compatibility matrix is still pending. The executable is currently unsigned, so Windows may display a publisher/reputation warning. The installer is also unsigned; code signing remains planned.

## What you can convert

| Category | Available in this Windows beta |
| --- | --- |
| Images | Still PNG, JPEG, BMP, WebP, QOI, PNM and GIF input; PNG, JPEG, BMP, lossless WebP, QOI and PPM output |
| Documents | TXT, Markdown, HTML, RTF, DOCX, ODT and PDF, with text extraction and document reconstruction |
| Audio and video | Common FFmpeg-supported inputs, audio export/extraction, MP4/MKV/WebM/AVI routes; supported 4K/resize/shrink and HDR/SDR options |
| Archives | ZIP, 7z, TAR, TAR.GZ, TAR.XZ and TAR.BZ2 creation/extraction/conversion; RAR extraction/conversion |
| Camera RAW | Selected CR2, CR3, DNG, NEF and ARW variants, exported as standard images |
| Structured text | LOG exports, JSON/XML conversion, formatting and minification |

The app offers only routes available for the file and installed engines. Format families do not mean every codec or variant is supported.

## Built around local files

- Conversion runs on your device, without uploading files.
- All conversion features are free. Following the project or supporting development does not unlock features.
- Outputs are validated before saving; existing files are not overwritten by default.
- Open saved files and revisit recent conversions from the app.

PDF conversion reconstructs content: complex layouts can change. Scanned PDFs do not have an OCR path in this beta. Tables and headings are reconstructed where reliable. Supported HDR can be kept in 10-bit WebM or tone-mapped to SDR MP4/WebM. Dolby Vision profile 8 compatibility 1 uses its HDR10 base for re-encoding; dynamic metadata is dropped with explicit consent. Supported unchanged HEVC copying to MKV preserves verified metadata. Other Dolby Vision modes, encrypted/unsupported documents, animated images and some RAW variants may be rejected. JSON/XML uses a documented typed mapping rather than guessing a conventional schema. Always review important converted documents.

## Releases and feedback

This repository hosts official downloads, release notes and issue reports. The application source-code license is still being decided. Third-party notices, LGPL library sources and build recipes are included with the download.

When reporting a problem, include the app version, Windows version, input/output formats and the error message. Only attach files you are comfortable publishing; use a minimal non-sensitive sample.

[Watch the app overview](https://youtube.com/shorts/-9uI7JuB4JE) · [Follow on Patreon](https://www.patreon.com/c/u4982665)

## Website maintenance

The landing page is a static site in `index.html` and `assets/`, published by
GitHub Pages from `main` / root. `.nojekyll` keeps the site independent of a
Jekyll build. There are no runtime JavaScript dependencies, trackers, or external
fonts. Application source is maintained separately; this repository contains
only the public website, downloads, and release information.

To preview locally, run `python -m http.server 8000` in this repository and open
`http://localhost:8000`. When updating a release, change both installer buttons,
both portable links, version notes, release-note links, and relevant feature/FAQ
copy. Check phone and desktop layouts, keyboard navigation, enlarged text, and
download links before publishing. Preserve the relative asset paths so the site
works under `/ultimate-converter/`.


## Optional support

[Support via Base by mono](https://base.monobank.ua/Ck8dMrxpTM4C44): a one-time paid message from UAH 10 includes a Ukrainian mini-guide. All app features remain free. Checkout availability verified; no actual payment was made.
