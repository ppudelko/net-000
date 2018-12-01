**Dokument opisuje piersze kroki z GitHub'em:** 
![](https://github.com/ppudelko/net-000/tree/master/PNG/remarkable.png) 

[pp sobota, 01. grudnia 2018 06:40] 


linki:
https://www.youtube.com/watch?v=xw4EVrJZjAY - GitHub [PL]
http://www.codebind.com/linux-tutorials/basic-git-commands-list/ - tutorial GitHub [EN]
https://git-scm.com/book/pl/v1/ -dokumentacja GitHub [PL]


Podstawowe kroki aby używać GitHub'a:

0. Plik projektu:
Do tworzenie/edycji pliku używaj edytora plików "markdown", /lista na końcu/ plik nazwij "NazwaPliku.md"

1. Stwórz konto używając konta email na GitHub'ie:
https://github.com/

2. Dodaj za pomocą web'a swoje repozytorium, nazwa repozytorium. 
    Repozytorium ustaw jako 'Publiczne"

3. Zainstaluj klienta GitHub dla systemu operacyjnego: Windows/Linux/MacOS

4. Uruchom z cli klienta GitHub

git config --global user.name "NickName"
git config --global user.email "email"

4.1 Inne polecenia z cli
przejdź do folderu gdzie ma być dodane repozytorium projektu GitHub :

git clone <URL>
gdzie <URL> - kopiujesz z web GitHub link repo 

5. W folderze repozytorium lokalnym utwórz pliki lokalnie by potem je przesłać/dodać do repozytorium na sieci

- lokalnie przy pomocy edytora plików "markdown" na dysku lokalnym w repozytorium lokalnym dodaj  i edytuj plik np. NazwaPliku .md
- publikuj pliku .md na repozytorium publiczne, przejdź do folderu repozytorium WAŻNE!:

cd <folder repozytorium lokalne> 
git add NazwaPliku.md

- zatwierdź zmiany w lokalnym repo, ważne żeby podawać komentarz w „commit” poprawny; czego zmiany dotyczyły będzie to potem wyświetlane:

git commit -m "dodalem rozdzial xx" NazwaPliku.md

-wyślij plik do repozytorium publicznego:

git push -u origin master

7.  Synchorinzacja repozytorium zdalnego z repozytarium lokalnym /zrob przed zmianami loklanymi koniecznie!/ 
 git pull origin master
 

7. Historia rewizji
https://git-scm.com/book/pl/v1/Podstawy-Gita-Podgl%C4%85d-historii-rewizji

 git log


7. Inne przydatne informacje:
a) W przypadku problemów z wysyłaniem lokalnego repozytorium do publicznego komenda:
"git push", usuń repozytorium lokalne i zrób clone'a lokalnie repozytorium publicznego "git clone

b) MarkDown editor:
https://itsfoss.com/best-markdown-editors-linux/
http://remarkableapp.github.io/index.html 
