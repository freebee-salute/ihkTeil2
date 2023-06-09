# TLS

TLS (Transport Layer Security) ist ein Protokoll zur sicheren Kommunikation über das Internet, das zum Schutz von Daten vor unbefugtem Zugriff entwickelt wurde. Es ist der Nachfolger des SSL (Secure Sockets Layer)-Protokolls und bietet ähnliche Funktionen, aber mit verbesserten Sicherheitsfunktionen.

TLS wird häufig verwendet, um die Verbindung zwischen einem Client (z.B. Webbrowser) und einem Server (z.B. Webserver) zu verschlüsseln und zu sichern, um sicherzustellen, dass sensible Informationen wie Benutzernamen, Passwörter, Kreditkartendaten und andere vertrauliche Informationen vor neugierigen Augen geschützt sind. Das Protokoll arbeitet auf der Transportebene des OSI-Modells und verwendet kryptographische Algorithmen, um die Daten zu verschlüsseln und zu authentifizieren.

TLS bietet verschiedene Sicherheitsmechanismen wie die Verschlüsselung von Daten, die Integritätssicherung und die Authentifizierung von Servern und Clients. Um die Authentizität von Servern zu überprüfen, verwendet TLS ein System von digitalen Zertifikaten, das von einer vertrauenswürdigen Zertifizierungsstelle ausgestellt wurde. Wenn ein Server ein Zertifikat vorlegt, überprüft der Client, ob es von einer vertrauenswürdigen Quelle ausgestellt wurde, bevor er die Verbindung aufbaut.

TLS ist eine wichtige Komponente bei der Sicherung von Online-Transaktionen und anderen sensiblen Daten, und wird von vielen Web-Browsern und Servern unterstützt. Es wird jedoch ständig weiterentwickelt, um den sich ständig ändernden Bedrohungen durch Cyberkriminalität und Hacking zu begegnen.

Bei TLS kann die Authentizität der Gegenstelle auch dann überprüft werden, wenn man im Vorhinein nicht alle Public Keys kennt. Dies geschieht mithilfe von digitalen Zertifikaten, die von vertrauenswürdigen Zertifizierungsstellen (Certificate Authorities, CA) ausgestellt werden. Die Zertifizierungsstelle überprüft die Identität des Antragstellers und stellt ihm ein digitales Zertifikat aus, das die Identität des Antragstellers und seinen öffentlichen Schlüssel enthält. Wenn eine Verbindung hergestellt wird, sendet die Gegenstelle ihr Zertifikat und der Empfänger überprüft das Zertifikat anhand des öffentlichen Schlüssels der Zertifizierungsstelle, um die Identität der Gegenstelle zu überprüfen. Wenn das Zertifikat gültig ist, kann man davon ausgehen, dass man tatsächlich mit der erwarteten Gegenstelle verbunden ist.

Vorgang:

1. Client kontaktiert den Server. Dieser Antwortet mit einem SSL-Zertifikat
2. Client prüft die Gültigkeit des Zertifikates und sendet dem Server eine Zufallszahl, verschlüsselt mit dem **public-key** des Servers
3. Der Server erzeugt aus dieser Zufallszahl einen **Sitzungsschlüssel** (Session key). Mit diesem wird die Kommunikation verschlüsselt.
4. Der Server sendet dem Client den Sitzungsschlüssel in verschlüsselter Form.
5. Nun können beide Parteien ihre Datem mit dem Sitzungsschlüssel gesichert senden.
