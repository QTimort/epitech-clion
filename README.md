# epitech-clion
Epitech norm compliant configuration for CLion IDE.

This CLion configuration is made to be as compliant as possible with the Epitech norm but there is still some known problem:
- When reformating the file, variable and function aren't aligned together, you have to do it manually.
- The header is semi-hard coded since there isn't a "PATH" variable and the last modified field isn't updated. (but it shouldn't affect the norm)
- When creating a new project, the default main generated doesn't have the epitech header, you have to copy paste it manually.
- Be carefull when declaring a variable and a function, Clion automatically put a space instead of a tab, you have to fix it manually.
- Warning regarding the number of line in a function, line breaks != number of lines, more exactly 24 line breaks = 25 lines.

If you have any suggestion please let me know.

# Installation

**Code Style**<br />
*file -> settings -> code style -> manage... -> import*
- Import "Epitech_C.xml"

**Epitech Header**<br />
*file -> settings -> code style -> File and Code Templates -> Includes*
- Add an include for c/h Extension and paste the content of Header_Template.txt in it.
- Replace 'nom' and 'prenom' with yours.
