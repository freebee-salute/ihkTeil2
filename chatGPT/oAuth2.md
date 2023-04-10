#

OAuth2 (Open Authorization 2.0) ist ein Protokoll, das die sichere Weitergabe von Authentifizierungs- und Autorisierungsdaten zwischen verschiedenen Webanwendungen ermöglicht, ohne dass der Benutzer seine Anmeldeinformationen für jede Anwendung neu eingeben muss. Das Protokoll basiert auf der Autorisierung von Anwendungen und Benutzern und ermöglicht es Anwendungen, auf Ressourcen zuzugreifen, ohne dass der Benutzer seine Anmeldeinformationen an die Anwendung weitergeben muss.

Das Protokoll besteht aus vier Akteuren: dem Benutzer, der Client-Anwendung, dem Autorisierungsserver und dem Ressourcenserver. Der Client ist die Anwendung, die auf die Ressourcen des Benutzers zugreifen möchte, der Autorisierungsserver ist der Server, der die Autorisierung des Benutzers überprüft, und der Ressourcenserver ist der Server, der die Ressourcen des Benutzers bereitstellt.

Der Ablauf von OAuth2 besteht aus mehreren Schritten:

    Der Client sendet eine Anfrage an den Autorisierungsserver, um eine Autorisierung zu erhalten.
    Der Autorisierungsserver fordert den Benutzer auf, seine Anmeldeinformationen einzugeben, um die Identität des Benutzers zu überprüfen.
    Der Benutzer gibt seine Anmeldeinformationen ein und der Autorisierungsserver überprüft sie.
    Wenn die Anmeldeinformationen korrekt sind, fordert der Autorisierungsserver den Benutzer auf, die Freigabe der angeforderten Ressourcen zu autorisieren.
    Der Benutzer gibt seine Zustimmung zur Autorisierung der Ressourcen und der Autorisierungsserver sendet einen Autorisierungscode an den Client.
    Der Client sendet den Autorisierungscode an den Autorisierungsserver, um einen Zugriffstoken zu erhalten.
    Der Autorisierungsserver überprüft den Autorisierungscode und erteilt dem Client einen Zugriffstoken.
    Der Client sendet den Zugriffstoken an den Ressourcenserver, um auf die angeforderten Ressourcen zuzugreifen.
    Der Ressourcenserver überprüft den Zugriffstoken und erteilt dem Client Zugriff auf die angeforderten Ressourcen.

OAuth2 unterscheidet sich von Single-Sign-On (SSO), da es nicht nur die Anmeldung bei verschiedenen Anwendungen ermöglicht, sondern auch den Zugriff auf bestimmte Ressourcen innerhalb einer Anwendung autorisiert. Es ermöglicht auch eine feinere Steuerung des Zugriffs auf Ressourcen und kann den Benutzer auffordern, nur bestimmte Ressourcen freizugeben, anstatt der gesamten Anwendung den Zugriff zu gestatten.