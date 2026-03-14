# Canary Films Receipt Printer
MXW01 Catprinter website configured for Canary Films receipt printing.

Printer technology and protocol inspired by and copied from https://github.com/jeremy46231/catprinter.

**THIS CURRENTLY IS TESTED TO WORK WITH MXW01 CAT PRINTERS *ONLY***

## Logo
To display the Canary Films logo at the top of every receipt, place a file named `logo.png` inside the `images/` directory. The logo will be automatically scaled to fit the printer width (384px) while preserving its aspect ratio. If no logo file is found, receipts will print without a logo.

## Usage
Open `index.html` in a browser (Chrome/Edge recommended) via a local HTTP server. Web Bluetooth requires a secure context (HTTPS or localhost).

```bash
python3 -m http.server 8000
# Then visit http://localhost:8000
```
