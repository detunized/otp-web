# OTP Web

A single-page TOTP code viewer. Import your authenticator export, view live codes, copy with a click. No backend, no dependencies, runs entirely in the browser.

## Features

- Import OTP config via file drop or paste (JSON format)
- Live TOTP code generation using Web Crypto API
- Click any entry to copy the code to clipboard
- Add, edit, and delete entries
- Sort by original order, service name, or account
- Persistent storage via localStorage
- Deterministic color-coded icons per service

**https://1otp.netlify.app/**

## Usage

Open `index.html` in a browser or serve it with any static file server.

## License

MIT
