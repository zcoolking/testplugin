# Crelay SMP Plugin

Ein kleines Paper-SMP-Plugin fuer Minecraft 1.21.11 Server.

Branding im Plugin: `Crelay Test für Bewerbung`

## Funktionen

- Konfigurierbare Join-Nachricht
- `/serverplugin` oder `/sp` fuer Plugin-Infos
- `/smp` fuer SMP-Infos
- `/rules` oder `/regeln`
- `/sethome` und `/home`
- `/setspawn` und `/spawn`
- `/tpa`, `/tpaccept`, `/tpdeny`
- `/heal [spieler]`
- `/feed [spieler]`
- Permissions fuer Admins

## Bauen

Installiere Java 21 und Gradle. Danach im Projektordner:

```powershell
gradle build
```

Die fertige `.jar` liegt danach in:

```text
build/libs/ServerPlugin-1.1.0.jar
```

## Installieren

1. Paper-Server fuer Minecraft 1.21.11 starten.
2. Die `.jar` in den `plugins`-Ordner kopieren.
3. Server neu starten.
4. Optional `plugins/ServerPlugin/config.yml` bearbeiten.

## Permissions

- `serverplugin.admin`
- `serverplugin.heal`
- `serverplugin.feed`
- `serverplugin.setspawn`
