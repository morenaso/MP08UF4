# Enunciat:

Documenteu la instal·lació de Moodle a la vostra Màquina Virtual.

- Explicar els passos seguits durant la instal·lació de Moodle (4 punts).
  -   Instal·lació APACHE (1p).
  -     Per instal·lar apache simplement executem la comanda sudo apt-get install apache2, que es el servei que utilitzarem
  -   Instal·lació BBDD (1p).
  -      Aqui mes o menys el mateix,instal·lem la base de dades i despres amb el mysql rot provem de connectar-nos i veure si funciona
  -   Instal·lació PHP (1p).
  -       Primer el que fem es instal·lar el software del php amb la versió corresponent, en el nostre cas la versió 7.4, i desprès descarregem e instal·lem les llibreries.
  -   Instal·lació Moodle (1p).
  -     Primer de tot descarregem el moodle des de la pagina web ( al fer-ho a una màquina virttual, ho fem amb la comanda wget i el enllaç de descàrrega)
  -     Desprès el descomprimim amb la comanda unzip.
  -      El seguent pas es crear el usuari a mysql i la base de dades de moodle, i donar-li permisos.
  -      Un cop fet aixo, accedim mitjançant la nostra ip i al final /moodle, i ens porta a la primera pestanya de l'instal·lació, en la qual es fa seleccionar el idioma que volem.
  -      Després, ens fa instal·lar dues dependències per a poder continuar amb la instal·lació, i després confirmar les rutes de la direcció de dades, etc.
  -      EL seguent pas es seleccionar el controlador de la base de dades,que en el nostre cas es MYSQL. Després el pas seguent es posar les nostres credencials, nom de la base de dades, nom d'usuari, etc.
  -      Després ens demana també varies dependències requerides per poder continuar, les instal·lem, recarregem el servidor apache i ja podem continuar.
  -      Un cop a la seguent pantalla d'instal·lació, es fan les comprovacions del servidor, i moodle et diu que et fa falta i que ja tens instal·lat.
- Inserir les captures de pantalla dels moments delicats de la instal·lació, explicant què es fa a la captura (4 punts).
  -   Instal·lació APACHE (1p).
  -   ![image](https://user-images.githubusercontent.com/119657664/205694636-757b20d0-c272-4a2a-8f0b-f69ec6728cfa.png)

  -   Instal·lació BBDD (1p).
  -   ![Captura de pantalla de 2022-12-05 17-30-45](https://user-images.githubusercontent.com/119657664/205691550-7cfb63a9-4b1c-4a89-b73d-5b93bcc60155.png)

  -   ![image](https://user-images.githubusercontent.com/119657664/205691244-383b35b5-6221-4ca3-b1db-bafc98d7186a.png)
  -   Instal·lació PHP (1p).
  -   ![image](https://user-images.githubusercontent.com/119657664/205695827-4b541007-911c-4cb2-95e6-9c9d5a473c16.png)
      ![image](https://user-images.githubusercontent.com/119657664/205706318-8e034bd2-c317-4937-849e-1675a9bd453d.png)
      ![image](https://user-images.githubusercontent.com/119657664/205708095-70770c07-5e40-4b1b-9be9-12740627dd6f.png)

  -   Instal·lació Moodle (1p).
  -   ![image](https://user-images.githubusercontent.com/119657664/205709844-9411613b-9213-4e3a-973e-e24398619fed.png) 
  -   ![Captura de pantalla de 2022-12-12 17-52-41](https://user-images.githubusercontent.com/119657664/207113443-9769bc30-a276-4cc2-b6e2-2b72917afdd5.png)
  -   ![Captura de pantalla de 2022-12-12 17-52-18](https://user-images.githubusercontent.com/119657664/207113549-c84c2647-1671-4103-b1d3-9f3c8c76517a.png)
  -   ![Captura de pantalla de 2022-12-12 18-49-50](https://user-images.githubusercontent.com/119657664/207118176-01e0d1c7-4a86-4499-b58f-9a2359ffe2ea.png)
  -   ![image](https://user-images.githubusercontent.com/119657664/207117967-1f236ba4-068f-42df-b1a9-8ffcc6013e48.png)
  -   ![image](https://user-images.githubusercontent.com/119657664/207119056-e3ff1ff9-1158-4a37-9130-e905f905c0e4.png)
  -   ![image](https://user-images.githubusercontent.com/119657664/207124416-88535835-a56c-4473-9966-a5b5b323d6e7.png)
  -   ![Captura de pantalla de 2022-12-12 19-26-39](https://user-images.githubusercontent.com/119657664/207125135-e9337c7c-a10e-46b9-9e21-1f48a86d0947.png)
  -   ![Captura de pantalla de 2022-12-12 19-28-01](https://user-images.githubusercontent.com/119657664/207125200-bf4e0e39-5967-4b6f-83ae-dd01dbb39dc6.png)
  -   ![image](https://user-images.githubusercontent.com/119657664/208072612-9319ac9f-095d-4aed-a033-3414501bb8d8.png)
  -   ![image](https://user-images.githubusercontent.com/119657664/208079533-7446c21c-3427-4002-a9cb-326601665cec.png)
  -   ![image](https://user-images.githubusercontent.com/119657664/208079676-0853eb5d-6855-4c4a-8b33-7a1ca9a7fc1b.png)
  -   ![image](https://user-images.githubusercontent.com/119657664/208079870-72bd1819-d4a4-402e-8ebb-54ec9d66ccdd.png)
  -   ![image](https://user-images.githubusercontent.com/119657664/208080813-423efac9-a732-4486-8c98-77990a030b02.png)
  -   ![image](https://user-images.githubusercontent.com/119657664/208080937-4171b9f2-5768-4265-8948-f40c128fd524.png)
  -   ![Captura de pantalla de 2022-12-16 12-10-44](https://user-images.githubusercontent.com/119657664/208086087-ca30ba56-1435-401b-be3f-f83c05582112.png)
  -   ![image](https://user-images.githubusercontent.com/119657664/208086055-27abed27-1ea8-4806-934e-2c1ede87321c.png)
  -   ![image](https://user-images.githubusercontent.com/119657664/208087009-7ee51440-969a-4b9e-b54f-c4ae0e9f5033.png)
  -   ![image](https://user-images.githubusercontent.com/119657664/208087385-b9bc6d0d-7aa2-47f3-a7a5-f1a8c19902b8.png)
  -    ![image](https://user-images.githubusercontent.com/119657664/208088956-87240e08-ab91-4dd3-ad1d-5cfbffa4fcfd.png)
  -   ![image](https://user-images.githubusercontent.com/119657664/208089205-aee32161-52b0-42f1-9f97-8a31ea17732e.png)
  -   ![image](https://user-images.githubusercontent.com/119657664/208093290-4aed3571-8a2c-4424-a335-fa85b31f5697.png)
  -   ![image](https://user-images.githubusercontent.com/119657664/208094829-d4d982fc-3ca9-4d21-a6cb-25327a49dc65.png)
 
- Documentar els problemes que hem tingut durant la instal·lació (2 punts).
  -   Com hem sapigut quina versió de PHP instal·lar (1p).
  -   Altres (1p).
