# Generische Klassen

Generische Klassen sind Klassen, die so definiert sind, dass sie mit verschiedenen Datentypen verwendet werden können. Mit anderen Worten, eine generische Klasse ist eine Klasse, die einen oder mehrere Platzhaltertypen (sogenannte Typparameter) verwendet, anstelle eines konkreten Datentyps. Diese Platzhaltertypen können dann durch tatsächliche Datentypen ersetzt werden, wenn eine Instanz der generischen Klasse erstellt wird.

Ein Beispiel für eine generische Klasse in Java ist die ArrayList-Klasse. Diese Klasse ist so konzipiert, dass sie mit einer Vielzahl von Datentypen verwendet werden kann, indem sie einen Typparameter verwendet, der den Typ des gespeicherten Elements angibt. Durch die Verwendung von generischen Klassen können Entwickler wiederverwendbaren und flexiblen Code schreiben, der für verschiedene Anwendungsfälle verwendet werden kann, ohne dass separate Implementierungen für jeden Datentyp erforderlich sind.

Generische Klassen können genutzt werden, indem sie mit tatsächlichen Datentypen instanziiert werden. Dies kann durch die Verwendung von spitzen Klammern (<>), gefolgt von dem tatsächlichen Datentyp, der anstelle des Typparameters verwendet werden soll, erreicht werden. Ein Beispiel dafür wäre die Erstellung einer ArrayList-Instanz, die Integer-Objekte speichert:

    ArrayList<Integer> liste = new ArrayList<Integer>();

Durch die Verwendung von Generics wird Typsicherheit und Lesbarkeit des Codes verbessert und das Risiko von Laufzeitfehlern reduziert, da der Compiler bereits während der Kompilierung prüfen kann, ob die Typen korrekt verwendet wurden.
