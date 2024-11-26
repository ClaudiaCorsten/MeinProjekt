# MeinProjekt
a) Schritte zum Einrichten des GitHub-Repositorys "MeinProjekt"
   
   1. in GitHub angemeldet
   
   2. neues Repository erstellt durch Klick auf +
   
   3. URL des erstellten Repositorys: https://github.com/ClaudiaCorsten/MeinProjekt.git


b) 4. Mein Terminal Git Bash unter Windows geöffnet

   5. ls ~/.ssh/
   
      - verfügbare SSH-Schlüssel überprüft


c) Schritte zum lokalen Klonen des Repositorys, zum Konfigurieren von Git und zum Erstellen der initialen Commits

   8. cd teilprüfung
   
      - in Verzeichnes "Teilprüfung" gewechselt, in dem das Git-Repository erstellt werden soll
   
   9. git clone https://github.com/ClaudiaCorsten/MeinProjekt.git
   
      - GitHub-Repository "MeinProjekt" auf meinen lokalen Rechner geklont
   10. cd MeinProjekt
       - ins geklonte Verzeichnis "MeinProjekt" navigiert
   11. git config user.name "ClaudiaCorsten"
       git config user.email "c-corsten@t-online.de"
       - Git mit meinen Namen und E-Mail konfiguriert
   12. git add index.html
       git commit -m "Initialer Commit"
       - Neue Datei "index.html" hinzugefügt und einen Initial-Commit erstellt
   13. git checkout -b feature
       - einen neuen Branch mit Namen "feature" erstellt.
   14. git add Text/mychanges.txt
       git commit -m "Neue Funktion hinzugefügt"
       - eine weitere Datei hinzugefügt und einen Commit auf dem "feature" Branch erstellt.
   15. git add index.html
       git commit -m "Hauptdatei aktualisiert"
       - zunächst die index.html in indexA.html umbenannt
       - Änderung bestätigt und einen Commit auf dem "Feature"-Branch durchgeführt
   16. git checkout main
       - zurück zum Main-Branch gewechselt
   17. git add index.html
       git commit -m "Hauptdatei aktualisiert
       - index.html umbenannt und einen Commit auf den "main"-Branch durchgeführt
   18. git merge feature
       - "Feature"-Branch in den "main"-Branch gemergt        
