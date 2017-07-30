# Pobieranie programu PuTTy, konfiguracja klienta SSH oraz generowanie kluczy.

### Spis treści:

  - Pobieranie PuTTy
  - Instalacja PuTTy
  - Generowanie klucza SSH
  

# Wstęp:
Użytkownicy systemu Widnows w celu zalogowania się na serwer, potrzebują klienta SSH. Klient SSH umożliwia wygenerowanie klucza, który pozawala nam na bezpieczne i wygodne połączenie z serwerem. Zalecamy używanie darmowej aplikacji PuTTy.

### Pobieranie aplikacji PuTTy

1) W celu pobrania klienta PuTTy otwieramy stronę: [www.putty.org ](http://www.putty.org/). Następnie klikamy na odnośnik "You can download PuTTy here"
 
 ![alt](https://github.com/icin1234/PuTTy/blob/master/putty3.PNG?raw=true)

2) Zalecamy pobranie pełnej paczki instalacyjnej programu PuTTy. 
Następnie zależnie od posiadanej przez nas wersji systemu Windows, wybieramy instalator 32-bit lub 64-bit.

![alt](https://github.com/icin1234/PuTTy/blob/master/putyy4.PNG?raw=true)

> *Jeśli nie jesteśmy pewni jaką posiadamy wersję systemu Windows, twórcy aplikacji PuTTy zalecają zainstalowanie wersji 32-bit.
> [FAQ-PuTTy Wersja](https://www.chiark.greenend.org.uk/~sgtatham/putty/faq.html#faq-32bit-64bit)*

### Instalacja aplikacji PuTTy
1)Uruchamiamy instalator programu PuTTy i klikamy next.

![alt](https://github.com/icin1234/PuTTy/blob/master/next1.PNG?raw=true)

2)Wskazujemy miejsce, w którym chcemy zainstalować program.

![alt](https://github.com/icin1234/PuTTy/blob/master/sciezka.PNG?raw=true)

3)W tym kroku, możemy dodać skrót na pulpicie. Następnie klikamy install.

![alt](https://github.com/icin1234/PuTTy/blob/master/install.PNG?raw=true)

4)Klikamy finish i gotowe. Program PuTTy został poprawnie zainstalowany.
![alt](https://github.com/icin1234/PuTTy/blob/master/finish.PNG?raw=true)


### Konfiguracja i generowanie klucza SSH.

1) Aby wygenerować własny klucz SSH uruchamiamy program o nazwie "puttygen". Aplikacja ta znajduje się w ścieżce docelowej, którą podaliśmy podczas instalacji programu. W moim przypadku jest to: *C:\Program Files\PuTTy*

![alt](https://github.com/icin1234/PuTTy/blob/master/puttygen.PNG?raw=true)

2)Klikamy na przycisk "Generate", a następnie wykonujemy losowe ruchy myszką w obszarze zaznaczonym na niebiesko. Umożliwia to  zebranie losowych danych na podstawie których zostaną wygenerowane klucze.

![alt](https://github.com/icin1234/PuTTy/blob/master/gen.PNG?raw=true)

3) W kolejnym kroku podajemy frazę zabezpieczającą dla wygenerowanych kluczy. Następnie zapisujemy klucz publiczny i prywatny.

![alt](https://github.com/icin1234/PuTTy/blob/master/key.PNG?raw=true)

4)Wygenerowany klucz publiczny kopiujemy.

![alt](https://github.com/icin1234/PuTTy/blob/master/key2.PNG?raw=true)

5)Nasz skopiowany klucz, dodajemy w panelu rootbox. 
W tym celu logujemy się do [Panelu](https://panel.rootbox.com/login). W prawym górnym rogu klikamy na ikonę ustawienia, a następnie otwieramy zakładkę "ssh keys"

![alt](https://github.com/icin1234/PuTTy/blob/master/sshdod.PNG?raw=true)
