# Minio


Puede acceder con usuario: User y contraseña: p4ssw0rd

Las operaciones de la API de S3 en el puerto predeterminado del servidor MinIO  :9000

El acceso del navegador en el puerto de la consola MinIO  :9001


Por ejemplo, considere una implementación de MinIO detrás de un proxy https://minio.example.net, https://console.minio.example.net con reglas 

para reenviar el tráfico en el puerto :9000 y :9001 a MinIO y a la consola MinIO, respectivamente, en la red interna.

Configúrelo MINIO_BROWSER_REDIRECT_URLen https://console.minio.example.net para garantizar que el navegador reciba una URL accesible válida.


