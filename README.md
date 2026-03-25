# Resoluci-n-M-quina-Tomcat

Iniciamos la máquina vulnerable

<img width="1920" height="1140" alt="Captura de pantalla 2026-03-23 215005" src="https://github.com/user-attachments/assets/a448f1aa-ba23-4f21-bacf-eabecef4aafa" />

# Reconocimiento

Utilizamos la herramienta nmap para hacer un escaneo de la maquina en busqueda de puertos abiertos con la versión de los respectivos servicios qude se encuentra ejecutando en dichos puertos

<img width="1920" height="1140" alt="Captura de pantalla 2026-03-23 215220" src="https://github.com/user-attachments/assets/41e40b1e-48b4-4d25-b464-acbca1cb9929" />

Abrimos en el buscador con el numero ip de la maquina en busqueda de información importante

<img width="1920" height="1140" alt="Captura de pantalla 2026-03-23 215515" src="https://github.com/user-attachments/assets/45d40987-c1af-49ba-ae59-8d995f6ac73e" />

Investigamos un poco dentro de los iconos que encontramos en la pagina y abrimos el que decia Manager App y contramos alguna credenciales

<img width="1920" height="1140" alt="Captura de pantalla 2026-03-23 215642" src="https://github.com/user-attachments/assets/87a04607-1b50-4d95-8670-f7b8850574af" />

Buscamos un poco d información con nuestro amigo gemini a ver que podia ayudarnos

<img width="1920" height="1140" alt="Captura de pantalla 2026-03-23 220318" src="https://github.com/user-attachments/assets/1e548947-b01d-4c24-9bcf-d6b42b4eaa37" />

# Explotación

Luego encntramos una pagina en la cual habia una sección donde nos permitia subir un archivo, creamos un archivo llamado shell2.war, el cual permitia hacer un revershell a nuesstra máquina

<img width="1920" height="1140" alt="Captura de pantalla 2026-03-23 221027" src="https://github.com/user-attachments/assets/d4809d08-f86c-4788-bc87-eaf945866079" />

Lo subimos a la aplicación y abrimos un kali en escucha y una vez abrimos el link nos permitio ingresar a la maquina

<img width="1920" height="1140" alt="Captura de pantalla 2026-03-23 221114" src="https://github.com/user-attachments/assets/464158a8-053c-415b-8117-a8311b941f31" />
<img width="1920" height="1140" alt="Captura de pantalla 2026-03-23 221126" src="https://github.com/user-attachments/assets/80d4094f-1866-4b6f-981f-9387e35d2c8e" />

# Resultados

Una vez dentro de la máquina listamos los archivos y encontramos el archivo que tanto buscabamos flag.txt

<img width="1920" height="1140" alt="Captura de pantalla 2026-03-23 221143" src="https://github.com/user-attachments/assets/108b751a-d321-4a6a-b787-0b9ab800f1f9" />

<img width="1920" height="1140" alt="Captura de pantalla 2026-03-23 221159" src="https://github.com/user-attachments/assets/5cf62387-765b-46a5-9b2a-d2fbfd1803f5" />

De esta manera explotamos esta maquina

<img width="1920" height="1140" alt="Captura de pantalla 2026-03-23 221232" src="https://github.com/user-attachments/assets/d4a09b2e-d533-480c-a48d-2db2048b212c" />
