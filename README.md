# Bibliotekssystem

Det här projektet är en enkel modell av ett bibliotekssystem skrivet i C#.  
Systemet består av flera klasser som visar hur objektorienterad programmering (OOP) fungerar med arv, inkapsling och metoder.

## Klasser och deras funktioner
- **Person (grundklass)**  
  - Attribut: `namn` (#) → skyddat, syns för klassen själv och de som ärver.  
  - Metod: `visaProfil()` (+) → öppen för alla, visar information om personen.  

- **Medlem (ärver från Person)**  
  - Ärver attribut och metoder från **Person**.  
  - Extra metod: `lånaBok()` (+) → gör det möjligt att låna en bok.  

- **Bibliotek**  
  - Attribut: `namn` (-) → privat, kan bara användas i klassen.  
  - Metod: `registreraBok()` (+) → lägger till en bok i biblioteket.  

- **Bok**  
  - Attribut: `titel` (-) → privat, tillhör bara klassen.  
  - Metod: `visaInfo()` (+) → visar information om boken.  

- **Lån**  
  - Attribut: `lånedatum` → datumet när lånet startade.  
  - Metod: `avsluta()` → avslutar ett lån.  

## Symboler i UML
- **+ (public):** öppen för alla.  
- **- (private):** endast synlig i den egna klassen.  
- **# (protected):** synlig för klassen själv och klasser som ärver från den.  
