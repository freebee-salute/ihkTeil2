#

HTTP-Codes sind Statuscodes, die vom Server an den Client zurückgegeben werden, um den Status einer Anfrage zu beschreiben. Hier sind die gängigsten HTTP-Statuscodes:

    200 OK: Die Anfrage wurde erfolgreich bearbeitet und die Antwort wird im Nachrichtenrumpf gesendet.

    201 Created: Die Anfrage wurde erfolgreich bearbeitet, und eine neue Ressource wurde erstellt.

    204 No Content: Die Anfrage wurde erfolgreich bearbeitet, und es gibt keine zusätzlichen Informationen, die zurückgesendet werden müssen.

    301 Moved Permanently: Die angeforderte Ressource wurde dauerhaft verschoben. Der Client sollte die neue Adresse verwenden.

    302 Found: Die angeforderte Ressource wurde vorübergehend verschoben. Der Client sollte die ursprüngliche Adresse beibehalten.

    400 Bad Request: Die Anfrage konnte aufgrund eines ungültigen oder fehlenden Parameters nicht verarbeitet werden.

    401 Unauthorized: Der Client ist nicht authentifiziert und darf keine Anfragen an den Server senden.

    403 Forbidden: Der Client ist authentifiziert, hat jedoch keine Berechtigung, auf die angeforderte Ressource zuzugreifen.

    404 Not Found: Die angeforderte Ressource wurde nicht gefunden.

    500 Internal Server Error: Ein unerwarteter Fehler ist aufgetreten, und der Server konnte die Anfrage nicht bearbeiten.

    503 Service Unavailable: Der Server kann die Anfrage aufgrund von Überlastung oder Wartung nicht bearbeiten.
