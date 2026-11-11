# Ludmanager – Windows-Beweislauf

Öffentlich, damit die GitHub-Runner ohne Minutenabrechnung laufen. Hier steht
**kein Produktcode**: nur der eine Workflow, der das veröffentlichte
Windows-Artefakt installiert, prüft und wieder deinstalliert (Gate 3 in
Ticket 35/44 der Produktplanung).

- Quelle des Artefakts: privates Repo `dalu951/ludmanager-desktop`, Release `win-0.1.0`
- Zugriff: über `secrets.INSTALLER_TOKEN` (nur Lesen), damit das Artefakt privat bleibt
- Start: Actions → „Windows-Installer prüfen" → Run workflow (Eingabe leer = Repository-Variable)
