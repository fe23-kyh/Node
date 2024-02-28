# Node Bootcamp

## Node calculator
Skapa en fil som heter `index.js` och en fil som heter `operations.js`
I `operations.js` definierar du fyra funktioner (`add`, `subtract`, `division` och `multiplication`). Varje funktion tar emot två parametrar, utför en specifik operation och returnerar ett resultat.
Exportera alla fyra funktioner och importera dessa i `index.js`
Anropa sedan varje funktion och använd `console.log()` för svaret.

### 💡 Level-Up 
Skapa filen `result.js` och lägg till samt exportera en av funktionerna från `operations.js` Importera sedan funktionen till `index.js` och anropa den för att logga ut resultatet. 
**Tips!** Tänk på ordningen av hur alla funktioner anropas.

## Läsa/skriva med Node
1. Skriv ett program som sparar citatet nedan i en textfil som heter `alicequotes.txt` Använd `writeFile`.
> "Why, sometimes I've believed as many as six impossible things before breakfast."

2. Skriv ett program som läser from textfilen `alicequotes.txt` och skriver ut innehållet.

3. Skriv ett program som läser in `style.css` och räknar antalet ID:n (d.v.s antalet #) och skriver sedan ut summan.

4. Skapa ett program som läser in `insults.json` och skriver ut både insults och räknar antal insults och skriver ut dessa. 
**Tips!** Här behöver du använda `JSON.parse()` för att göra om till JSON efter inläsning av filen.

5. Skapa en `index.html` med lite HTML-taggar i och skriv ett program som läser in denna HTML-fil och skriver ut innehållet.

### 💡 Level-Up 
Skriv ett program som skapar en fil och skriver en text till denna fil som en användare ger. En användare ska i terminalen få mata in vad filen ska heta och sedan vad för text som ska skrivas in i filen. 
**Tips!** Här behöver du använda dig av [readlineSync](https://www.npmjs.com/package/readline-sync)
