The description has been written in Polish and English.







POLISH:

Pseudojęzyk HGuiScript w Aplikacji HTA
Pseudojęzyk HGuiScript umożliwia sterowanie zachowaniem i wyglądem aplikacji w środowisku HTML APPLICATION. Język został zaprojektowany i zaprogramowany w JavaScripcie. Poniżej znajduje się lista dostępnych funkcji wraz z ich opisami.

Język nie jest przeznaczony do codziennego użytku. Został zaprojektowany raczej jako skrypt pomocniczy dla osób, które chcą stworzyć własny język w JS.

1. #text
Funkcja #text pozwala na dodawanie tekstu do interfejsu aplikacji. Tekst zawarty po komendzie zostaje wyświetlony na stronie.
Przykład:
#text Witaj w naszej aplikacji HTA!
2. #bg-color
Funkcja #bg-color umożliwia zmianę koloru tła aplikacji. Podany kolor zostanie użyty jako nowy kolor tła.
Przykład:
#bg-color white
3. #text-color
Funkcja #text-color pozwala na zmianę koloru tekstu w aplikacji. Podany kolor zostanie użyty jako nowy kolor tekstu.
Przykład:
#text-color black
4. #button
Funkcja #button służy do dodawania nowego przycisku do interfejsu aplikacji. Nowy przycisk pojawi się na stronie.
Przykład:
#button
5. #button-text
Funkcja #button-text umożliwia dodawanie przycisków z określonym tekstem do interfejsu aplikacji. Tekst zawarty po komendzie zostanie wykorzystany jako etykieta przycisku.
Przykład:
#button-text Kliknij mnie
Uwagi
    • Każda linia w pliku "script.txt" reprezentuje jedną Funkcje. Funkcje są wyświetlane w kolejności, w jakiej się pojawiają.
    • Wszystkie Funkcje zaczynają się od znaku #, a następnie występuje nazwa komendy lub jej identyfikator.
    • Nie ma potrzeby użycia cudzysłowów wokół tekstu, chyba że tekst zawiera spacje lub znaki specjalne.
To są podstawowe komendy dostępne w HGUIScript pracującym w HTA. Możesz tworzyć plik "script.txt" zawierający te komendy, aby programować wygląd i treść swojej aplikacji HTA.


ENGLISH:

Pseudo-language HGuiScript in HTA Application
The pseudo-language HGuiScript enables control over the behavior and appearance of an application within the HTML APPLICATION environment. The language has been designed and programmed in JavaScript. Below is a list of available functions along with their descriptions.
The language is not intended for everyday use but rather as a helper script for individuals who want to create their own language in JS.
    1. #text The #text function allows for adding text to the application interface. The text following the command will be displayed on the page. Example: #text Welcome to our HTA application!
    2. #bg-color The #bg-color function enables changing the background color of the application. The provided color will be used as the new background color. Example: #bg-color white
    3. #text-color The #text-color function allows for changing the text color in the application. The provided color will be used as the new text color. Example: #text-color black
    4. #button The #button function is used to add a new button to the application interface. The new button will appear on the page. Example: #button
    5. #button-text The #button-text function enables adding buttons with specific text to the application interface. The text following the command will be used as the button label. Example: #button-text Click me
Notes: • Each line in the "script.txt" file represents one function. Functions are displayed in the order they appear. • All functions start with the # symbol, followed by the command name or its identifier. • There's no need to use quotation marks around text unless the text contains spaces or special characters.
These are the basic commands available in HGuiScript working within HTA. You can create a "script.txt" file containing these commands to program the appearance and content of your HTA application.
