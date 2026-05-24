# Opis mini projektu

Ten folder zawiera dokumentację projektu. Uzupełnij ją własnymi notatkami z pracy w Git.

W projekcie powinny znaleźć się:

- opis celu projektu,
- lista najważniejszych komend Git,
- opis trzech branchy,
- krótka informacja, czego nauczyłeś/nauczyłaś się podczas pracy.

### Podstawowe komendy Git, których używam w projekcie:

* **git init** – tworzy nowe, lokalne repozytorium Git w folderze z projektem.
* **git status** – sprawdza stan plików (pokazuje, co zmieniliśmy, a co jest gotowe do zapisu).
* **git add .** – dodaje wszystkie zmienione pliki do poczekalni (staging area) przed zapisem.
* **git commit -m "opis"** – tworzy punkt zapisu (commit) w historii projektu z krótkim wyjaśnieniem, co zrobiliśmy.
* **git branch -M main** – ustawia domyślną, główną gałąź projektu o nazwie "main".
* **git switch -c nazwa-brancha** – tworzy nową gałąź roboczą i od razu się na nią przełącza.
* **git switch nazwa-brancha** – pozwala na szybkie przełączanie się między istniejącymi gałęziami.
* **git remote add origin link** – łączy nasze lokalne repozytorium z serwerem na GitHubie.
* **git push -u origin nazwa** – wysyła nasze commity z lokalnego komputera do zdalnego repozytorium w internecie.
* **git merge nazwa-brancha** – łączy zmiany z gałęzi roboczej z powrotem do gałęzi głównej.