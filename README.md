calculator.java - 134 loc
license - 17 loc
start.java - 19 loc
170 loc ukupno

neformalni pregled koda:
calculator.java - linija 5 - class Calculator je javni, treba Calculator.java 
calculator.java - linija 54 - koristi bolju petlju for 
calculator.java - linija 56 - konvertuj u switch string
calculator.java - linija 63 - promjenjiva nije potrebna
calculator.java - linija 64 - catch blok se moze pojednostaviti
calculator.java - linija 184 - izbrisati nepotrebni return statement

start.java - linija 8 - nedostaje zagrada u System.out.println.

staticka analiza SonarLint u IntelliJ IDEA:
calculator.java - linja 4(13) - Add a private constructor to hide implicit public one
calculator.java - linija 18(29) - rename method "ToString" to prevent any misunderstanding
calculator.java - linija 24(25) - rename this metod to match the regular expression
calculator.java - linija 63(35) - replace "exc" with an unnamed pattern
calculator.java - linija 70(28) - immediately return this expression instead of assigning to the temporary variable "text.Result"
calculator.java - linija 74(24) - rename this methos name to match the regular expression
calculator.java - linija 183(12) - remove this redundant jump

start.java - linija 19(16) - replace this use of System.out by a logger
start.java - linija 8(8) - replace this use of System.out by a logger
start.java - linija 6(15) - rename this local variable to match the regular expression
