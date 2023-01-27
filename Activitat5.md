# Copies de seguretat:

## Importància de les còpies de seguretat:

Quan treballem com administradors d'un servei ens hem de preocupar de com evitar que es perdin les dades o guardar-les per migrar-les a un altre servidor.

Per aquest motiu és important conèixer la informació necessària per poder recuperar el servei en cas d'error o migració.

També podem fer còpies de seguretat únicament de cursos per passar-los a un altre Moodle o crear un curs idèntic.

## Còpia de seguretat d'un curs:

![image](https://user-images.githubusercontent.com/110727546/212052894-c02acab1-3004-4a59-be6d-480c5457bb79.png)

![image](https://user-images.githubusercontent.com/110727546/212726727-6e23b7c5-566c-43d4-b634-22f19e80de9d.png)


Les còpies de seguretat d'un únic curs es fan des de'l mateix Moodle.

Serveixen per duplicar cursos, pasar informació i recursos d'un curs a un altre o migrar un curs a un nou servidor de Moodle.

[Tutorial a Moodle](https://docs.moodle.org/all/es/Respaldo_del_curso)
[Tutorial a Youtube](https://youtu.be/rH6DJ_lbMm0)

## Còpia de seguretat de tot Moodle:

Si volem migrar el servei o recuperar-lo hem de pensar quina informació estem utilitzant a Moodle i on està guardada.

### Pensem...

![image](https://user-images.githubusercontent.com/110727546/212053271-9d1305d7-af49-41a4-b6d5-846816c6bb69.png)
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
### Directori de Moodle: 

El directori amb els fitxers necessaris per què funcioni Moodle. A la nostra pràctica és a /var/www/html/moodle probablement.

### Directori de dades:

El directori on es guarden fitxers pujats pels usuaris/es de Moodle, com les pràctiques. A la nostra pràctica probablement estarà a /home/moodledata.

### Base de dades:

A la base de dades estaran guardades  les dades de cursos, usuaris, puntuacions... 

La forma de fer backup de la base de dades canviarà segons la bbdd que utilitzem.

### Possar-ho tot al lloc una altra vegada:

Després de recuperar tota aquesta informació caldrà ficar-la al nou servidor i comprovar que tot funciona bé.

### Tutorial de migració de Moodle:

[Tutorial a Moodle](https://docs.moodle.org/all/es/Migraci%C3%B3n_de_Moodle)

# Activitat:

L'activitat, que realitzareu per parelles, es divideix en dues pràctiques diferents, cadascuna amb el mateix valor:

## A1 - Backup i restauració de curs:

- Fareu una còpia de seguretat del vostre curs elaborat a Moodle.

![Captura de pantalla de 2023-01-27 08-18-21](https://user-images.githubusercontent.com/119657664/215030294-114c2a19-aa6b-4b7e-9692-f9461c946b4c.png)
![image](https://user-images.githubusercontent.com/119657664/215030369-0db11b89-d1b1-48c0-832d-8e70d3de618b.png)
![image](https://user-images.githubusercontent.com/119657664/215030400-bd1506b9-4eea-4b17-99b1-8e50c87a8c2c.png)
![image](https://user-images.githubusercontent.com/119657664/215030477-79be9fea-2948-40ca-b59e-829e1a60db0a.png)
![image](https://user-images.githubusercontent.com/119657664/215030523-16127a0b-9b07-40a6-b70d-47fbe598c0d3.png)


- Passareu el fitxer al server del company/a de grup.
- ![image](https://user-images.githubusercontent.com/119657664/215129453-243d74b3-936b-4df1-b2c5-222372fd61ba.png)

- Recuperareu el curs al seu Moodle.
- ![image](https://user-images.githubusercontent.com/119657664/215130130-a6214674-06ae-4e4f-a3d3-ac4203ba5e43.png)

- Comprovareu que tot funciona correctament.
- Aquest procés serà recíproc entre els dos companys/es de grup.
- Fareu un vídeo explicant el procés i mostrant el resultat de com a màxim 6 minuts.

## A2 - Migració de Moodle:

- Per aquesta pràctica necessitareu un servidor ubuntu net que serà el receptor del Moodle.
- Migrareu tota la informació d'un dels dos Moodles actuals (escolliu un) a la màquina ubuntu server nova.
- Fareu un vídeo explicant el procés i mostrant el resultat de com a màxim 6 minuts.

# Recursos per a fer vídeos:

- [Editor Kdenlive](https://kdenlive.org/es/).
- [Editor online de vídeo Cliupchamp](https://clipchamp.com/en/)
