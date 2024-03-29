Software Quality Introduction

Assignment : Metrika, pregled i statisticka analiza


LOC (Lines of code):
file Calculator.java ima 188 linija koda
file Start.java ima 26 linija koda
Zajedno svi fajlovi imaju 214 linija koda.

Statickom analizom koda radjenom SonarLint alatom za file Calculator.java IntelliJ IDEA daje 8 upozorenja:
problem imenovanja metode "ToString", da bi se izbjegle nedoumice i moguci sudar sa metodom "toString" iz superklase "java.lang.Object". Potpuno isto ime sa samo razlikom u velicini pocetnog slova, moze biti zbunjujuca. Ukazuje na gresku programera koji je umjesto override superklasne metode napravio novu sa istim imenom ili na lose imenovanje. PREPORUKA: promjena imena metode
Calculator klassa (4 linija koda) treba biti static umjesto public
Prilikom importa neimenovani paketi ne bi trebali biti koristeni jer to otezava razumjevanje koda
DoSomething primenovati tako da se ispostuje konvencija imenovanja (na tri mjesta u kodu)
Nepotrebna promjenjiva na 70toj liniji koda, preporuka je da se vrijednost vrati bez deklarisanja promjenjive
Nepotreban return na 183 liniji koda

Staticka analiza za file Start.java javlja 4 upozorenja:
Standardni outputi ne trebaju da se koriste direktno (iskoristeni na dva mjesta u kodu)
Neimenovani paketi kao i u Calculator.java
Kod promjenjive Expression nije ispostovana konvencija imenovanja
