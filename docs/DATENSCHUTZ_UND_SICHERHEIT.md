# Datenschutz und Sicherheit – Arbeitsstand

Die Anwendung verwaltet lokale Benutzerkonten, Passwort-Hashes, Aufgaben und eventuell Dateipfade. Dadurch können personenbezogene Daten entstehen. Die Datenbank liegt lokal im Windows-Benutzerprofil.

- Keine Datenbanken, persönlichen Logs oder Zugangsdaten nach GitHub hochladen.
- Vor betrieblicher Nutzung Zugriffsrechte, Datensicherung, Löschkonzept und Zuständigkeiten prüfen.
- Kein automatischer Backup- oder Update-Dienst.
- Keine Zertifizierung für sicherheitskritische Aufgaben.
- Passwörter werden mit bcrypt gehasht; die Anwendung wurde nicht unabhängig sicherheitsgeprüft.

Dieses Dokument ist keine finale Datenschutzerklärung.
