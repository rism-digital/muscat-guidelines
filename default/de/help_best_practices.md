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

#### 5. Creating records based on descriptions from printed catalogs or online library catalogs

Sometimes it is not possible to access the source in person and the only description available is in a printed catalog, catalog of works, or online library catalog. Such descriptions may be used as the basis of a RISM record. When doing so:

- Include a **General note (500)** that identifies the source of information, such as "Record based on description in YouV"
- Link to the source of information in the field **Catalog of works (690)**, **Bibliographic reference (691)**, or **External resource** (856) as appropriate
- In the field **Record origin (980)**, subfield **Material examined**, select **Material not examined**

#### 6. The shared cataloging environment of printed music

Bibliographic records for printed editions exist in a shared cataloging environment where multiple libraries have editing rights to the same record. This differs from manuscripts, which are unique to the holding library. Due to the shared environment, care must be taken so that the implications of adding or deleting information from core bibliographic records is thought through.

Catalogers should not remove information from the core record if it is correct. Administrative information is stored in the records that can explain decisions made by the Editorial Center and the relationship to other records. Never delete a note that indicates that a record was merged with another record. Do not delete or edit data in the fields **Initial entry in A/I (775)**, **Local number (035)**, or **RISM series (510)**.

If a record has already been revised by another working group (evident by the presence of a library's siglum and shelfmark in the field **Source of description note (588)**), use cataloger's judgement as to whether further revision is necessary. If you make further changes, make it clear in the note what revisions you contributed.

If your copy is incomplete, revisions might still be possible, but make it clear in the **Source of description note (588)** that your copy is incomplete.

If you wish to edit a record that was previously described using an incomplete copy, it must first be ensured that the accurate material information is preserved in the holdings record of the library with the incomplete copy. The Editorial Center can assist with transferring data to holdings records.
