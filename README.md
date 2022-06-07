# DockerExamen
#1
Requisitos:
Tener instalado docker y docker compose.
Para instalar docker compose utilizaremos el siguiente comando :
 Invoke-WebRequest "https://github.com/docker/compose/releases/download/v2.5.0/docker-compose-Windows-x86_64.exe" -UseBasicParsing -OutFile $Env:ProgramFiles\Docker\docker-compose.exe
 ![image](https://user-images.githubusercontent.com/91744605/172452773-45f59d7c-7329-4ab2-8f36-64516d497038.png)

#Creamos el fichero docker-compose.yml
![image](https://user-images.githubusercontent.com/91744605/172453234-9464079e-e21b-4f87-af0b-4cc09d4ab2e9.png)

Y en nuestro docker-compose yml introducimos la versiona obligatoriamente y los servicios siguientes

![image](https://user-images.githubusercontent.com/91744605/172454571-288e583f-59e2-48c9-9174-cdf35e921173.png)

Y utilizamos el comando docker-compose up 

![image](https://user-images.githubusercontent.com/91744605/172454883-252f0f0f-d3e2-4cbc-aff7-ef6f9117bab6.png)

Abrimos de nuevo la terminal escribimos docker-compose ps y veremos lo siguiente
![image](https://user-images.githubusercontent.com/91744605/172455388-fba77de4-0c58-44e1-852b-e2a7deb62aa9.png)

Añadimos los puertos a nuestro fichero yml y haremos un docker-compose up -d y finalizariamos la configuracion del archivo yml

