
followed the guide:
https://qlik.dev/embed/iframe/quickstart/embed-with-an-iframe/

for authentication followed the guide:
Handling user sessions with iframes and enigma.js (interactive Identity Providers)

Configure a Content Security Policy with the following values:

- origin: localhost, frame-ancestors
- Web integration id: https://localhost

Run locally:
- (first time only) install http-server, e.g. with npm install -g http-server
- run: http-server --port 443 -S -C cert.pem --cors

Browser: https://localhost