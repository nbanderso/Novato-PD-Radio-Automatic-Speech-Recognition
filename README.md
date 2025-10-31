**Novato Police Department Radio-Automatic Speech Recognition**

This project transforms public police radio communications from the Novato, California Police Department into structured, anonymized data to better understand local public safety activity.  Using consumer grade radio scanners, Whisper AI, and Python, the system:

- Records unencrypted dispatch audio legally and ethically
- Uses AI speech recognition to generate transcripts
- Expands police ten-codes and normalizes jargon
- Extracts locations, call types, units, and timestamps
- Geocodes streets and aggregates activity over time
- Outputs structured data into SQLite/PostgreSQL + an optional FastAPI dashboard

The goal is to enable community transparency, data-driven public discussion, and academic-quality analysis (e.g. call frequency by area, response types, potential bias trends), while protecting privacy and adhering to legal/ethical standards.  The entire pipeline is documented like a scientific study, with reproducibility in mind.
