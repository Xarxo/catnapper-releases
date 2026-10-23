# Catnapper Releases

Signierte Update-Pakete der Browser-Erweiterung **Catnapper NBA** (Sleeper, Liga ChickenBreak).

- `stable.json` – stabiler Kanal (Standard)
- `beta.json` – Testkanal

Die installierte Erweiterung lädt diese Dateien, prüft die ECDSA-P-256-Signatur gegen den eingebauten öffentlichen Schlüssel und führt nur gültig signierte Pakete aus. Die Pakete enthalten ausschließlich Catnapper-Code und exakte Patch-Anker; Sleepers eigener Code wird hier nicht verteilt.

Diese Dateien werden mit `npm run release` aus dem (privaten) Quellprojekt erzeugt. Bitte nicht von Hand bearbeiten – jede Änderung macht die Signatur ungültig.
