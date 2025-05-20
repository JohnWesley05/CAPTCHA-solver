# Text CAPTCHA Solver Extension

## Overview
This browser extension is a research-focused tool designed to solve text-based CAPTCHAs. It has been trained on CAPTCHAs from selected government websites for demonstration and research purposes only.

## Features
- **Process CAPTCHAs with a single click**: Right-click on a CAPTCHA and select "Process CAPTCHA" from the context menu.
- **Automatic CAPTCHA filling**: If successfully solved, the CAPTCHA field is autofilled.
- **Clipboard functionality**: The solved CAPTCHA is also copied to the user's clipboard for convenience.
- **Notification system**: Receive a notification about the status of the CAPTCHA solving process.

## Technical Details
- This extension uses an OCR model trained with a Connectionist Temporal Classification (CTC) loss function to accurately recognize and solve text-based CAPTCHAs.

## Installation
1. Download the extension files.
2. Open your browser's extension manager (e.g., `chrome://extensions` for Chrome).
3. Enable developer mode.
4. Click "Load unpacked" and select the folder containing the extension files.

## Usage
1. Enable the extension in your browser.
2. Navigate to a webpage with a CAPTCHA.
3. Right-click on the CAPTCHA and select **Process CAPTCHA** from the context menu.
4. A notification will appear to inform you of the process status:
   - If solved successfully, the CAPTCHA field will be autofilled, and the text will be copied to your clipboard.
   - If not solved, you will be notified of the failure.

## Limitations
- This extension is designed for research and educational purposes only and should not be used for any malicious or unauthorized activities.
- It may not work on all types of CAPTCHAs or websites, especially those with advanced anti-bot mechanisms.

## Disclaimer
This tool is intended solely for research and development purposes. Unauthorized use on websites without proper consent is strictly prohibited. The developers are not responsible for any misuse of this tool.



