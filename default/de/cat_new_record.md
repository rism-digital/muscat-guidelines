# Datensätze und Datensatzarten

Ein neuer Datensatz kann in Muscat entweder durch Auswahl der entsprechenden Vorlage oder durch Kopieren eines bestehenden Datensatzes erstellt werden. Links zu beiden finden Sie auf der Seite Quellen oder in der vollständigen Datensatzansicht.

## Vorlagen

Muscat bietet Vorlagen für unterschiedliche Quellen. Die Vorlage bietet nur die Felder an, die für die jeweilige Quelle benötigt werden.

Wenn Sie feststellen, dass sich ein Datensatz in der falschen Vorlage befindet, benachrichtigen Sie bitte die Zentralredaktion, damit das Template geändert wird.

### Verfügbare Vorlagen

Ein Datensatz für eine **Sammlung** (übergeordneter Datensatz) wird verwendet, wenn das Objekt mehrere Teile enthält. Jedes Stück in der Sammlung wird dann als **Teileintrag der Sammlung** (untergeordneter Datensatz) eingetragen und mit dem Datensatz der Sammlung verknüpft. Handschriften und Drucke können auch als **Individualeintrag** außerhalb von Sammlungen existieren.

Ein **Konvolut** besteht aus Elementen, die separat erstellt, aber später zusammengebunden wurden, typischerweise von einem Eigentümer oder einer Institution. Dazu zählen sowohl Bände, in denen Drucke zusammengebunden sind, als auch Bände, in denen Drucke und Handschriften zusammengebunden sind.

Handschriften sind Unikate und können nur im Besitz einer einzigen Institution sein. Gedrucktes Material ist in Form von Exemplaren vorhanden. Das bedeutet, dass mehrere Bibliotheken Kopien (Exemplare) einer Ausgabe besitzen können.

Die Vorlage Libretto/Songtext wird für Dokumente verwendet, die Texte enthalten, die eindeutig eine gesungene musikalische Darbietung darstellen. Meistens handelt es sich dabei um Bücher, die den Text einer Oper oder eines anderen langen Vokalwerkes enthalten, es können aber auch reine Textsammlungen wie Gesangbücher oder Weihnachtslieder sein. Solche Veröffentlichungen werden manchmal auch als Liederbücher, Taschenbücher (die häufig auf der Quelle als solche gekennzeichnet sind) oder Melodiebücher bezeichnet.

Die Vorlage für Theoretika wird für Dokumente verwendet, die sich mit theoretischen Aspekten der Musik befassen, einschließlich Fragen der Komposition oder Aufführung.

Sowohl Libretti als auch Traktate können Noten enthalten, und die Grenze zwischen Libretto oder Traktat und Musik ist nicht immer klar zu ziehen.

Die folgenden Vorlagen werden in Muscat für Quellen verwendet. Vorlagen sind im MARC Record Leader kodiert, Positionen 6-7.

Für handschriftliches Material:
- Musikhandschrift
 - Sammlung (übergeordneter Datensatz) [LDR: dc]
   - Teileintrag der Sammlung (untergeordeneter Eintrag) [LDR: da]
 - Individualeintrag Musikhandschrift [LDR: dm]
- Libretto/Liedtext
 - Sammlung (übergeordneter Datensatz) [LDR: dc]
   - Teileintrag der Sammlung (untergeordeneter Eintrag) [LDR: ta]
  - Individualeintrag Libretto/Liedtext [LDR: tm]
- Traktat
   - Sammlung (übergeordneter Datensatz) [LDR: dc]
    - Teileintrag der Sammlung (untergeordeneter Eintrag) [LDR: ta]
   - Individualeintrag Theoretikum [LDR: tm]

Für gedrucktes Material:
- Musikdruck
 - Sammlung (übergeordneter Datensatz) [LDR: cc]
   - Teileintrag der Sammlung (untergeordeneter Eintrag) [LDR: ca]
 - Individualeintrag Musikdruck [LDR: cm]
- Libretto/Liedtext
 - Sammlung (übergeordneter Datensatz) [LDR: ac]
   - Teileintrag der Sammlung (untergeordeneter Eintrag) [LDR: aa]
  - Individualeintrag Libretto/Liedtext [LDR: am]
- Traktat
   - Sammlung (übergeordneter Datensatz) [LDR: ac]
    - Teileintrag der Sammlung (untergeordeneter Eintrag) [LDR: aa]
   - Individualeintrag Theoretikum [LDR: am]

Für Konvolutbände:
- Konvolut [LDR: pc]


## Kopieren bestehender Datensätze

Es gibt zwei Möglichkeiten, einen Datensatz zu kopieren.

Auf dem Auswahlbildschirm für die Vorlage: Geben Sie einfach die RISM-Nummer in das Feld „Erstellen aus vorhandener Quelle“ ein. Sie sehen dann eine Kopie des Datensatzes im Bearbeitungsmodus und können von dort aus alle gewünschten Änderungen am Datensatz vornehmen. Der kopierte Datensatz erhält beim Speichern automatisch eine neue RISM ID.

In der Ansicht des vollständigen Datensatzes: Wenn Sie einen beliebigen Datensatz in Muscat anzeigen, können Sie auf die Schaltfläche „Kopieren“ in der rechten Seitenleiste klicken, um eine Kopie des Datensatzes im Bearbeitungsmodus anzuzeigen.

Katalogisierer können jeden Datensatz in Muscat duplizieren, auch Datensätze, die von einer anderen Bibliothek erstellt wurden. Die Bearbeitungsrechte gelten weiterhin, so dass Katalogisierer keine Datensätze für Institutionen speichern können, für die sie keine Rechte haben. Das Duplizieren von Datensätzen spart Zeit bei der Katalogisierung der eigenen Sammlungen (vor allem, wenn der Inhalt durchweg ähnlich ist), aber Katalogisierer können auch von Datensätzen profitieren, die von anderen Bibliotheken erstellt wurden, vor allem, wenn ein Datensatz umfangreiche Notenincipits enthält oder wenn Nachdrucke mit gleichem oder ähnlichem Inhalt erfasst werden. Es kann jeweils nur ein Datensatz dupliziert werden.

Der Plaine & Easie-Code für jedes Musikincipit kann aus der Vollansicht eines jeden Datensatzes kopiert werden. Klicken Sie einfach auf den Link **PAE Code** oberhalb des Notenincipits und Sie können den angezeigten Incipit-Code kopieren und einfügen.
