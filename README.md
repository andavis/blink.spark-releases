# blink.spark – Releases

Dieses Repository enthält nur die Installationsdateien von blink.spark (macOS und Windows, jeweils für Apple Silicon/ARM und Intel/x64).

## Installation und Update

### macOS

Im Terminal:

```sh
curl -fsSL https://github.com/andavis/blink.spark-releases/releases/latest/download/install.sh | bash
```

Das Skript lädt die neueste Version nach `/Applications` (oder `~/Applications`) und startet sie. Für ein Update
denselben Befehl erneut ausführen; blink.spark vorher beenden.

### Windows (Vorschau, noch nicht auf allen Rechnern erprobt)

Voraussetzungen: [Git for Windows](https://git-scm.com/download/win) (bringt Git Bash mit, das blink.spark braucht),
[Node.js 22 oder neuer](https://nodejs.org/en/download) und [Claude Code](https://docs.claude.com/claude-code)
(danach einmal `claude` starten und anmelden).

In PowerShell:

```powershell
irm https://github.com/andavis/blink.spark-releases/releases/latest/download/install.ps1 | iex
```

Das Skript lädt die neueste Version nach `%LOCALAPPDATA%\Programs\blink.spark`, legt einen Eintrag im Startmenü an
und startet sie. Für ein Update denselben Befehl erneut ausführen; blink.spark vorher beenden.

Die App ist nicht signiert. Falls Windows SmartScreen beim Start warnt: „Weitere Informationen“ → „Trotzdem ausführen“.
