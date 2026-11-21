# Kante – Releases

Hier liegen die veröffentlichten Versionen von Kante, einem schlanken
Browser für Windows 11, und der Update-Kanal unter
<https://kante.vanozoda.com/stable/latest.json>.

- **Installieren:** unter [Releases](https://github.com/vanozoda/kante-release/releases/latest)
  `kante-setup-<Version>.exe` laden und starten. Installiert wird pro
  Benutzer, ohne Administratorrechte.
- **Updates:** Kante prüft den Kanal selbst. Jedes Update ist mit ed25519
  signiert; Kante prüft Signatur und SHA-256, bevor es etwas ersetzt.
- **Fehler** bitte als [Issue](https://github.com/vanozoda/kante-release/issues) melden, **Sicherheitslücken** aber privat, siehe [SECURITY.md](SECURITY.md).

Dieses Repository wird von `cargo xtask publish` geschrieben, nicht von Hand.
