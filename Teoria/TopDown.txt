Design Top-Down i Parametrització de Funcions
amb Kotlin

Disseny top-down i la parametrització de funcions, adaptat específicament per als
coneixements previs d'aquests conceptes en Python per aplicar-los amb Kotlin.
Disseny Top-Down en Kotlin
Conceptes Previs
El disseny top-down implica abordar un problema complex dividint-lo en subproblemes més
petits i resolent-los de manera individual. Aquests subproblemes es poden descompondre
fins a arribar a tasques més manejables. En Kotlin, aquesta metodologia segueix sent
efectiva, però amb algunes particularitats sintàctiques específiques d'aquest llenguatge.
Aplicació en Kotlin
Per aplicar el disseny top-down amb Kotlin, continueu utilitzant funcions per resoldre
subproblemes específics. Defineixeu les funcions de manera modular, proporcionant la
informació necessària mitjançant paràmetres d'entrada i retornant els resultats mitjançant el
valor de retorn o paràmetres de sortida.
Parametrització de Funcions en Kotlin
Conceptes Previs
Ja esteu familiaritzats amb la parametrització de funcions, que implica la capacitat de passar
paràmetres d'entrada a una funció i, si és necessari, rebre valors de sortida.
Aplicació en Kotlin
A Kotlin, podeu parametritzar les vostres funcions de manera similar a com ho feu en
Python. Declareu els paràmetres d'entrada a les funcions i utilitzeu-los dins del cos de la
funció segons les vostres necessitats. L'ús de paràmetres en Kotlin és bastant intuïtiu i es
manté consistent amb els principis que ja heu après.

Exemple Pràctic en Kotlin
Per a una comprensió més clara, veurem un exemple pràctic adaptat a Kotlin. Aquest
exemple mostrarà com aplicar els conceptes de disseny top-down i parametrització de
funcions en aquest llenguatge.
Exemple: Gestió d'Estudiant en Kotlin
Suposem que voleu desenvolupar un sistema de gestió d'estudiants amb Kotlin. Podeu
descompondre el problema en funcions com "afegirEstudiant," "buscarEstudiant," i
"eliminarEstudiant," aplicant el disseny top-down. A més, utilitzeu paràmetres d'entrada per
passar informació rellevant a aquestes funcions.
Funció per Afegir Estudiant:
fun afegirEstudiant(nom: String, edat: Int, curs: String) {
// Codi per afegir estudiant a la base de dades o sistema de gestió
}

Funció per Buscar Estudiant:
fun buscarEstudiant(nom: String): Estudiant? {
// Codi per buscar estudiant per nom
// Retornarà l'estudiant trobat o null si no es troba
}
Funció per Eliminar Estudiant:
fun eliminarEstudiant(nom: String) {
// Codi per eliminar estudiant de la base de dades o sistema de gestió
}
Aquest exemple il·lustra com podeu aplicar els conceptes que ja coneixeu en un context
específic de Kotlin. Recordeu que la transició de Python a Kotlin sovint implica ajustar-vos a
la sintaxi i a les convencions específiques del llenguatge.
Amb aquest document, teniu una base per comprendre com aplicar els vostres
coneixements existents de disseny top-down i parametrització de funcions en el context de
Kotlin.
