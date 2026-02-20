# pshd-reader

A single-page web app for reading [Patient Shared Health Documents](https://github.com/flexpa/pshd). Scan or paste a SMART Health Link (SHLink) to retrieve, decrypt, and view a patient-shared FHIR R4 bundle.

## Features

- QR code scanning and manual SHLink input
- JWE decryption (A256GCM)
- FHIR R4 bundle verification with pass/warn/fail checks
- Patient demographics extraction
- Embedded PDF preview and download
- Raw FHIR bundle inspection and export

## Usage

Open `index.html` in a browser. No build step or server required.

1. Paste an SHLink URL (e.g. `shlink:/eyJ1cmwiOi...`) or scan a QR code
2. Click **Retrieve & Decrypt**
3. View the verification results, patient demographics, and PDF document

## License

[MIT](LICENSE)
