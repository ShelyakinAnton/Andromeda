# Andromeda
Привет
Для старта веб сервера на Linux:
python3 -m http.server --cgi

Для старта веб сервера на Windows:
from http.server import HTTPServer, CGIHTTPRequestHandler
server_address = ("", 8000)
httpd = HTTPServer(server_address, CGIHTTPRequestHandler)
httpd.serve_forever()
