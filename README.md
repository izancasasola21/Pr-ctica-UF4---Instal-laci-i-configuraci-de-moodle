# Practica UF4-Instal·lació i configuració de moodle
Inicia sessió com a administrador del teu Moodle i realitza les següents tasques prèvies d'administració.
![Captura de pantalla de 2025-03-13 10-57-20](https://github.com/user-attachments/assets/4c2a9056-968c-4553-8e57-931fb69ee861)
Nada mas entrar a Moodle tendremos que irnos a Pagina Principal y Editar perfil y ahi configuramos todo con nuestros datos personales, 
a) Canvia la teva direcció de correu electrònic i també la teva contrasenya per una altra. Afegeix-te a més un avatar.

### b) Canvia el nom del teu lloc (tant llarg com curt) i fes que la pàgina principal no mostri res pels usuaris que no estiguin autentificats. 
![Captura de pantalla de 2025-03-14 14-26-20](https://github.com/user-attachments/assets/92f1332a-3e0a-4d39-a0c9-68764ad680fe)

![Captura de pantalla de 2025-03-14 14-30-52](https://github.com/user-attachments/assets/47569992-cb01-4a55-8ebb-e7f77d6b0f19)

A continuación como se observa, tendremos que cambiar el nombre entonces tendremos que ir a pagina principal y a sus ajustes y alli dentro ya nos vamos a los dos primeros apartados y cambaiamos los nombres

### c) Comprova que la franja horària del teu lloc sigui la correcta.
![Captura de pantalla de 2025-03-14 14-31-26](https://github.com/user-attachments/assets/8b8c1aca-5693-46a5-9e73-0b4bcf464860)
![Captura de pantalla de 2025-03-14 14-32-00](https://github.com/user-attachments/assets/7ee42e36-9cc0-4e0a-aeff-40749177da65)

Aqui tendremos que ir a Ubicacion para poder acceder a los ajustes de ubicacion y en el primer apartado podremos cambiar la franja horaria poniendo "Europa/Madrid" como se observa en la imagen 

### d) Canvia l'idioma del teu lloc. 
![Captura de pantalla de 2025-03-20 13-48-09](https://github.com/user-attachments/assets/74dcf7cd-f6cc-4a0e-8284-eb5ae2ad7728)
![Captura de pantalla de 2025-03-20 13-50-07](https://github.com/user-attachments/assets/9ed6c908-9939-4ada-8577-6e7c334e1eb0)

Tendremos que ir a Idiomas y seguidamente entrar en los ajustes para poder cambiar el idioma, se cambia con un desplegble y el idioma es /Español(es_wp) este sera,se puede apreciar en las fotos, seguidamente tendremos que importar paquetes de idiomas para poder usarlos a la hora de usar Moodle, y esto se encuentra abajo de ajustes de idioma en "Paqutes de idioma" ahi os saldran dos columnas y ahi unicamente buscais los idiomas que querais y los seleccionais para importarlos, como se ve en la siguiente foto 

![Captura de pantalla de 2025-03-20 13-52-11](https://github.com/user-attachments/assets/ce3fdaee-122a-494d-afd5-f7c4f0b07b13)


NOTA: Per disposar d'un determinat idioma, primer cal instal.lar-lo des de Administració del lloc > Idioma > Paquets d'idioma

### e) Canvia la política de contrasenyes de manera que els usuaris que es creiïn tinguin una contrasenya de com a mínim 4 caràcters incloent-hi, majúscules, minúscules i xifres. Això es pot fer anant a l'opció Administració del lloc > Seguretat > Normatives del lloc.

### 2. Crea els següents cursos: un curs anomenat A que estigui format per 3 temes i un altre anomenat B que estigui format per 5 temes. Tot això ho pots fer des de Administració del lloc > Gestiona cursos i categories o també des del quadre Navegació anant a Cursos > Afegeix curs

### 3. Vés a algun dels cursos creats al punt anterior (simplement seleccionant-lo dins del quadre Navegació) i fes que contingui en algun del seus temes algun tipus de material (un document PDF, per exemple), canvia el títol d'algun tema i, en general, investiga les possibilitats que et dóna el botó Activar edició en un curs.

NOTA: Aquestes possibilitats no les estudiarem a fons perquè són una tasca més pròpia del professor que no pas de l'administrador del Moodle, però sempre va bé tenir-ne alguna idea.

## 4. Creació d’usuaris i alumnes.

### a) Crea manualment un usuari anomenat Bob que ha de fer servir el mètode d'autenticació manual. Això es pot fer des de Administració del lloc > Usuaris > Comptes > Afegeix un usuari

### b) Genera deu alumnes que ho seran dels dos cursos A i B . Fes servir un arxiu CSV per realitzar aquesta creació en bloc. Vés a Administració del lloc > Usuaris > Comptes > Carrega usuaris i segueix els passos que et marca.

NOTA: Per saber el contingut que hauria de tenir aquest fitxer, consulteu més abaix a la secció Usuaris.

### c) Elimina dos dels deu alumnes creats a l'apartat anterior fent servir l'opció Administració del lloc > Usuaris > Accions amb usuaris en bloc

## 5. Ara matricula aquests usuaris als diferents cursos.

### a) Fes que al curs A no hi hagi possibilitat d'inscripció (és a dir, que només es permeti l'accés de visitant de manera que el curs sigui totalment públic sense control d'usuaris -ni alumnes ni professors-). D'altra banda, fes que al curs B es necessiti registre manual d'usuaris (és a dir, que sigui l'administrador -tu- qui matriculi cada usuari al curs, ja sigui com a professor o com a alumne). Tot això ho pots fer des de Administració del curs > Ususaris > Mètodes d'inscripció. Si no surt algun mètode d'inscripció disponible, has d'activar-lo a: Administració de lloc > Connectors > Autenticació > Gestió de l'autenticació

### b) Assigna com a professor del curs B l'usuari "Bob" i com a alumnes a tots els que fas afegir des de l'arxiu CSV Tot això ho pots fer anant a Administració del curs > Usuaris inscrits > Inscriure.

### c) Comprova que efectivament, el contingut del curs A (afegit per l'administrador del sistema -és a dir, tu- estigui disponible públicament i que per accedir al curs B s'hagi d'iniciar sessió amb un usuari registrat (alumne o professor)

### 6. Canvia l'aparença estètica del teu lloc. Concretament, descarrega't i activa un tema diferent dels que venen per defecte i prova de canviar també la capçalera i el peu de pàgina del lloc. Això ho pots fer primer anant a Administració del lloc > Connectors > Instal·lar complement i després a Administració del lloc > Aparença > Temes > Selector de temes Sempre pots fer servir l'enllaç Canvi de rol del menú de la dreta per observar com es veuria el lloc sent alumne, professor, etc.

### 7. Assigna un professor i matricula alumnes al curs A.

### 8. Amb el professor afegeix contingut al curs A. Afegeix diferents tipus d’activitats i recursos. Crea una tasca amb data d’entrega oberta que demani la càrrega d’un fitxer PDF.

### 9. Entra amb un alumne i comprova que pots lliurar la tasca.
Continguts

### En el curs A crea una UF amb 2 NF dintre. En aquesta UF crea diverses activitats.

Botó Activar Edició (a dalt a la dreta). Una UF es pot crear amb una etiqueta i movent a la dreta el seu contingut. Es pot canviar el Format del curs a Temes a Administració del Curs > Editar Curs > Format del Curs

Fes servir el moodle del puig com a referència. Han d’haver tant activitats magistrals com evaluables (com a mínim una entrega i un questionari). Clona (importa) el curs sencer al curs B Administració del Curs > Importar (des del curs B)
Qualificació

En el curs A fes que un alumne completi totes les tasques evaluables (entrant amb la seva compta). Calificales amb el professor i configura el calificador per a que doni una nota de la UF automàticament a Administració del Curs > Configuració de qualificacions.

Crea una insignia i atorga-la a aquest alumne des de Administració del Lloc > Insígnies
Qüestionaris

Crea un qüestionari i afegeix preguntes del banc de preguntes. Crea diferents categories dintre del banc de preguntes i diverses preguntes en cada categoria. A l'hora de crear el qüestionari has de seleccionar les preguntes del banc de preguntes. Respon les preguntes del qüestionari amb un usuari estudiant i mira les qualificacions amb l'usuari professor.
Importar i exportar un curs

Entra a la zona Administració > Cursos > Còpies i fes una còpia de seguretat del teu curs. Després envia aquest fitxer a un company i que l'importi al seu moodle. Has d'importar al teu moodle un altre curs d'un company.
Personalització

Descarrega i aplica un tema nou al teu LMS.

Edita també tant la capçalera (header) com el peu (footer) i la pàgina principal (Front page) Posa-li un logotip al teu moodle.
Seguretat

Baneja una IP i aplica una política de seguretat. Pots posar la que vulguis però l’hauràs de justificar.

NOTA: Capturar per a cada pregunta, les imatges que han de mostrar la resposta, i tenir-les a mà, farà que sigui molt més fàcil contestar les preguntes el dia de l’avaluació!
Usuaris

Crea 10 usuaris alumnes i un usuari professor posant-li dades. Administració del Lloc > Usuaris > Crear Usuari / Pujar Usuaris (de cop amb un arxiu csv, hi ha un model de csv al final del document).

Assigna al professor a A i B. Matricula els alumnes a A mitjançant Administració del Curs > Usuaris > Usuaris Matriculats i connectat amb un alumne i matricula'l a B amb la contrassenya.
