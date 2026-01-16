
followed the guide:
https://qlik.dev/embed/iframe/quickstart/embed-with-an-iframe/

for authentication followed the guide:
Handling user sessions with iframes and enigma.js (interactive Identity Providers)

Configure a Content Security Policy with the following values:
- origin: localhost, frame-ancestors
- Web integration id: https://localhost

Run locally:
- (first time only) generate openssl key pairs using the command:
  - openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem
- (first time only) install http-server, e.g. with npm install -g http-server
- run: http-server --port 443 -S -C cert.pem --cors

Browser: https://localhost