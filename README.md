# Human Oversight

**Ein einfaches Framework, damit der Mensch bei der Arbeit mit KI die Kontrolle behält — und den EU AI Act (Art. 14) in der Praxis lebt.**

> 🇬🇧 *English version: [README.en.md](README.en.md)*

---

## Worum geht es?

KI ist schnell und meistens gut. Genau das schafft zwei Probleme:

1. **Man denkt selbst nicht mehr mit.** Wer Ergebnisse ungeprüft übernimmt, verliert mit der Zeit das eigene Urteilsvermögen. Studien zeigen einen klaren Zusammenhang zwischen intensiver, unreflektierter KI-Nutzung und nachlassendem kritischem Denken.
2. **Man startet zu viel auf einmal.** Weil mit KI alles so leicht geht, beginnt man zehn Dinge gleichzeitig — und bringt keins richtig zu Ende.

**Human Oversight** ist ein Framework gegen beides. Es sorgt dafür, dass du jeden Schritt verstehst, jederzeit eingreifen kannst und am Ende die Verantwortung trägst — statt der Maschine blind zu vertrauen.

Das deckt sich mit dem, was der **EU AI Act (Artikel 14)** für wichtige KI-Systeme ohnehin verlangt: echte menschliche Aufsicht, kein bloßes Abnicken.

---

## Die drei Modi

Du musst dir nichts merken — das Framework wählt den passenden Modus automatisch nach Situation. Im Kern sind es drei:

### 1. Planen & Priorisieren
*Bevor du loslegst.*

Du hast zu viele Baustellen? Dieser Modus geht mit dir alle Projekte durch, stellt ehrliche Fragen („Wer zahlt dafür? Was passiert, wenn du es **nicht** machst?") und sortiert alles in vier klare Prioritätsstufen. Dazu ein realistischer Kapazitäts-Check: Was passt überhaupt in deine Woche?

**Die wichtigste Frage:** Willst du etwas Neues starten, obwohl das Wichtigste noch nicht fertig ist? → *„Welches laufende Projekt parkst du dafür?"*

### 2. Transparente Schritte
*Während gearbeitet wird.*

Statt dir einfach ein fertiges Ergebnis hinzulegen, arbeitet die KI Schritt für Schritt — und erklärt jeden davon:

- *„Ich mache jetzt X, weil Y."*
- *„Das ist mein Zwischenstand: …"*
- *„Erkennst du, warum ich diesen Weg gewählt habe statt eines anderen?"*

So bleibst du wach und kannst jederzeit korrigieren, bevor am Ende etwas Fertiges in die falsche Richtung läuft.

### 3. Quality Gate
*Bevor das Ergebnis rausgeht.*

Eine strukturierte Endprüfung, der **RALF-Loop**:

| Schritt | Prüft |
|---------|-------|
| **R**easoning | Ist die Begründung lückenlos? Versteckte Annahmen? |
| **A**nalysis | Wurde alles Relevante berücksichtigt? Gegenargumente? |
| **L**ogic | Widersprüche? Logische Sprünge? |
| **F**actcheck | Stimmen Zahlen, Namen, Quellen? |

Am Ende sagt dir die KI ehrlich, **wo sie am unsichersten ist** — damit du genau dort hinschaust. Und: Nichts gilt als „fertig", bevor du es freigibst. Du kannst jederzeit „Stop" sagen.

---

## Wie nutze ich das?

Du kannst Human Oversight auf drei Wegen einsetzen — such dir den passenden aus:

### A) Als Methode im Kopf (kein Setup)
Lies die drei Modi und wende sie bewusst an. Schon das Wissen „Ich lasse mir den Weg erklären und prüfe das Ergebnis aktiv" verändert, wie du mit KI arbeitest.

### B) Als Baustein in deinem KI-Chat (Copy & Paste)
Kopiere diesen Text an den Anfang deines Chats (z. B. bei ChatGPT, Claude oder Gemini), dann hält sich die KI daran:

```
Du arbeitest nach dem Human-Oversight-Prinzip:
1. Liefere NIEMALS direkt ein Endergebnis. Erkläre zuerst deinen Weg.
2. Zeige Zwischenschritte und stelle eine Verständnisfrage pro Schritt.
3. Warte auf Bestätigung, bevor du weitermachst.
4. Vor dem finalen Ergebnis: Prüfe Reasoning, Analysis, Logic, Factcheck (RALF).
5. Zeige mir, wo du am wenigsten sicher bist.
6. Das Ergebnis ist erst fertig, wenn ich es freigebe.
```

### C) Als Skill in Claude Code / als Workflow-Baustein
Die Datei [`SKILL.md`](SKILL.md) ist das vollständige Framework im Detail. Sie funktioniert direkt als Skill in Claude Code (in den Skills-Ordner legen) und enthält außerdem fertige Bausteine für automatisierte Abläufe (z. B. n8n oder Agenten-Frameworks wie CrewAI).

---

## Für wen ist das?

- **Einzelpersonen & Selbstständige**, die mit KI arbeiten und nicht den Überblick (oder das eigene Urteil) verlieren wollen.
- **Teams**, die KI in Prozesse einbauen und dabei nachvollziehbar bleiben müssen.
- **Unternehmen mit Compliance-Anforderungen** (EU AI Act, DSGVO), die menschliche Aufsicht praktisch umsetzen wollen.

Du brauchst **kein technisches Vorwissen.** Wenn du KI nutzt und gelegentlich denkst „Moment, verstehe ich eigentlich noch, was hier passiert?" — dann ist dieses Framework für dich.

---

## Inhalt dieses Repos

| Datei | Was drin ist |
|-------|--------------|
| [`README.md`](README.md) | Diese Einführung (Deutsch) |
| [`README.en.md`](README.en.md) | English version |
| [`SKILL.md`](SKILL.md) | Das vollständige Framework im Detail (auch als Claude-Code-Skill nutzbar) |
| [`LICENSE`](LICENSE) | Lizenz (CC BY 4.0) |

---

## Lizenz & Urheber

© Claus Zeißler. Lizenziert unter **[Creative Commons CC BY 4.0](LICENSE)** — du darfst das Framework frei nutzen, weitergeben und anpassen, solange du den Urheber nennst.

Mehr: [affairs-consulting.de](https://affairs-consulting.de)
