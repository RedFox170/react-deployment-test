Wie kann ich meine React App mit github veröffentlichen?

1. Repo erstellen (leer - ohne Readme ohne gitignore)
2. im Verzeichnis vom zu Veröffentlichen Repo:

git remote set-url origin <ssh-adresse von eurem neu erstellen Repo>

2.5 Zum Prüfen:
git remote get-url origin
Jetzt müsst ihr die Adresse von eurem neu erstellen Repo sehen

3. jetzt das lokal geclonte Repo auf euer github-Repo pushen:
   git push -u origin main
