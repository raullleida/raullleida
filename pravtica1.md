# MÒDUL 16 – Ciberseguretat i hacking ètic
### UNITAT FORMATIVA 1
### Ciberseguretat i ciberintel·ligència
Pràctica 1.1
Anàlisi forense I

**Raúl lleida**

**Index de continguts**
1. Introducció
1.1 Escenari
1.2 Anàlisi amb autopsy
1.3 Anàlisi amb foremost i testdisk
1.4 Anàlisi amb Exiftool
2. Conclusions

**Introducció**
- Eines
- Kali Linux
- Testdisk (command line)
- Foremost (Command line)
- Forensics/Autopsy (Windows && JDK)
- Lliureu un document en format PDF amb els passos que heu seguit i la resposta a les
- preguntes que es plantegen

**1.1 Escenari**

Avui és 15 de setembre de 2004. L'hora són les 3:15 PM. El senyor Jim Boss, el
propietari de la Really Big Company, et truca per a què vagis a la seva oficina. El
senyor Boss et comenta que sospita que la seva assistent, Emma Crook, estava
proporcionant material sensible de l'empresa a alguns dels seus competidors.
A les 2:00 PM, avui truca a la Sra Crook i li comenta les seves sospites. Li diu que
tornaria a les 3:00 PM per a una explicació. 
Quan el senyor Boss torna a l'oficina de la Sra. Crook a les 3:00 PM, ella no hi és, i ha buidat el despatx de totes les seves pertinences. 
El senyor Boss intenta encendre l'ordinador de la senyora Crook, però no
arrenca. Examinant l’habitació, troba un disquet a la paperera. 
El senyor Boss t’entrega el disquet i vol que li expliquis exactament el que la Sra. Crook estava fent. El primer que fas es comprovar l’ordinador, i trobes que li falta el disc dur. Així doncs, l’única prova que tenim és un disquet. Un cop ja al teu despatx,
introdueixes el disquet i descobreixes que no hi ha res, és a dir, l’han formatejat.
Fas una còpia del mateix i obtens un fitxer RAW amb el què treballaràs.

1. Documenta i descriu tot el procés de la teva investigació (amb captures de
pantalla, comentant tots els passos seguits).







12
Anàlisi amb Autopsy
○ Forensics / autopsy → per a analitzar la imatge RAW
Des de una máquina windows, baixa i instal·la l'Autopsy
Amb aquest programa, carrega la imatge RAW anterior, i analitzala.
¿Que trobes?
¿Pots llegir alguna informació? En cas afirmatiu, ¿Quina?


/etc/apt/sourcelist > cambias el http a  https
setxkbmap es
usaremos https://dillinger.io/ para la documentación


13
Anàlisi amb Foremost i testdisk
Des de una màquina Kali/Debian, executa el foremost, torna a carregar la imatge RAW
anterior, analitzala i compara els resultats amb els obtinguts anteriorment
Des de una màquina Kali/Debian, executa el testdisk, torna a carregar la imatge RAW
anterior, analitzala i compara els resultats amb els obtinguts anteriorment

14
Anàlisi amb Exiftool
Des de una màquina Kali/Debian, executa Exiftool, carrega els fitxers trobats
anteriorment i analitza'ls.
Què observes en els resultats?
Hi ha informació interessant?
2
Conclusions
Examina els arxius i troba l’evidència de les sospites del Sr. Boss
Per últim mirarem que aquest quart ja no es un arxiu doc i que esta protegit amb una
contrasenya (ho veurem en el apartat de Security).
Obrim aquest arxiu en un format Excel com ens deixa clar en les metadades. Només
entrar veurem que aquest document està protegit amb un contrasenya. La qual intentarem
vulnerar amb el programa JohnTheRipper.
2. Què va fer la senyora Crook en aquest interval de temps?
3. Quines evidències has trobat?

4. Ho podries demostrar devant del Jutge?
