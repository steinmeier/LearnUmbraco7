#Developer Tools#

![9026576438_2b6993f317_o (1).jpg](assets/9026576438_2b6993f317_o.jpg)
>Foto: Doug Robar

Denne bog handler om at udvide Umbraco. Den kan være simple, men den kan også være avanceret, skulle man vælge det.
Derfor, afhængigt af hvad du ønsker at opnå, kræves der ikke noget særligt.

##Nødvendige tools##
##En god text editor###
Hvis du blot skal tilføje et par custom data types til din Umbraco-løsning, kan du nøjes med din foretrukne text editor, som fx. [Sublime](http://www.sublimetext.com/).

###Visual Studio Express eller højere###
Hvis du har planer om at udbygge funktionaliteten i backoffice, som kræver custom-kode på serversiden, skal du bruge Microsoft Visual Studio. Frygt ikke; Express-udgaven af VS er gratis, og fuldt ud i stand til det meste.
Læs mere i appendix’et om [installing Visual Studio Express](/z-Appendix B - Installing Visual Studio Express/README.md).

Ting, der kræver custom-kode på serversiden:
* Custom trees og sections
* Integration med Umbraco content, som ikke udbydes via en Umbraco web service
* Håndtering af custom forms
* Programmatisk oprettelse/import af content
* Custom database-kald
* Opfange og redigere default-adfærd gennem event handling 
(som fx. at køre kode før eller efter noget er publiseret)

*Tjek venligst dokumentationen og Google for det du forsøger at opnå. Der er mange ting Umbraco allerede understøtter.*

##Valgfrie Tools##
Über-nørden, vil nok have gavn også af disse tools:
* [ReSharper](https://www.jetbrains.com/resharper/) - ReSharper tager code hinting og completion et skridt videre.  
*Ikke sikkert, den kan installeres på VS Express.*
* [GitExtensions](https://code.google.com/p/gitextensions/) 
	- En GUI der hjælper med almindelige Git-kommandoer.
* [Fiddler](http://www.telerik.com/fiddler) - Et gratis tool til monitorering af HTTP transactions i real-time.

[<Tilbage Overview](README.md)
