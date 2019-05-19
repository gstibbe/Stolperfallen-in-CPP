# Einfache Stolperfallen

## Gefährliche Syntaxfehler

### Gleich oder Vergleich

if (a=5)

### Niemals ein lokales Objekt per Referenz zurückgeben

A& funktion()
{
  A test;
  // ...
  return test;  // Fehler!!
}



**In fett markiert **
