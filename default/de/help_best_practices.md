### Bewährte RISM-Praktiken

In diesem Abschnitt werden bewährte Praktiken zur Katalogisierung für RISM erläutert, also Konventionen, die nicht in den Richtlinien festgehalten sind, die jedoch zu einer soliden, zuverlässigen und transparenten Erfassung beitragen.

#### 1. Freitextfelder und indexierte Felder

Wenn Sie in Ihrem Datensatz eine Person oder eine Institution nennen (z. B. in einem Bemerkungsfeld), dann tragen Sie den Namen bitte auch in die indesierten Felder **Nebeneintragung Personen (700)** oder **Nebeneintragung Körperschaften (710)** ein.

Dasselbe gilt für das Zitieren von Sekundärliteratur: Wenn Sie in einem Bemerkungsfeld auf eine Publikation verweisen, müssen Sie diese auch in das Feld **Literaturverweis (691)** eintragen.

Stellen Sie umgekehrt sicher, dass die Bedeutung eines indexierten Namens oder einer Institution klar ist, beispielsweise durch eine Erläuterung in einem Bemerkungsfeld.

#### 2. Sekundärliteratur zitieren

Informationen, die nicht in der Quelle zu finden sind, können in den RISM-Datensatz aufgenommen werden, aber die Sekundärliteratur sollte zitiert werden. Ist z. B. der Komponist eines Manuskripts durch einen Zeitschriftenartikel bekannt oder wird das Erscheinungsjahr einer gedruckten Ausgabe in einer veröffentlichten Studie über den Verleger angegeben, sollte die Quelle der Information durch eine **Bemerkung (500)** deutlich gemacht und im Feld **Literaturverweis (691)** indexiert werden.

#### 3. 3. URLs und Links zu externen Ressourcen

Verwenden Sie immer Permalinks, insbesondere wenn Sie auf Digitalisate im Feld **Elektronische Lokalisierung und Zugriff (856)** verlinken.

Wenn Sie einen Link zu einer Website herstellen möchten, dann verwenden Sie bitte kein Bemerkungsfeld. Geben Sie die Ressource stattdessen als bibliografische Referenz ein. Dies geschieht durch Eingabe in die Normdatei **Sekundärliteratur**. Verweisen Sie dann im Feld **Literaturverweis (691)** darauf und geben Sie in einem Bemerkungsfeld den Kurztitel an. Dadurch erhalten die Nutzer Zugriff auf die vollständigen bibliografischen Informationen und bei einer Änderung der URL ist nur eine einmalige Aktualisierung über die Datenbank **Sekundärliteratur** erforderlich.

Erstellen Sie für Bücher, die Sie bei Google Books oder anderen Online-Repositorien finden, immer einen bibliografischen Datensatz in der Normdatei **Sekundärliteratur** für das Buch selbst und nicht für das Repositorium.

Bei Datenbanken, die als Sekundärliteratur zitiert werden, können Sie zur Vereinfachung für unsere Nutzer die Datenbank im Feld **Literaturverweis (691)** zitieren und dann über das Feld **Elektronische Lokalisierung und Zugriff (856)** einen direkten Link zum Eintrag in der Datenbank bereitstellen.

Wenn Sie auf eine digitalisierte Musikquelle verweisen möchten, die sich aber nicht in RISM befindet, wenden Sie sich an die RISM-Zentralredaktion, um die Aufnahme der Quelle zu besprechen.

#### 4. Identifizierungen vornehmen

