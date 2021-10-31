# crear punto montaje
mount -t cifs -o username=xxx,domain=xxx,password=xxx  //ruta-origen /media/FRONT-REPO

# levantar servicio
docker-compose up --build -d