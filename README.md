# SITO WEB NODEJS+FRAMEWORK EXPRESS+SSL


Come si usa?
Digita questo comando nella cartella dove metti i file:

npm start app.js

DEFAULT PORT SSL: 3543
<br>
DEFAULT PORT: 3580

MODULI NECESSARI AL SUO FUNZIONAMENTO:
=> npm install express <=

<b>PER ABILITARE SSL MODIFICARE LE SEGUENTI RIGHE DI CODICE NEL FILE APP.JS</b>
<br>
<ul>
  <li>var privateKey = fs.readFileSync('/cartellavostrakey/privkey.pem', 'utf8');</li>
<br>
  <li>var certificate = fs.readFileSync('/cartellavostrocert/cert.pem', 'utf8');</li>
</ul>
