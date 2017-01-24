# epitech-clion
Epitech norm compliant configuration for CLion IDE.

This CLion configuration is made to be as compliant as possible with the Epitech norm but there is still some known problem:
- When reformating the file, variable and function aren't aligned together, you have to do it manually.
- The header is semi-hard coded since there isn't a "PATH" variable and the last modified field isn't updated. (but it shouldn't affect the norm)

If you have any suggestion please let me know.

# Installation

**Code Style**<br />
*file -> settings -> code style -> manage... -> import*
- Import "Epitech_C.xml"

**Epitech Header**<br />
*file -> settings -> code style -> File and Code Templates -> Includes*
- Add an include for c/h Extension and paste the content of Header_Template.txt in it.
- Replace 'nom' and 'prenom' with yours.
