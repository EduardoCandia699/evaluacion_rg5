# evaluacion_rg5
Examen Primera Semana Rockstar 5G

### Requisitos
- Python 3
- Docker

### Instrucciones:
- Clonar este repo
- Crear imagen de docker
```
docker build -t "eva_rg5"
```
- Correr imagen en modo developer (salir al cerrar)
```
docker run -it -p 5000:5000 --rm --name "eva_rg5-volatil" eva_rg5
```
- Correr imagen en modo servicio
```
docker run -p 5000:5000 -d  --name "eva_rg5-serv" eva_rg5
```