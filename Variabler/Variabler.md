

# Variabler

*af Jeppe Veirum Larsen, senest opdateret Okt. 2020*

**Fag:** Programmering c.&nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp;**Sprog:** JavaScript

<br/>

![Think variables as boxes contining values!](./figures/variables.png)

<br/>

Variabler er fuldstændigt essentielle og en af grundpillerne i al programmering. Lige meget hvad man gerne vil lave, vil man altid komme til at bruge variabler på den ene eller den anden måde. Denne tekst vil gennemgå hvad en variabel er, hvilke typer der findes, hvordan de kan bruges og giver jer mulighed for at stifte bekendskab med oprettelse og ændringer af variabler.

<br/>

 **I dette forløb vil i lære**

- Hvad er en variabel

- Hvad er datatyper

- Oprette en variable
- Basal aritmetik i programmering

- Ændre typen af variablen

- Skrive til konsollen
- Konstanter

<br/>

## Hvad er en variabel?

Udtrykket *variabel* bruges i mange forskellige sammenhænge og mange kender det måske fra matematik. I matematik bruges en variabel f.eks. ***a*** eller ***x*** til at beskrive en ukendt mængde så den kan ændre sig, eller variere, derfra navnet *variabel*. I datalogi repræsenterer en variabel allokering af hukommelse til opbevaring af data som kan ændres. Men inden vi kommer alt for langt og får præsenteret for mange nye termer så lad os se på et eksempel af en variabel der hedder *a* og indeholder værdien *2*.

``` javascript
// Et eksempel på en variabel i JavaScript

let a = 2;

```

<br/>

Eksemplet ovenfor kan nok se lidt fremmed ud for folk, der aldrig før har stiftet bekendskab med programmering. Den første vi skriver er ordet *let*. Det skal skrives når man ønsker at oprette en ny variabel. Herefter skal variablen have et navn, som i dette tilfælde er *a*. Dernæst kommer ligmed tegnet *( = )* , der i programmering bruges til at tildele noget en værdi som her i eksemplet er *2*. Til sidst afsluttes der med semicolon *( ; )* der er et tegn til computeren at vores linien slutter her. 



HÅNDTEGNET BILLEDE HER!



```javascript
//Her er en variabel kaldet 'a', indeholdende værdien 2, skrevet i C++.

let a = 2;
	
//Her er komponenterne en variabel dekleration består af
//	initialiser		navn			operator			værdi				terminator
			let						a						=						2							;

```

<br/>

## Datatyper

Som billedet [øverst](variabler) viser I vores første eksempel brugte vi tallet 2 som vi puttede ind i vores variabel. 

Når vi opretter en variabel operere vi med forskellige såkaldte data typer. 



## Implicitte og Eksplicitte Variabler

Der findes to overordnede typer af variabler kaldet implicitte og eksplicitte variabler. 

### Data typer





Disse to typer knytter sig til forskellig sprog 





 Allokering betyder hvor i compterens hukommelse, ligger lige netop denne variabel er, og hvor meget plads giver vi den.



For at gå lidt væk fra de teksttunge eksempler så forestil jer at en variabel er en spand. I en spand kan man opbevare f.eks. vand og alle spande har en bestemt størrelse så der kan kune være f.eks. 20 liter i spanden inden den flyder over, men der kan også være 10 liter. [Nu prøver vi at skrive det][1]




## Data typer



> :pencil2: **Øvelse 1**
>
> Prøv at oprette din egen variabel. Du kan kalde den hvad du vil og du vælger selv om den skal indeholde tal eller bogstaver.



> :warning: De mest brugte datatyper er int (heltal), float (kommatal, String (tekst), bool (sandt/falsk) 



:warning: Implicitte variabler, som f.eks. dem i JavaScript og Python, bestemmer selv hvilken datatype de bliver ud fra hvilke værdier de gemmer på. Dette går for det meste godt, men nogle gange ønsker vi at  



>:pencil2: **Øvelse 1**
>
>
>Prøv at oprette din egen variabel. Du kan kalde den hvad du vil og du vælger selv om den skal indeholde tal eller bogstaver.



> :mag: Hvis du er i tvivl om, hvilken *datatype* din variabel er.
>
> ```javascript
> console.log(typeof enVariabel);
> //output: "number"
> ```
>
> 



> :warning: I vil støde på eksempler, hvor ordet **var** bruges istedet for **let**. 
>
> ```javascript
> var enVariabel = 2;
> ```
>
> 



> :warning: Husk at et variabel navn skal være unikt og sigende for hvad den indeholder.  
> Du skal benytte [a-z] [A - Z] [0 - 9] _ eller $. Første position kan ikke være [0-9] når du navngiver. Ved at følge dette undgår du fejl hvis du ønsker at bruge din kode andre steder eller i andre sprog.
>
> :no_entry_sign: 
>
> ```javascript
> //Begynder med et tal
> let 1lilleMand = "Jørgen";
> 
> //Begynder med et beskytte ord
> let undefined = 98;
> ```
>
> <br/>
>
> :white_check_mark: 
>
> ```javascript
> let enLilleMand = "Jørgen";
> let monsterJegHarDrukket = 98;
> ```
>



> :book: **Termer**
>
> | Term på Engelsk | Betydning på Dansk                  |
> | --------------- | ----------------------------------- |
> | Initialise      | Fastsætte en værdi som udgangspunkt |
> | Allocate        | Tildele plads i hukommelse (RAM)    |
> | Declare         | Erklære/oprette                     |
> | Assign          | Tildele en variable en værdi        |
>
> 





> :books: **Uddybende Materiale**
>
> [Javascript.info om Variabler](https://javascript.info/variables)
>
> [Variables in P5.js Video 1/2](https://www.youtube.com/watch?v=RnS0YNuLfQQ)
>
> [Variables in P5.js Video 2/2](https://www.youtube.com/watch?v=Bn_B3T_Vbxs)


