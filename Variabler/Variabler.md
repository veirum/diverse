

# Variabler

*Jeppe Veirum Larsen, Okt. 2020*

**Fag:** Programmering c.         **Sprog:** JavaScript

![Think variables as boxes contining values!](./figures/variables.png)



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

Udtrykket *variabel* bruges i mange forskellige sammenhænge og i kender det måske fra matematik. I matematik bruges en variabel f.eks. *a* eller *x* til at beskrive en ukendt mængde så den kan ændre sig, eller variere, derfra navnet variabel. I datalogi repræsenterer en variabel allokering af data som kan ændres. Men inden vi kommer alt for langt og får præsenteret for mange nye termer så lad os se på et eksempel af en variabel der hedder *a* og indeholder værdien *2*.

``` javascript
let a = 2;
```

<br/>

### En Variabels forskellige komponenter

Eksemplet ovenfor ser nok lidt fremmed ud for folk, der aldrig før har stiftet bekendskab med programmering. I dette afsnit vil vi gennemgå eksemplet de elementer som en variabel består af, så vi kan begynde at lave vores egne variabler. 

```java
//Her er en variabel kaldet 'a', indeholdende værdien 2, skrevet i C++.

int a = 2;
	
//Her er komponenterne en variabel dekleration består af
//	type			navn				operator			værdi				terminator
		int					a						  =						2							;

```



***Type*** deffinere hvilken type data variablen kan indeholde. ***a*** er navnet på variablen, ***=*** er den operator som tildeler variablen en værdi, ***2*** er værdien som tildeles og ***;*** afslutter sætningen og fortæller compileren at linien er slut.







````js
//I JavaScript kan vi oprette en variabel kaldet 'a', indeholdende værdien 2, f.eks. se sådan ud.

let a = 2;
 
````



## Implicitte og Eksplicitte Variabler

Der findes to overordnede typer af variabler kaldet implicitte og eksplicitte variabler. 

### Data typer





Disse to typer knytter sig til forskellig sprog 





 Allokering betyder hvor i compterens hukommelse, ligger lige netop denne variabel er, og hvor meget plads giver vi den.



For at gå lidt væk fra de teksttunge eksempler så forestil jer at en variabel er en spand. I en spand kan man opbevare f.eks. vand og alle spande har en bestemt størrelse så der kan kune være f.eks. 20 liter i spanden inden den flyder over, men der kan også være 10 liter. 




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
> 

































