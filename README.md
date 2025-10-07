# Open PDFs

Open `index.html` in this folder to get a simple page with buttons that open the PDFs in a new tab.

Buttons available:
- `LOR-YUSUF.pdf` (Open LOR)
- `CERTIFICATE.pdf` (Open Certificate)
- `ONE_MORE_LETTER.pdf` (One More Letter) — place this file in the same folder to make the button work.

If your browser blocks local file navigation, run a simple local server from this folder and open http://localhost:8000/index.html

PowerShell (from this folder):

```powershell
python -m http.server 8000
```

Then open your browser to http://localhost:8000
