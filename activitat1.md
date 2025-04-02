# Els anteriors punts estan fets per Nil

## 4.- Serveis

- Utilitza webmin per mostrar els serveis que s'inicien amb el sistema.

![image](https://github.com/user-attachments/assets/52e42d21-9ce4-423d-b48f-557f5ddf0420)

- Utilitza webmin per mostrar els serveis que estan actius.

![image](https://github.com/user-attachments/assets/e35ac7dd-ba00-4ead-97a9-4211e64e6dd8)

- Utilitza webmin per mostrar l'estat del servidor Apache.

![image](https://github.com/user-attachments/assets/d6673e96-13f6-4561-97cd-d0936d390d79)

- Utilitza webmin per aturar Apache.

![image](https://github.com/user-attachments/assets/44a28203-ef34-436c-9acc-7b12a9cfa50c)

- Utilitza webmin per mostrar l'estat del servidor Apache apagat.

![image](https://github.com/user-attachments/assets/b427431c-11ac-444d-8313-14098a1ba157)

- Utilitza webmin per reiniciar Apache.

![image](https://github.com/user-attachments/assets/c0e31830-60fc-469f-a29b-fd6fda4106c7)

- Utilitza webmin per mostrar l'estat del servidor Apache reiniciat.

![image](https://github.com/user-attachments/assets/04be2112-456f-42cb-8f95-694cd8a82e61)

![image](https://github.com/user-attachments/assets/f35f2a46-15ea-49dd-90a4-ed826cbc20a1)

## 5.- Quotes de disc

Activa les quotes de disc pels usuaris amb la comanda: 

```
sudo apt install quota quotatool
```
![image](https://github.com/user-attachments/assets/0a9b6018-5f02-4678-8234-944ba232cb98)

- Utilitza webmin perquè l'usuari bakalao_X no pugui tenir més de 2 MB d'informació al disc.

![image](https://github.com/user-attachments/assets/9eab0203-1faa-4d6a-baa3-2c91243fddae)

- Comprova que el límit de la quota funciona.

![image](https://github.com/user-attachments/assets/b87fb140-74fd-4907-84cb-7bda96afce76)

- Utilitza webmin perquè l'usuari techno no pugui tenir més de 10 fitxers al disc.

![image](https://github.com/user-attachments/assets/a6d342b0-5057-41d6-abd3-c97e3f35dcec)

- Comprova que el límit de la quota funciona.

![image](https://github.com/user-attachments/assets/0dbdf0c4-3201-45af-b7be-f14965d4c634)

## 6.- Còpies de seguretat

- Utilitzant el mòdul de Webmin Filesystem Backup fes una còpia de seguretat del directori /home al directori /backups (l'haureu de crear si no existeix).

![image](https://github.com/user-attachments/assets/8baef292-3235-423d-911e-476093c616f5)

- Modifica alguns fitxers de /home.

![image](https://github.com/user-attachments/assets/2ec7c4f1-6339-47be-b9d7-b4d285e04db1)

- Recupera la còpia de seguretat.

![image](https://github.com/user-attachments/assets/adfa693f-1575-4061-9f73-dd19991e9703)

- Comprova que els fitxers de /home són els correctes.

![image](https://github.com/user-attachments/assets/c32919cc-9a36-45d1-86a2-51a3f32f7068)

- Programa una còpia de seguretat de /home/bakalao_X per els divendres a les 21:00.

![image](https://github.com/user-attachments/assets/877fbc2b-30d7-431f-8cec-da0e8a68b0f1)

- Esborra la còpia de seguretat programada anteriorment.

![image](https://github.com/user-attachments/assets/7f78889e-e159-495f-b511-debde9d4e2e2)

![image](https://github.com/user-attachments/assets/7d1425d8-185d-4e6e-8ce6-8c6144ba3418)

## 7.- Compartició

- Crea un recurs a webmin que, utilitzant samba, comparteixi una carpeta anomenada "area_public_X" per a usuaris sense autenticar en forma de lectura i escriptura.

![image](https://github.com/user-attachments/assets/7ae57051-1373-4490-9028-2b2664e3838c)

- Crea un recurs a webmin que, utilitzant samba, comparteixi una carpeta anomenada "pontaeri_privat_X" per a usuaris _X i techno només de lectura.

![image](https://github.com/user-attachments/assets/f0dd548b-a213-409e-9476-2260e6bbf871)

- Comprovar des de Windows que aquests recursos funcionen.


