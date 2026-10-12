<p align="center"><a href="https://redactic.eu/"><img src="docs/redactic-logo.svg" alt="Redactic" height="56"></a></p>

# Redactic

[Redactic](https://redactic.eu/) is a European document redaction tool. It detects personal data in PDF, Word, Excel, images and scanned documents, and lets you either **mask it reversibly** before working with AI or **black it out permanently** before sharing.

- Processed in the EU, held only in encrypted memory for a few minutes, never stored
- Never used to train AI models
- Reversible masking with restoration in your browser: the mapping never reaches the server
- Permanent black-out on the page, including OCR for scans, plus metadata removal
- Redaction certificate with document hashes for every operation
- DPA signed automatically on subscription

This repository holds the public overview page published at **https://egesia1.github.io/redactic-docs/** and is the place to request support for new identifier types. The product itself runs at [redactic.eu](https://redactic.eu/).

## National identifiers validated by check digit

| Country | Identifiers |
|---|---|
| France | NIR, SIREN, SIRET, numéro fiscal, RIB, TVA, passport |
| Germany | Steuer-IdNr, USt-IdNr, Sozialversicherungsnummer |
| Italy | Codice Fiscale, Partita IVA, Tessera Sanitaria |
| Spain | DNI, NIE, NSS |
| All | IBAN in any country format, payment card numbers |

Formats for the Netherlands, Switzerland, Austria, Belgium, Ireland, the United Kingdom, the United States, Canada, India, Singapore and South Africa are also recognised.

## Request an identifier type

Missing a document type or a national identifier your work depends on? [Open an issue](https://github.com/egesia1/redactic-docs/issues/new) with the country, the identifier name and a link to its official format specification. Please never paste real personal data in an issue.

---

Redactic is a product by [KS-Agents](https://ks-agents.com/).
