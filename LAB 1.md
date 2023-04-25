# Ćwiczenie nr 1

## (1-2)
* Włączam program Putty oraz loguje się do systemu

## 3
* Za pomocą komendy `ssh-keygen` generuje klucz RSA (w trakcie tworzenia trzykrotnie klikam enter bez wypełniania pól.
* Szukam wygenerownych kluczy, następnie za pomocą komedny `ssh-copy-id` kopiuje klucz publiczny.
* Z konsoli mts-a loguję się na swoje konto studenckie za pomocą komendy `ssh apuc@student.agh.edu.pl`
* Analizuję procedruę autentykacji i szukam lokalizacji klucza publicznego.

## 4 
* Tworzę katalog o nazwie "tmp"

![image](https://user-images.githubusercontent.com/92114245/234362294-e351c5bb-f4df-423a-bb8c-bb3a18fd63e5.png)

* Tworzę plik "Test" zawierający moje Imię i Nazwisko

![image](https://user-images.githubusercontent.com/92114245/234362774-9b6e359b-78ef-4eeb-ac2a-8febc498ccb5.png)

![image](https://user-images.githubusercontent.com/92114245/234363328-fa0624f9-3d97-415e-9170-3dae1d86bbbc.png)

* Powstały plik ma prawa pozwalające na czytanie dla wszystkich użytkowników

![image](https://user-images.githubusercontent.com/92114245/234363479-9350cb7d-682e-4bb7-9107-bfd8b6ccc7ee.png)

* Komendą `chmod go-r Test` zabieram uprawnienia do czytania pliku "Test"

![image](https://user-images.githubusercontent.com/92114245/234364688-756570a4-ff6f-4e93-83c7-b3274c067b6e.png)

## 5
* Za pomocą komendy `ps` wyświetlam procesy

![image](https://user-images.githubusercontent.com/92114245/234365274-0633499a-0188-4ab9-809e-591bbbaeb7b4.png)

## 6
* Za pomocą komendy `who` sprawdzam ilu użytkownikó pracuje na serwerze,a następnie za pomocą komendy `who | wc -l` otrzymujemy systemowo obliczoną ilość aktywnych użytkowników 

![image](https://user-images.githubusercontent.com/92114245/234367350-c474441e-6ad0-448a-a992-498829ba7aa4.png)

## 7 
* Za pomocą komendy `passwd` możemy zmienić nasze hasło. Hasło było już zmieniane, dlatego nie robię tego ponownie.

## 8
* Za pomocą komendy `find / -name passwd` możemy znaleźć plik o nazwie "passwd"

![image](https://user-images.githubusercontent.com/92114245/234368751-c7dd91e2-b983-40c3-836b-858f776928d0.png)

## 9
* Za pomocą komendy `pwd` jest wyświetlana obecna lokalizacja 

![image](https://user-images.githubusercontent.com/92114245/234369055-16842255-db26-45ad-a38c-b90fa671fb83.png)

## 10
* Za pomocą komendy `echo "Adam Puc" > test2` tworzę nowy plik i przekierowuję jego wartość do pliku "test2"

![image](https://user-images.githubusercontent.com/92114245/234374638-747e1518-d507-44e4-97eb-8b88d3e2cf83.png)

## 11
* Przeglądam opis komendy `rm` pozwalającej na usuwanie plików i katalogów. Po wpisaniu komendy `rm -r tmp` zostanie usunięty cały katalog "tmp" łącznie z zawartością.

![image](https://user-images.githubusercontent.com/92114245/234376331-6a4c6892-8c02-426d-ac1f-8bce0c3750f5.png)

## 12
* Tworzę katalog do publikowania stron WWW zgodnie z opisem 

## 13
* Tworzę plik tekstowy "tmp.txt"

## 14
* W utworzonym pliku umieszczam poniższy tekst

![image](https://user-images.githubusercontent.com/92114245/234377227-fa551453-bf72-45bf-a5de-a2a875f79141.png)

## 15
* Za pomocą komendy `mv tmp.txt index.html` przenoszę zawartość pliku "tmp.txt" do pliku "index.html"

![image](https://user-images.githubusercontent.com/92114245/234377761-35280b07-1a93-4aa5-a2c0-a447a36081db.png)

## 16
* Sprawdzam prawa dostępu do pliku "index.html"

![image](https://user-images.githubusercontent.com/92114245/234378123-d7ebe06b-386c-4aa9-a0b9-b34c01175528.png)

## 17
* Plik "tmp.txt" został usunięty podczas przenoszenia zawartości do pliku "index.html"

## 18
* Stosując komendę `wc -l index.html` zostanie policzona programowo ilość linijek w pliku "index.html"

![image](https://user-images.githubusercontent.com/92114245/234378520-342f7ae5-310a-406e-b240-09f3874f26e6.png)

## 19
* Sprawdzam czy moja strona działa poprawnie. Polskie znaki pokazują się poprawnie 

![image](https://user-images.githubusercontent.com/92114245/234378968-9c3b66b6-5c41-40ea-8e30-8e20a03cad0f.png)

## 20
* Z pliku "index.html" usuwam linię ze znacznikiem META. Sprawia ona, że polskie znaki wyświetlają się niepoprawnie 

![image](https://user-images.githubusercontent.com/92114245/234387575-fd243d0f-b169-479c-8fc3-9a3d6d4bdd96.png)
![image](https://user-images.githubusercontent.com/92114245/234387661-18a453d1-16ff-4a36-b2db-eec45db0813e.png)

## 21 
* Zmieniejąc prawa dostępu do pliku "index.html" i katalogu w któym się znajduje "public_html" możemy sprawić, że strona nie będzie działać poprawnie. Minimalne prawa dla pliku to prawa odczytu dla reszty użytkowników, dla katalogu to prawo wykonania dla użytkowników, aby strona działała poprawnie

![image](https://user-images.githubusercontent.com/92114245/234388944-2b10da70-11f3-4cc3-bb9c-3aefd4603c6b.png)
![image](https://user-images.githubusercontent.com/92114245/234388980-0dc60524-1d91-43c8-8f82-dad2e01e9960.png)

![image](https://user-images.githubusercontent.com/92114245/234389899-a5239820-d999-4c59-b90a-764d40e3c195.png)
![image](https://user-images.githubusercontent.com/92114245/234389846-fbdd55f6-bb79-4628-a606-7c02a7870dd9.png)

## 22
* Widać, że po swtorzeniu skompresowanego pliku zmienia on kolor

![image](https://user-images.githubusercontent.com/92114245/234392278-96c95d44-790d-470b-87bb-f353fcc2a93b.png)

## 24
* Wykonuję modyfiakcje zgodnie z poleceniami






















