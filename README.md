# Staticka analiza projekta "calculator-java"

## LOC analiza

Ukupan broj linija koda (LOC) u Java fajlovima: **148**

Alat korišćen za analizu: `cloc` (v2.04)  
Komanda korišćena:  
cloc .

markdown
Копирај
Измени

## Zapažanja (neformalan pregled koda)

**Calculator.java**
- 4 – Suvišan import klase `Scanner` jer se ne koristi
- 12 – Promenljive `a` i `b` imaju generičke nazive, preporučuju se deskriptivniji nazivi
- 30 – Duplirani kod za matematičke operacije, može se refaktorisati u posebnu metodu
- 42 – Nedostaju komentari za složeniji deo koda

**Main.java**
- 6 – Formatiranje koda nije dosledno
- 11 – Nedostaje provera korisničkog unosa
- 15 – Poželjno dodati komentare za tok izvršavanja

## Zaključak

Kod je funkcionalan i jednostavan za razumevanje, ali sadrži nekoliko manjih propusta. Preporučuje se:
- Uklanjanje neiskorišćenih importova
- Korišćenje deskriptivnijih naziva promenljivih
- Dodavanje komentara gde je logika kompleksnija
- Refaktorisanje ponavljajućih delova koda

Ove izmene bi poboljšale čitljivost i održavanje projekta.
