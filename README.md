# IPT1 · Lernsession 03 · GitHub-Flow & Markdown

> **Name:** _Numa_  
> **Datum:** _08.09.2026_

## Ziel

Ich kann die wichtigsten Begriffe rund um **Git**, **GitHub**, den **GitHub-Flow** und **Markdown** kurz erklären und meinen Lernfortschritt mit einem eigenen README dokumentieren.

> **Hinweis:** Ersetze die Platzhalter `DEINE ANTWORT` durch deine eigenen kurzen Antworten. Committe die ausgefüllte Datei anschliessend mit einer aussagekräftigen Commit-Nachricht.

---

## 1 · Git und GitHub verstehen

### 1. Was ist Git?

**Meine Antwort:** Git ist ein Tool. Es ist eine Lokale Versionsverwaltung.

### 2. Was ist GitHub?

**Meine Antwort:** Github ist eine Cloudbasierte Platform, wo personen ihre Repositorys für andere Leute hochladen.

### 3. Was ist der wichtigste Unterschied zwischen Git und GitHub?

**Meine Antwort:** Git ist das Werkzeug auf deinem Computer, GitHub ist der Online Dienst im Internet.

### 4. Funktioniert Git auch ohne GitHub?

**Meine Antwort:** Ja, Git funktioniert komplett lokal.

### 5. Was ist ein Repository (Repo)?

**Meine Antwort:** Ein Projektordner, der alle Dateien sowie die komplette Versionshistorie enthält.

### 6. Was ist der `main`-Branch?

**Meine Antwort:** Der Hauptzweig des Repositories (aktueller Build)

### 7. Was ist Markdown?

**Meine Antwort:** eine Textsprache sowie ein File Type.

### 8. Was bedeutet GitHub-Flavoured Markdown (GFM)?

**Meine Antwort:** Eine von GitHub erweiterte Markdown Variante.

---

## 2 · GitHub-Flow

### 9. Bringe die Schritte in die richtige Reihenfolge

`Commit · Issue · Pull Request · Branch`

**Meine Antwort:** Issue → Branch → Commit → Pull Request

### 10. Was ist ein Issue?

**Meine Antwort:** Eine Aufgabe im Repository.

### 11. Was ist ein Branch?

**Meine Antwort:** Ein isolierter Arbeitszweig getrennt von dem Stable Build.

### 12. Warum arbeitet man für eine Änderung häufig auf einem eigenen Branch?

**Meine Antwort:** Damit die Aktuelle funktionierende Version nicht beschädigt wird.

### 13. Was ist ein Commit?

**Meine Antwort:** wie ein gespeicherter Snapshot

### 14. Wozu dient eine Commit-Nachricht?

**Meine Antwort:** Sie beschreibt, was geändert wurde

### 15. Was ist ein Pull Request?

**Meine Antwort:** Ein Antrag, die Änderungen eines Branches in einen anderen Branch zusammenzuführen.

### 16. Was bedeutet Review?

**Meine Antwort:** Die Überprüfung des Codes

### 17. Was bedeutet Merge?

**Meine Antwort:** Änderungen aus einem Branch -> Hauptzweig.

### 18. Wann sollte ein Pull Request gemergt werden?

**Meine Antwort:** Wenn die Änderungen getestet, korrigiert und im Review fregegeben wurden.

---

## 3 · Wichtige Git-Begriffe und Befehle

### 19. Was bedeutet Push?

**Meine Antwort:** Hochlanden von Lokal --> Online Repo.

### 20. Was bedeutet Pull?

**Meine Antwort:** Herunterladen von Onlnine Änderungen --> Lokal.

### 21. Was ist der Unterschied zwischen Commit und Push?

**Meine Antwort:** Commit speichert lokal auf deinem Rechner, Push überträgt die Speicherung auf GitHub.

### 22. Was ist der Unterschied zwischen Pull und Pull Request?

**Meine Antwort:** Pull lädt Daten lokal herunter, eine Pull Request ist ein Antrag auf GitHub, Zweige zusammenzuführen.

### 23. Was bedeutet Clone?

**Meine Antwort:** Das "Klonen" eines Repositories auf den Computer.

### 24. Was macht `git status`?

**Meine Antwort:** zeigt aktuellen Stand des Repositories.

### 25. Was macht `git add`?

**Meine Antwort:** Vorebereiten von geänderten Dateien für den Commit. (Staging Area)

### 26. Was ist die Staging Area?

**Meine Antwort:** Der virtuelle Zwischenbereich, in dem Dateien für den nächsten Commit gesammelt werden.

### 27. Was macht `git log`?

**Meine Antwort:** Zeigt den Verlauf aller Commits an.

### 28. Was bedeutet Branch wechseln?

**Meine Antwort:** Umschaltung auf einen anderen Arbeitszweig

### 29. Speichert `git add` bereits eine neue Version?

**Meine Antwort:** Nein, es merkt sich die Dateien nur für die Vorbereitung.

### 30. Speichert `git push` deine noch nicht committeten Dateiänderungen?

**Meine Antwort:** ein, git push lädt nur bereits erstellte Commits hoch.

