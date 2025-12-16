# Mi az a GIT és GITHUB

## Git
A git egy elossztott verziókezelő rendszer, amelyet Linus Torvald fejlesztettt 20005-ban. Lehgetővé teszi:
- Kódváltozások nyomon követését
- Korábbi kódverziókhoz való visszatérés
- Párhuzamos fejlesztést branch-eken
- OffLine munka a teljes projekt történelméval

## GitHub
A GItHub egy felhőalapú platform Git repository-k tárolására és kezekléásére. Funkciói:
- Repository hosting
- Egyműködési eszközök (Issue, Pull Request)
- CI/CD Integráció (GitHub Actions)
- Projektmenedzsment (PRojects, Millentones)
- Kód review és biztonság


> összefoglalva</br>
**Git** - verziókezelő eszköz a gépeden **GitHub** - online platform a repository-k tárolására

## Miért érdemes megtanulni?
 - Csapatmunka (Több fejlesztő dolgozhat ugyanazon a projekten)
 - Biztonság (kód biztonságos tárolása, pl nem vész el)
 - Történet (Minden változás visszakövethető)
 - Visszaállítás (Bármikor visszatérhetünk a korábbi verzióhoz)
 - Iparági standard (a legtöbb cég **elvárja** a Git ismeratét)
 
 ## Telepítés

 ### Ellenörzés

 >git --version
 >git version

 ## Git alapvető parancsok

 ### Lokális repository létrehozása

 git init

 git add .

 git commit -m ""

 git log

 git reset HEAD~1

 git status

git remote add origin https://github.com/papprichard/git.git
git branch -M main
git push -u origin main