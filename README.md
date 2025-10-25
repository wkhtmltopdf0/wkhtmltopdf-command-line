# wkhtmltopdf Command Line — Complete CLI Guide

Use **wkhtmltopdf** efficiently with command-line options for generating PDFs from HTML or URLs.

---

## 🧱 Basic Command
```bash
wkhtmltopdf https://example.com file.pdf
⚙️ Common Options
Option	Description
--orientation	Set page orientation (Portrait / Landscape)
--page-size	Choose paper size (A4, Letter, etc.)
--header-html	Add a custom header
--footer-html	Add a custom footer
--zoom	Adjust zoom ratio

🧩 Advanced Example
bash
Copy code
wkhtmltopdf --zoom 1.3 --page-size A4 --footer-center "Page [page]" input.html output.pdf
📘 References
Official site: https://wkhtmltopdf.com

Docs: https://wkhtmltopdf.com/docs/

Download: https://wkhtmltopdf.com/download/