---

## 4 · GitHub-Flow praktisch erklären

### 31. Erkläre den GitHub-Flow in einem kurzen Satz.

**Meine Antwort:** Ein Workflow, bei dem man Änderungen isoliert auf einem Branch entwickelt und über Pull Requests nach einer Prüfung in den main Branch übernimmt.

### 32. Ordne die Begriffe zu

| Bedeutung | Git-/GitHub-Begriff |
|---|---|
| Aufgabe | Issue |
| Arbeitszweig | Branch |
| Speicherpunkt | Commit |
| Änderungsantrag | Pull Request |
| Zusammenführen | Merge |

### 33. Welche Richtung beschreibt Push?

**Meine Antwort:** Von Lokal --> Cloud

### 34. Welche Richtung beschreibt Pull?

**Meine Antwort:** Von Cloud --> Lokal

### 35. Warum sind mehrere sinnvolle Commits oft besser als ein einziger riesiger Commit?

**Meine Antwort:** Änderungen bleiben übersichtlicher, beii Fehlern leichter rückgängig.

### 36. Nenne ein Beispiel für eine gute Commit-Nachricht.

```text
Fragen im README ausfuellen.
```

### 37. Warum ist die Commit-Nachricht `update` wenig hilfreich?

**Meine Antwort:** Weil es nicht sagt, welche Datein oder welche Inhalte geändert wurden.

---

## 5 · Markdown und README

### 38. Überschrift Ebene 1

Ergänze darunter eine Markdown-Überschrift der Ebene 1:

# Mein Portfolio

### 39. Ungeordnete Liste

Erstelle eine Liste mit mindestens drei Begriffen aus dieser Lernsession:

- Git
- GitHub
- Commit

### 40. Link

Erstelle einen funktionierenden Markdown-Link zu GitHub oder Microsoft Learn:

[Zu GitHub](https://github.com)

### 41. Bild

Schreibe die Markdown-Syntax für ein Bild mit Alternativtext:


![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)


### 42. Inline-Code

Schreibe `git status` als Inline-Code in einem sinnvollen Satz:

Mit dem Befehl git status kann ich geänderte Dateien einsehen.

### 43. Codeblock

Ergänze mindestens drei Git-Befehle in diesem Codeblock:

```bash
git status
git add .
git commit -m "docs: README ergänzen"
```

### 44. Was sollte ein gutes Portfolio-README mindestens leisten?

**Meine Antwort:** Es informiert schnell und verständlich über den Inhalt des Projekts, den Entwickler und die Nutzung.

---

## 6 · Mein fachlicher Lernnachweis

### Was habe ich heute über Git und GitHub gelernt?

Ich habe den Unterschied zwischen Git und GitHub verstanden und gelernt, wie der GitHub-Flow (Branch, Commit usw...)

### Was habe ich heute praktisch umgesetzt?

Ich habe ein README-Template im Repository bearbeitet, Markdown-Formatierungen angewendet.

### Meine konkrete Verbesserung aus dem Selbst- oder Peer-Check

Aussagekräftigere Commit-Nachrichten schreiben (nicht nur die von Copilot)

### Mein nächster Portfolio-Schritt

README-Qualitätscheck

---

## 7 · Microsoft Learn · Abschlusskontrolle

- [ ] **Einführung in GitHub**: Übung, Modulbewertung und Zusammenfassung abgeschlossen
- [ ] **Effektive Kommunikation auf GitHub mithilfe von Markdown** abgeschlossen
- [ ] Ich habe meinen Lernfortschritt / meine Modulbewertung kontrolliert.

## 8 · Begriffe · deutsche Merkhilfe

Fülle die zweite Spalte mit einer kurzen deutschen Merkhilfe aus.

| Begriff | Deutsche Merkhilfe |
|---|---|
| Issue | DEINE ANTWORT |
| Branch | DEINE ANTWORT |
| Commit | DEINE ANTWORT |
| Push | DEINE ANTWORT |
| Pull | DEINE ANTWORT |
| Pull Request | DEINE ANTWORT |
| Review | DEINE ANTWORT |
| Merge | DEINE ANTWORT |
| Clone | DEINE ANTWORT |
| Repository | DEINE ANTWORT |

---

## 9 · Selbstcheck

- [ ] Ich kann **Git** und **GitHub** unterscheiden.
- [ ] Ich kann **Issue → Branch → Commit → Pull Request → Merge** erklären.
- [ ] Ich kenne den Unterschied zwischen **Commit** und **Push**.
- [ ] Ich kenne den Unterschied zwischen **Pull** und **Pull Request**.
- [ ] Ich kann Überschriften, Listen, Links, Bilder und Codeblöcke in Markdown verwenden.
- [ ] Mein README wird auf GitHub korrekt gerendert.
- [ ] Ich habe mindestens eine konkrete Verbesserung umgesetzt.
- [ ] Ich habe meine Änderung mit einer aussagekräftigen Commit-Nachricht dokumentiert.

## Meine Commit-Nachricht für diese Abgabe

```text
DEINE COMMIT-NACHRICHT
```
