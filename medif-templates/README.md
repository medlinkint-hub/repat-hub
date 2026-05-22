# MEDIF templates

Drop each airline's **official MEDIF PDF** into this folder using its
canonical key as the filename:

| Airline | Filename |
|---|---|
| Aegean Airlines    | `aegean.pdf`    |
| Lufthansa          | `lufthansa.pdf` |
| SWISS              | `swiss.pdf`     |
| Austrian           | `austrian.pdf`  |
| Air France         | `airfrance.pdf` |
| KLM                | `klm.pdf`       |
| British Airways    | `ba.pdf`        |
| ITA Airways        | `ita.pdf`       |
| Turkish Airlines   | `turkish.pdf`   |
| Pegasus            | `pegasus.pdf`   |
| Ryanair            | `ryanair.pdf`   |
| easyJet            | `easyjet.pdf`   |
| Wizz Air           | `wizz.pdf`      |

When a PDF is present here, the app's "📄 Generate PDF" button on the
Airline MEDIF form will load the **official airline file**, fill its
form fields with the case data, and download it for you to print or
email. If a PDF is missing for a given airline, the app falls back to
the HWA-branded HTML rendering of the IATA-standard MEDIF.

After uploading a new PDF, open the MEDIF form for that airline and
click "🔍 Inspect template" — it lists every AcroForm field name in
the PDF. Share that list and we'll write the case-to-PDF mapping for
that airline.

PDFs uploaded here are served by GitHub Pages at
`./medif-templates/<airline>.pdf` (same-origin, no CORS issues).
