# Pobieranie programu PuTTy i generowanie kluczy SSH.

# Spis treści:

- Wstęp
- Pobieranie aplikacji PuTTy
- Instalacja aplikacji PuTTy
- Generowanie klucza SSH
- Dodawanie klucza SSH do panelu oraz aplikacji

# Wstęp:
Użytkownicy systemu Widnows w celu zalogowania się na serwer w prosty i bezpieczny sposób, potrzebują klienta SSH. Zalecamy używanie darmowej aplikacji PuTTy. Pozwala wygenerować nam własny klucz SSH a także umożliwia połączenie z naszym serwerem w szybki i chroniony sposób. 

### Pobieranie aplikacji PuTTy

1) W celu pobrania klienta PuTTy otwieramy stronę: [www.putty.org ](http://www.putty.org/). Dalej klikamy na odnośnik **"You can download PuTTy here"**
 
 ![alt](https://github.com/icin1234/PuTTy/blob/master/putty3.PNG?raw=true)

2) Zalecamy pobranie pełnej paczki instalacyjnej programu PuTTy. 
Następnie zależnie od posiadanej przez nas wersji systemu Windows, wybieramy instalator 32-bit lub 64-bit.

![alt](https://github.com/icin1234/PuTTy/blob/master/putyy4.PNG?raw=true)

> Jeśli nie jesteśmy pewni jaką posiadamy wersję systemu Windows, twórcy aplikacji PuTTy zalecają zainstalowanie wersji 32-bit. [FAQ-PuTTy Wersja](https://www.chiark.greenend.org.uk/~sgtatham/putty/faq.html#faq-32bit-64bit)

### Instalacja aplikacji PuTTy
1)Uruchamiamy instalator programu PuTTy i klikamy next.

![alt](https://github.com/icin1234/PuTTy/blob/master/next1.PNG?raw=true)

2)Wskazujemy miejsce, w którym chcemy zainstalować program.

![alt](https://github.com/icin1234/PuTTy/blob/master/sciezka.PNG?raw=true)

3)W tym kroku, możemy dodać skrót na pulpicie. Następnie klikamy "install".

![alt](https://github.com/icin1234/PuTTy/blob/master/install.PNG?raw=true)

4)Klikamy "finish" i gotowe program PuTTy został poprawnie zainstalowany.
![alt](https://github.com/icin1234/PuTTy/blob/master/finish.PNG?raw=true)


### Generowanie klucza SSH

1) Aby wygenerować własny klucz SSH uruchamiamy program o nazwie **"puttygen"**. Aplikacja ta znajduje się w ścieżce docelowej, którą podaliśmy podczas instalacji programu. W moim przypadku jest to: *C:\Program Files\PuTTy*

![alt](https://github.com/icin1234/PuTTy/blob/master/puttygen.PNG?raw=true)

2)Klikamy na przycisk **"Generate"**, a następnie wykonujemy losowe ruchy myszką w obszarze zaznaczonym na niebiesko. Umożliwia to  zebranie losowych danych na podstawie których zostaną wygenerowane klucze.

![alt](https://github.com/icin1234/PuTTy/blob/master/gen.PNG?raw=true)

3) W kolejnym kroku podajemy frazę zabezpieczającą dla wygenerowanych kluczy. Następnie zapisujemy klucz publiczny i prywatny.

![alt](https://github.com/icin1234/PuTTy/blob/master/key.PNG?raw=true)

4)Wygenerowany klucz publiczny kopiujemy.

![alt](https://github.com/icin1234/PuTTy/blob/master/key2.PNG?raw=true)

### Dodawanie klucza SSH do panelu oraz aplikacji

1)Nasz skopiowany klucz publiczny, dodajemy w panelu rootbox. 
W tym celu logujemy się do [Panelu](https://panel.rootbox.com/login), w prawym górnym rogu klikamy na ikonę ustawienia. Następnie otwieramy zakładkę **"ssh keys"**

![alt](https://github.com/icin1234/PuTTy/blob/master/sshdod.PNG?raw=true)

2)Klikamy na przycisk **"Utwórz nowy"**...

![alt](https://github.com/icin1234/PuTTy/blob/master/addkey2.PNG?raw=true)

3)Wpisujemy nazwę naszego klucza, wklejamy go w zaznaczone pole i klikamy **"Add SSH Key"**

![alt](https://github.com/icin1234/PuTTy/blob/master/addkey3.PNG?raw=true)

4)Klucz prywatny dodajemy w ustawieniach autoryzacji klienta SSH. Aby to  wykonać **uruchamiamy aplikacje PuTTy**, aplikacja znajduje sie w folderze wskazanym przez nas podczas instalacji, a więc w moim przypadku jest to: *C:\Program Files\PuTTy*.
Po lewej stronie aplikacji **rozwijamy zakładkę SSH...**

![alt](https://github.com/icin1234/PuTTy/blob/master/putty1.PNG?raw=true)

5)Wybieramy opcję **Auth**, a w dalszej kolejności klikamy na przycisk "**Browse...**"

![alt](https://github.com/icin1234/PuTTy/blob/master/putty2_1.PNG?raw=true)

6)Wskazujemy miejsce zapisania naszego klucza prywatnego. Klucz prywatny zapisywaliśmy w punkcie 3 roździału **"Generowanie klucza SSH"**

![alt](https://github.com/icin1234/PuTTy/blob/master/sshmiejsce.PNG?raw=true)

### Gratulacje! Właśnie wygenerowałeś własne klucze SSH. Teraz czas na założenie serwera i pierwsze logowanie za pomocą aplikacji PuTTy!
