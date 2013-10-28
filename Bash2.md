### Laboratorium 2

W katalogu c utwórz plik program.c zawierający co najmniej 10 linii kodu napisanego w języku C. (Sam kod należy wyszukać i pobrać z sieci.)

```sh
cd temp/nauka/c
nano program.c
```

1\. Wyświetl na ekran 2 pierwsze wiersze pliku program.c. (head)
```bash
head -2 program.c
```
2\. Wyświetl na ekran 4 ostatnie wiersze pliku program.c. (head, tail)
```bash
tail -4 program.c
```
3\. W pliku program.c znajdź wszystkie wiersze z wystąpieniem słowa „main”. (grep)
```bash
grep main program.c
```

4\. Plikowi program.c nadaj następujące uprawnienia: właściciel – czytanie, pisanie, grupa – czytanie, pozostali użytkownicy: brak uprawnień. (chmod)
```bash
chmod 640 program.c
```

5\. Będąc w katalogu temp przenieś katalog wazne-sprawy do katalogu praca.
```bash
cd ../../
mv dom/wazne-sprawy praca
```

6\. Zarchiwizuj cały katalog temp. (zip i tar)
```bash
tar -cf temp.tar temp
```

7\. Usuń katalog temp.
```bash
rm -r temp
```

8\. Odtwórz z archiwum katalog temp. (unzip i tar)
```bash
tar -xf temp.tar
```

9\. Posprzątaj na swoim koncie.
```bash
rm temp.tar
mv temp/praca/wazne-sprawy/ temp/dom/
```

10\. Wyświetl linijki z pliku program.c (3 i 4 licząc od początku tekstu).
```bash
head -n4 program.c | tail -n2
```
11\. Wyświetl linijki z pliku program.c (5 i 6 licząc od końca tekstu).
```bash
tail -n 6 program.c | head -n 2
```
