---
title: "How Can I Use FocusTabs?"
description: "Step-by-step about how to best use our extension to organize your Chrome tabs and increase your productivity online."
url: "/page/how-can-i-use-focustabs/"
draft: false
tags: ["Featured"]
keywords: ["installation","install from release","download","zip file","developer mode","install from source","repository","dependencies"]
---

# How Can I Use FocusTabs?

By following the steps below, you will not get lost in a sea of tabs anymore. From now on, you will always find your flow.

### Installation

#### Install From Release

1. Download the latest release from the [Releases](https://github.com/guifeitosabr/s24-team-09/releases)
2. Unzip the downloaded ZIP file
3. Open Chrome and navigate to `chrome://extensions`
4. Enable "Developer mode"
5. Drag and drop the unzipped folder into the extensions page

#### Install From Source

1. Clone the repository:

   ```bash
   git clone https://github.com/jlumbroso/chrome-extension-text-collector
   ```

2. Install dependencies:

   ```bash
   cd chrome-extension-text-collector
   npm install
   ```

3. Build the extension:

   ```bash
   npm run build
   ```

4. Load the extension in Chrome:

   - Open Chrome and navigate to `chrome://extensions`
   - Enable "Developer mode"
   - Click "Load unpacked" and select the `dist` directory from this project directory.