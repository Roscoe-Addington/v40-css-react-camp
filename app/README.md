Felsökning

Import
Är CSS-filen importerad?
Titta i App.jsx-filen högst upp, försäkra dig att det har gjorts en import av CSS-filen (import"./App.css";). Är det inget som fungarar kan felet bero på det.

className
Stämmer className?
Det Jämnför klassnamnet i JSX med selektorn i CSS-filen, bokstav för bookstav. Det måste matcha exakt. Datorn gissar inte vad man menar. Om klassen sätts med en ternary: bör man kontrollera att både grenerna ger rätt klasser.

Inspect
Inspektera elemenrtet
Genom att högerklicka och skråla vidare till Inspect. Kan man se om regeln används eller om den är överstruken.
