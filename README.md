# npm-packages

|Bezeichnung|Module|Beschreibung|
|--| :--: |-- |
|express|third party|Ein NodeJs Framework für die HTTP API [:br]mit Routing, Middleware|
|file system (fs)|native|Ermöglicht das arbeiten an den Dateien [:br]und Verzeichnissen des Betriebsystems|
|cors|third party|Cross-Origin-Resource-Sharing, erlaubt das Bereitstellen von[:br]Inhalten aus einer anderen Quelle.|
|body-parser|third-party|extrahiert den gesamten Body-Teil eines eingehenden Anfragestroms [:br]und stellt ihn in `req.body` dar, damit die Schnittstelle [:br]einfacher zu bedienen ist.  [(seit express v4.16.0 native)](https://expressjs.com/en/4x/api.html#express.json)|
|multer|third-party|Middleware für die Verarbeitung von `multipart/form-data`, [:br]da der body parser dafür kein Unterstützung hat|
|crypto|native|generiert Universally Unique Identifier (UUID) [:br] [(Hinzugefügt in: v14.17.0 NodeJs)](https://nodejs.org/docs/latest-v14.x/api/crypto.html#crypto_crypto_randomuuid_options) |
|uid|third-party|generiert Universally Unique Identifier (UUID)|
|morgan|third-party|HTTP request logger|
