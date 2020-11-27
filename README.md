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

- Correr imagen en modo servicio y dinamico
```
docker run -d -p 5050:5050 -v /rockstar/github/evaluacion_rg5:/usr/src/app --name "eva_dynamico" eva_rg5
```