# NoteBash: Enkel webbaserad anteckningsapplikation

## Översikt:
NoteBash är en enkel webbapplikation avsedd för att skapa, uppdatera, visa och ta bort anteckningar. Varje anteckning inom applikationen består av en titel, innehåll och är kopplad till en specifik användare.

## Funktioner:
- Skapa nya anteckningar
- Visa befintliga anteckningar
- Uppdatera anteckningar
- Ta bort anteckningar

## Installation:
1. Forka eller Klon:a: Börja genom att hämta källkoden. Du kan göra detta genom att forka eller klona repositoryt från GitHub.
2. Navigera till Projektets Katalog: Använd din terminal för att navigera till den katalog där projektet är placerat.
3. Installera beroenden: Kör `npm install` för att installera de nödvändiga node_modulerna.
4. Starta Applikationen: Starta applikationen i din webbläsare genom att köra `npm run dev`.

## Användning:
- Skapa en anteckning: Fyll i användar-, titel- och anteckningsfälten, se till att anteckningen innehåller minst 5 tecken. Klicka på skicka för att skapa en ny anteckning.
- Visa anteckningar: Ange användarnamnet och klicka på "Hämta mina anteckningar" för att hämta sparade anteckningar som är kopplade till den användaren.
- Redigera och ta bort anteckningar: Varje anteckning inkluderar alternativ för att redigera eller ta bort den.

## Säkerhet:
Observera att NoteBash för närvarande inte implementerar användarautentisering eller auktorisering. Som ett resultat kan vem som helst som känner till ditt användarnamn komma åt, visa och redigera dina anteckningar. Var försiktig när du använder denna applikation och undvik att använda känslig information i dina anteckningar.

Observera: Denna applikation är avsedd för demonstrations- och utbildningsändamål och bör inte användas för att lagra konfidentiella eller känsliga data.

## Ytterligare Information:
- Beroenden: Se till att du har Node.js och npm installerat på ditt system, och se till att du använder en kompatibel version av npm.
- Använda Teknologier: NoteBash är byggd med TypeScript, Vite, Axios för att hantera HTTP-förfrågningar och Sass för styling.
- Felsökning: Om du stöter på några problem under installationen eller användningen av NoteBash, rekommenderas det att felsöka genom att KOLLA ATT DU ÄR I RÄTT MAPP...    XD
