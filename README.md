# Sorting Hat

Automatically categorise file downloads from My Oracle Support into a directory based on the Service Request number.

## Configuration
There is currently no configuration, it simply looks for a download referrer URL and plucks the SR number from it.  Downloads will be placed into your normal download directory, with a subdirectory based on the SR name.  It is not possible to download into a directory outside of your Download directory.

## Installation

1. Clone the extension
```
  # cd ~/src
  # git clone https://github.com/lathiat/chrome-sortinghat
```
2. Open  <a href="chrome://extensions/">chrome://extensions/</a> or click (Menu button -> More Tools -> Extensions)
3. Enable Developer Mode
4. Select "Load unpacked extension"
5. Highlight the chrome-sortinghat directory and press OK
 
 
