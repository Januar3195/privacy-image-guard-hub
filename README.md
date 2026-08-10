# Image Privacy Guard v2.5-beta.1 - 2026 Privacy Suite

> **Client-side image sanitization for 2026.** Image Privacy Guard evaluates hidden image tags directly within your Web browser, allowing you to sanitize JPG, PNG, and TIFF media without sending any data over the network.

[![Platform](https://img.shields.io/badge/Platform-web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2.5-beta.1-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/masonh67/privacy-image-guard-hub?style=flat-square)](https://github.com/masonh67/privacy-image-guard-hub)

---

<p align="center">
  <a href="https://masonh67.github.io/privacy-image-guard-hub/">
    <img src="https://img.shields.io/badge/Download-Image%20Privacy%20Guard%20Latest-brightgreen?style=for-the-badge" alt="Download Image Privacy Guard">
  </a>
</p>

> **[Download Image Privacy Guard v2.5-beta.1](https://masonh67.github.io/privacy-image-guard-hub/)**

---

[Download Latest Build](https://masonh67.github.io/privacy-image-guard-hub/)

---

## Overview

Image Privacy Guard is a browser-focused security utility built to scan media headers and purge embedded attributes before files leave your machine. Because all processing executes locally, you can evaluate and clean graphics prior to public distribution without risking data leaks.

This tool caters to photographers, designers, and privacy-conscious users needing an immediate method to strip EXIF and structural metadata. By executing everything inside the browser document model, it delivers quick inspection and scrub options without requiring backend infrastructure.

---

## Key Capabilities

- Completely client-side execution for local file verification
- Instant scanning of hidden tags embedded inside graphics
- One-click stripping of identified tracking or descriptive metadata
- Zero network transfers or remote storage requirements
- Broad compatibility with JPG, PNG, and TIFF extensions
- Streamlined interface optimized for rapid audit workflows
- Prepares your media for safe web publishing

---

## Setup Instructions

1. Access the web app using any modern browser, or download the source code locally:
   - `git clone https://github.com/masonh67/privacy-image-guard-hub.git
2. Serve the static directory through your web server of choice or open the index entry point directly.
3. Import your target file into the interface to execute the initial diagnostic.

*Note: For self-hosted instances, confirm your web browser environment can parse the application bundle without relying on remote API calls.*

---

## Operational Guide

1. Launch Image Privacy Guard in a web browser.
2. Drag or select a JPG, PNG, or TIFF file.
3. Inspect the discovered header attributes.
4. Execute the metadata deletion process.
5. Export the sanitized image file to your disk.

Standard deployment steps:

- Audit file properties prior to distribution
- Purge unwanted identification records
- Save the sanitized asset for publication or long-term storage

---

## Environment Parameters

System behavior is configured through local browser state or direct edits to static configuration blocks, depending on your hosting setup.

Sample structure:

    {
      "analysis": true,
      "metadataRemoval": true,
      "supportedFormats": ["jpg", "png", "tiff"]
    }

To modify operational defaults in static deployments, adjust the target JSON or runtime parameters in your build directory.

---

## System Requirements

- A modern Web standards-compliant browser
- JavaScript processing enabled
- Sufficient available RAM and storage to process incoming image buffers
- Acceptable formats: JPG, PNG, TIFF

The entire engine operates without external API connections or remote server dependencies.

---

## Frequently Asked Questions

**Are files uploaded to remote servers during processing?**  
No. File parsing and header scrubbing happen entirely inside your local browser context.

**Which graphics formats can I scrub?**  
The utility supports standard JPG, PNG, and TIFF formats.

**How do I update to newer builds?**  
Pull the latest code from the main repository or replace your static web directory with the latest release assets.

**Where are user preferences persisted?**  
Settings remain stored in the local application state or within the static assets served by your host.

**What should I do if a file fails to load?**  
Ensure your image matches one of the three supported file types and verify that your browser has adequate free memory.

---

## License Details

Distributed under the GNU GPL v3.0 License. Refer to [LICENSE](LICENSE) for full legal text.