Häufig werden wichtige Informationen – wie die Namen von Komponisten oder Werken – nicht immer auf der Quelle selbst genannt. Manchmal ist es möglich, Identifizierungen anhand von Sekundärliteratur, Referenzquellen, anderen RISM-Datensätzen oder Archivquellen vorzunehmen. Wenn Sie auf solche Quellen zurückgreifen, sollten Sie in den Datensätzen immer deutlich machen, was Sie zur Identifizierung verwendet haben: Nennen Sie die Quelle in RISM (mit Sigel, Signatur und RISM-ID Nummer) in den **Bemerkungen (500)** und fügen gegebenenfalls einen **Literaturverweis (691)** hinzu. Stellen Sie sicher, dass für spätere RISM-Nutzer klar ist, wie Sie zu Ihren Schlussfolgerungen gekommen sind. Ausführlichere, erläuternde Informationen, die nicht für die Öffentlichkeit relevant sind, können bei Bedarf in **Interne Bemerkungen (599)** aufgenommen werden.

#### 5. Erstellen von Datensätzen auf Grundlage von Beschreibungen aus gedruckten Katalogen oder Online-Bibliothekskatalogen

Manchmal ist es nicht möglich, die Quelle persönlich einzusehen, und die einzig verfügbare Beschreibung findet sich in einem gedruckten Katalog, einem Werkkatalog oder einem Online-Bibliothekskatalog. Solche Beschreibungen können als Grundlage für einen RISM-Datensatz verwendet werden. Dabei ist Folgendes zu beachten:

- Ergänzen Sie eine **Bemerkung (500)**, die die Informationsquelle identifiziert, wie "Datensatz basierend auf Beschreibung in YouV"
- Link zur Informationsquelle im Feld **Werkverzeichnis (690)**, **Literaturverweis (691)** oder **Elektronische Lokalisierung und Zugriff (856)**, je nach Bedarf
- Im Feld **Herkunft (980)**, Unterfeld **Autopsie** wählen Sie **keine Autopsie**

#### 6. Die gemeinsame Katalogisierungsumgebung für Musikdrucke

Bibliografische Datensätze für Musikdrucke existieren in einer gemeinsamen Katalogisierungsumgebung, in der mehrere Bibliotheken Bearbeitungsrechte für denselben Datensatz haben. Dies unterscheidet sich von Manuskripten, die nur in der jeweiligen Bibliothek vorhanden sind. Aufgrund der gemeinsamen Umgebung, müssen die Auswirkungen des Hinzufügens oder Löschens von Informationen aus bibliografischen Kerndatensätzen sorgfältig bedacht werden.

Katalogisierer sollten keine Informationen aus dem Kerndatensatz entfernen, wenn diese korrekt sind. Verwaltungsinformationen werden in den Datensätzen gespeichert, die die Entscheidungen der Zentralredaktion und die Beziehung zu anderen Datensätzen erläutern können. Löschen oder bearbeiten Sie keine Daten in den Feldern **Ersteintrag in A/I (775)**, **Lokale Nummer (035)** oder **RISM-Serien (510)**. Löschen Sie niemals den Hinweis, dass ein Datensatz mit einem anderen Datensatz zusammengeführt wurde.

Wenn ein Datensatz bereits von einer anderen Arbeitsgruppe überarbeitet wurde (erkennbar an der Angabe des Sigels und der Signatur einer Bibliothek im Feld **Vorlageexemplar (588)**), entscheidet der Katalogisierer nach eigenem Ermessen, ob eine weitere Überarbeitung erforderlich ist. Falls Sie weitere Änderungen vornehmen, geben Sie in dem Vermerk bitte deutlich an, welche Überarbeitungen Sie durchgeführt haben.

Falls Ihr Exemplar unvollständig ist, sind möglicherweise auch Überarbeitungen möglich, aber weisen Sie im **Vorlageexemplar (588)** deutlich darauf hin, dass Ihr Exemplar unvollständig ist.

Wenn Sie einen Datensatz bearbeiten möchten, der anhand einem unvollständigen Exemplar beschrieben wurde, müssen zunächst die korrekten Materialinformationen im Exemplardatensatz der Bibliothek mit der unvollständigen Exemplar abgeglichen werden. Die Zentralredaktion kann bei der Übertragung von Daten in die Exemplardatensätze behilflich sein.
