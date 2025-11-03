# Project Sanitizer

## Overview
**Project Sanitizer** automates the process of preparing **CloverDX sandboxes** for upload to **Upgrade Analyzer**.  
It removes sensitive data, ensures compliance with security standards, and packages the sandboxes automatically — saving time and reducing human error.

---

## Goals
- Simplify and speed up sandbox preparation  
- Ensure compliance with data protection policies  
- Reduce manual errors during sanitization  
- Provide clear reports of what was sanitized or changed  
- Improve user experience through simple setup and guidance

---

## Key Features
- **Sandbox Selection:** Choose one or multiple sandboxes to process  
- **Sensitive Data Scan:** Automatically detects passwords, tokens, and credentials  
- **Sanitization:** Removes or masks sensitive values in supported file types  
- **Packaging:** Creates a single ZIP file containing sanitized sandboxes  
- **Reporting:** Generates a summary report of processed and modified files  
- **User Guidance:** Short tutorial video for setup and usage (coming soon)

---

## Technical Details
- **Target:** CloverDX Server 5.0+  
- **Output:** `Sanitized_[timestamp].zip` + sanitization report (CSV/XLSX)  
- **Supported Files:** `.grf`, `.sgrf`, `.jbf`, `.rjob`, `.wjob`, `.properties`, `.cfg`, `.prm`, `.fmt`, `.ctl`, `.java`, `.sql`

---

## How-To Guide
- You can find a video explaining how to use it [**HERE**](https://youtu.be/jbTs5eXZfAI)
