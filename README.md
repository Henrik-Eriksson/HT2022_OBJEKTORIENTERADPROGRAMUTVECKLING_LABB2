# Laboration 2: Objektorienterad Programmering - Othello-spel
Labs done in pair with [11Johan11](https://www.github.com/11Johan11)
## Kurs: Objektorienterad Programutveckling (TOCK12) - Hösten 2022

## Inledning
Det här repositoriet innehåller min lösning på laboration 2 i kursen Objektorienterad Programutveckling. Uppgiften var att skapa ett enkelt Othello-spel som en WPF-applikation. Projektet fokuserade på grafiska gränssnitt, händelsehantering, databindning och trådhantering i samband med objektorienterad design.

## Uppgiftsbeskrivning
Uppgiften innebar att utveckla ett Othello-spel med följande funktionaliteter:
1. **Spellogik**: Implementera grundläggande spellogik för Othello.
2. **Spelartyper**: Möjliggör spel mellan två mänskliga spelare, en mänsklig och en datorspelare, eller två datorspelare.
3. **Grafiskt Gränssnitt**: Utveckla ett grafiskt användargränssnitt med WPF för spelet.
4. **Trådhantering**: Hantera trådar korrekt för att säkerställa att gränssnittet inte fryser under beräkningar.

## Tekniska Detaljer
- **Språk och Teknik**: C# med WPF för .NET.
- **Arkitektur**: MVVM (Model-View-ViewModel) eller en annan lämplig design.
- **Klasser**: Inkluderar `GameWindow`, `SetupGameDialog`, `WinnerDialog`, `DrawnDialog`, `Player`, `HumanPlayer`, `ComputerPlayer`, `GameBoard` och `GameManager`.
- **Asynkron Programmering**: Användning av trådar för att hantera långvariga beräkningar utan att påverka användargränssnittet.

## Bedömning och Krav
- Korrekt implementering av Othello-spelet.
- Kod måste vara välorganiserad och följa god objektorienterad design.
- Adekvat dokumentation och namngivning enligt C# standarder.
- Programmet måste kompilera och köra korrekt i en .NET-miljö.

## Inlämning
Uppgiften bedömdes som godkänd eller underkänd baserat på korrekt implementering och dokumentation av de krävda funktionerna.
