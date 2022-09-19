to run with WSGI server:
install flask and waitress server
use "waitress-serve --port=80 --call "main:app"" to run it
go to the link given, like "http://127.0.0.1:5000"
if you add "/api/v1/hello-world14" in the end, you`ll recieve another message
CTRL+C in the terminal to close the server, now the site is unreacheble

to run with flask:
with cd move to ".../PP"
install flask: 'pip flask install'
write in cmd: 'set FLASK_APP="path_to_main.py"'
cmd: flask run
use the link, to go tj the site
