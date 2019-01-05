# SITO WEB NODEJS+FRAMEWORK EXPRESS+SSL


Come si usa?
Digita questo comando nella cartella dove metti i file:

npm start app.js

DEFAULT PORT SSL: 3543
<br>
DEFAULT PORT: 3580

MODULI NECESSARI AL SUO FUNZIONAMENTO:
=> npm install express <=

PER ABILITARE SSL MODIFICARE LE SEGUENTI RIGHE DI CODICE NEL FILE APP.JS
<br>
var privateKey = fs.readFileSync('/cartellavostrakey/privkey.pem', 'utf8');
var certificate = fs.readFileSync('/cartellavostrocert/cert.pem', 'utf8');
