# Cover

**Auto redact personal info (PII) from documents before sending to Ai. Documents never leave your machine.**

Cover is a redaction engine that finds and removes personal information (PII) from your documents. Things like SSNs, account and routing numbers, names,
addresses, dates of birth) from PDFs and images, entirely on your Mac.

Most redaction engines aren't well trained. And most local AI is extremely slow and over redacts, placing black boxes all over your documents in places they shouldn't be.

Cover's engine is deterministic (Rust) with fail-closed verification: the glyphs under every redaction are removed from the file itself, and the output is checked
at the byte level before Cover will save it. There's a Mac app that wraps the engine which allows for the most intuitive proofing & editing of redactions, saving you hours of time.

- Website and download: [coverredact.com](https://coverredact.com)
- Claude Desktop extension: [cover-mcp](https://github.com/coverredact/cover-mcp). Redact from a Claude conversation; no document text ever reaches the model.
- Support: support@coverredact.com

Cover Redact LLC
