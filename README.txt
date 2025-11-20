
followed the guide:
https://qlik.dev/embed/iframe/quickstart/embed-with-an-iframe/

for authentication followed the guide:
Handling user sessions with iframes and enigma.js (interactive Identity Providers)

CSP:
origin: localhost:9100, frame-ancestors

Web integration id: https://localhost:9100

run:
http-server --port 9100 -S -C cert.pem -o

browser: https://localhost:9100/