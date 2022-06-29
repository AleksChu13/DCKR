

### Сборка образа:
**cd <путь до Dockerfile>**

**docker build . --tag=<тэг образа> .**
### Команда для запуска контейнера:
**docker run -d -p 8000:8000 <имя/тэг образа>**

*Сервер развернется на localhost:8000, для доступа к API- localhost:8000/api/v1/products и localhost:8000/api/v1/stocks* 