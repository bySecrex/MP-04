# Activitat Impresorea (Compartir de Linux (Ubuntu) a Windows)

## Compartir de Linux a Windows

Per a compartir una impresora de Linux a Windows, cal fer lo següent:


### **1. Instalar CUPS**

Aquest servei ens permetrà administrar les impresores

Instalar CUPS:

![image](https://github.com/user-attachments/assets/f3230ca4-6054-4a30-ae51-bb761ad16444)

Instalar drivers:

![image](https://github.com/user-attachments/assets/12bc4e35-91d2-4cfc-b698-7736ab566f3f)

Instalar impresora virtual:

![image](https://github.com/user-attachments/assets/a4baaafd-87f1-4b5a-a1a9-b3bb9cea711d)

### **2. Instalar Samba**

Aquest servei ens permetrà compartir les impresores i en el cas de Samba Client, poder utilitzar la impresora compartida desde Windows

Instalar Samba:

![image](https://github.com/user-attachments/assets/c7dd36db-6318-4627-9b3e-214085170a81)

Instalar Samba Client:

![image](https://github.com/user-attachments/assets/e47b56ae-d4a4-4991-b1ab-4bf22d85e73d)

### **3. Configuració de CUPS i creació de una impresora virtual**

Ara podem accedir a CUPS, per a accedir, tindrem que obrir un navegador i posar lo següent

```
localhost:631
```

Al introduirlo, ens portarà a aquesta pagina, i tindrem la interficie grafica de CUPS

![image](https://github.com/user-attachments/assets/edd71f96-37ec-447f-b1e2-7847333c5751)

Per a administar les impresores, anirem a la secció "Administration", aquí tindrem que activar les seguents caselles, les quals surten a la dreta (Despres d'activarles, assegurat de donarli a "Change Settings", sino no servira de res)

![image](https://github.com/user-attachments/assets/4e85ebc0-69a8-4138-9542-dab473af7550)

Després de canviar les opcions, afeixirem la impresora, en aquest cas, creare una virtual ja que no tinc una a mà, per això, li donarem a l'opció "Add Printer"

![image](https://github.com/user-attachments/assets/207f1250-6d47-46fb-89b9-626e4ee80e57)



![image](https://github.com/user-attachments/assets/f5fce0fd-fdd5-462a-a908-4b3f36275a73)

![image](https://github.com/user-attachments/assets/9e27334a-57d2-4749-bcfa-2b3f833933be)

![image](https://github.com/user-attachments/assets/14d22027-4b44-4b36-8669-4c46fe1fc5b6)

![image](https://github.com/user-attachments/assets/9094f854-9a91-4acc-ba93-eb5642973088)

![image](https://github.com/user-attachments/assets/42c38f32-2002-4bc5-aeed-bc0ba55d4e12)
