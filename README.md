<div align="center">

# <img src="https://raw.githubusercontent.com/Querbox/tally-updates/main/icon.png" width="48" align="center" /> Tally Updates

**Auto-Update Server für [Tally](https://github.com/Querbox/tally-app)**

</div>

---

Dieses Repository enthält ausschließlich die **Update-Manifest-Datei** und **Release-Binaries** für den Tally Auto-Updater.

| Datei | Zweck |
|---|---|
| `latest.json` | Update-Manifest mit Version, Signatur und Download-URL |
| Releases | `.tar.gz` (Updater) und `.dmg` (Installer) Binaries |

> **Hinweis:** Der Quellcode von Tally befindet sich nicht in diesem Repository.

## Wie funktioniert's?

```
Tally App → prüft latest.json → Version neuer? → lädt .tar.gz → verifiziert Signatur → installiert Update
```

Das Update-Manifest wird bei jedem Release automatisch durch GitHub Actions aktualisiert.
