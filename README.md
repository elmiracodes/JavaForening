# JavaForening
Förening och Ideellförening


Mindre programmeringsuppgift i Java
Använd BlueJ för att skapa ett projekt med namnet Föreningar och sedan följa de följande steg:

Del1:Klasser & objekt

-Skriv en klass som heter Förening som har följande egenskaper(attribut): namn, adress och registreringsår.

Välj lämpliga typer för värdena namn, adress och registreringsår. namn och adress ska representeras av en sträng (String), medan registreringsår ska anges som ett heltal.
Värdena för namn och adress inte skall vara tillgängliga utanför klassen Förening , registreringsår ska vara tillgänglig utanför klassen (Använd lämpliga tillgänglighetsmodifierare(public,private.)).
 A-Klassen ska ha följande konstruktorer:

En konstruktor som tar emot tre argument och tilldelar dem till lämpliga fält:namn, adress och registreringsår
En konstruktor som tar emot två argument och tilldelar dem till namn och registreringsår. Adress ska tilldelas en tom sträng (" ").
En konstruktor som tar emot två argument och tilldelar dem till namn och adress.  registreringsår ska tilldelas en värde 0.
En konstruktor som tar emot ett argument och tilldelar det till namn, tilldela en tom sträng (" ") till adress och 0 till registreringsår.
En parameterlös konstruktor som tilldelar tomma strängar (" ") till namn och adress och 0 till registreringsår.
B-Skriv lämpliga getter-setter metoder som lagrar värden i dessa fält och returnerar värdena från dessa fält.

C-Skriv en lämplig toString() metod som returnerar lämplig information om objekten.

D-Skriv ett separat program TestKlass (en klass som innehåller main-metod) där användaren matar in namnet, adressen och registreringsår i tre olika dialogrutor och sedan skapa ett objekt av klassen Förening som innehåller de inmatade data. 

På samma sätt låt användaren skapa fyra objekt till men använd en av konstruktorerna med varje objekt.
Låt användaren ändra värde för adress i första objekt och sedan bara visa adressen för detta objekt via en dialogruta (använd get och set metoder)
E- Visa data för varje objekt genom en dialogruta (Utnyttja toString-metoden i utskrifterna.)

Del2 : Arv ,Metod Överskuggning

G-Skapa därefter en klass IdeellFörening som ska ärva av klassen Förening . En Ideell Förening ska ha en privat egenskap antalMedlemmar.

Skriv lämpliga getter-setter metoder
Skriv lämpliga konstruktorer för klassen IdeellFörening
Skriv en lämplig toString() metod som returnerar lämplig information om objekteten
H-I Klassen TestKlass:

låt användaren skapa två objekt av klassen IdeellFörening och skriv sedan ut deras antalMedlemmar, namnet och adressen . Använd dialogrutor för inmatning och utmattning.
Låt användaren ändra värde för antalMedlemmar i första objekt och sedan visa bara namnet och antalMedlemmar för detta objekt via dialogrutor (använd get och set metoder)
 
