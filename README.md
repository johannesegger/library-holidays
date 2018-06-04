# softaware.Holidays
> A simple .NET Core Library for automatically generating Holidays

## Usage
Include `softaware.Holidays.Core` and `softaware.Holidays.<Country>` and then simply
```csharp
var holidays = new Holidays.Generator().ForAustria(2018);
```

## References
- Algorithm based on: https://de.wikipedia.org/wiki/Gaußsche_Osterformel
- Austrian Holidays based on: http://gesetzlichefeiertage.at/uebersicht/feiertage-2018.html
