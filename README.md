<h1>I. HTML - hipertekstowy język znaczników</h1>
https://chat.openai.com/chat
https://beta.openai.com/playground
Struktura dokumentu wg. specyfikacji HTML5 (nagłowek dokumentu, ciało dokumentu), DOM - model obiektowy dokumentu.
Wybrane elementy języka HTML5 - elementy blokowe (nagłówki, akapity, listy, grupowanie znaczników za pomocą div), elementy wstawiane, elementy osadzone, odsyłacze.
Tabele w HTML5 (tabele proste, wymiarowanie tabel, scalanie tabel).
Formularze (ramy formularza, pola wprowadzania danych, pola wyboru, typu radio, password,  lista rozwijalna, nowe typy pól formularza w HTML5).


Struktura dokumentu HTML5 składa się z nagłówka (head) i ciała (body). Nagłówek zawiera informacje metadanych, 
takie jak tytuł i opis strony, a ciało zawiera treść strony.
DOM (Model Obiektowy Dokumentu) jest to reprezentacja dokumentu HTML jako drzewa obiektów, umożliwiająca programistom manipulowanie elementami na stronie.

Wybrane elementy języka HTML5 to:

Elementy blokowe: nagłówki (h1-h6), akapity (p), listy (ul, ol, li), div (grupowanie znaczników).
Elementy wstawiane: np. obrazki (img), pliki dźwiękowe (audio), filmy (video).
Elementy osadzone: np. mapy (map), wtyczki (embed), ramki (iframe).
Odsyłacze: np. hiperłącza (a).
Tablice w HTML5 można tworzyć za pomocą elementu "table". Można ustawić ich wymiary i łączyć komórki, tworząc scalone komórki.

Formularze w HTML5 są tworzone za pomocą elementu "form". Mogą zawierać ramy (fieldset), pola wprowadzania danych (input), 
pola wyboru (select), radio (type="radio"), hasło (type="password"), listy rozwijalne i nowe typy pól, takie jak daty (type="date") i adresy e-mail (type="email").

II. CSS3 - kaskadowe arkusze stylu
metody dołączania stylu CSS do dokumentu HTML
klasy a identyfikatory
wybrane atrybuty CSS3 dotyczące formatowania bloków, list, formularzy
dziedziczenie właściwości CSS3


<h1> Metody dołączania stylu CSS do dokumentu HTML to: </h1>

Dołączenie pliku CSS zewnętrznego przez dodanie tagu <link> w nagłówku HTML.
Osadzenie stylów w nagłówku HTML za pomocą tagu <style>.
Bezpośrednie dołączenie stylów do elementu HTML za pomocą atrybutu "style".
Klasy i identyfikatory są to selektory CSS, które pozwalają na identyfikowanie i formatowanie określonych elementów HTML. Klasa jest wspólna dla wielu elementów, a identyfikator jest unikalny dla każdego elementu.

Wybrane atrybuty CSS3 dotyczące formatowania bloków to:

Właściwości układu (np. float, display, position)
Właściwości marginesów i paddingu
Właściwości tła (np. background-color, background-image)
Wybrane atrybuty CSS3 dotyczące formatowania list to:

Właściwości wyglądu punktów listy (np. list-style-type, list-style-image)
Właściwości położenia punktów listy (np. padding-left)
Wybrane atrybuty CSS3 dotyczące formatowania formularzy to:

Właściwości wyglądu pola formularza (np. border, padding, background)
Właściwości tekstu (np. font-size, color)
Właściwości interaktywności (np. :hover, :focus)
Dziedziczenie właściwości CSS3 polega na przekazywaniu wartości właściwości z rodzica na dziecko. 
Jeśli dziecko nie posiada własnej wartości dla danej właściwości, jest ona dziedziczona z rodzica. 
Można nadpisać dziedziczone właściwości za pomocą nowych wartości dla dziecka.

<h1>III. Podstawy programowania w JavaScript</h1>

Programowanie w JavaScript (JS) jest językiem skryptowym, który pozwala na interakcję z HTML i CSS oraz dodawanie dynamicznych elementów i funkcji na stronie internetowej.

Podstawowa składnia języka JS to:

Zmienne: służą do przechowywania danych, typy danych w JS to: number, string, boolean, undefined, null, symbol. Typ danych można sprawdzić za pomocą instrukcji typeof.
Operatory: służą do wykonywania działań matematycznych i na tekstach.
Funkcje okienkowe: takie jak alert(), confirm(), prompt(); pozwalają na interakcję z użytkownikiem.
Instrukcje warunkowe: if/else pozwalają na wykonywanie różnych działań w zależności od warunku.
Pętle: for i while pozwalają na powtarzanie bloku kodu.
Tablica w JS jest obiektem służącym do przechowywania wielu wartości. Istnieją podstawowe funkcje i metody dotyczące tablic takie jak np. push() i pop().

Zdarzenia to działania wykonywane przez użytkownika na stronie, takie jak kliknięcie przycisku. Zdarzenia można obsłużyć za pomocą funkcji użytkownika.

Odwoływanie się do elementów DOM polega na uzyskaniu dostępu do elementów HTML i ich modyfikacji za pomocą JS. Można to zrobić np. poprzez wyszukanie elementu po ID lub klasie i zmianę jego wartości lub właściwości.

Debugowanie kodu JS można wykonać za pomocą narzędzia debugger, takiego jak konsola lub inspektor.
