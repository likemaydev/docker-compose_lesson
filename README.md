URLs

[Vote](http://34.122.27.228:5000)
[Result](http://34.122.27.228:5001)

8 Lesson. Docker-compose
---------------

1.Download project:
```
git clone https://github.com/dockersamples/example-voting-app.git
```

2.Split docker-compose.yml
```
cp docker-compose.yml docker-compose_db.yml
cp docker-compose.yml docker-compose_app.yml
vi docker-compose_db.yml
vi docker-compose_app.yml
```

3.Create app:
```
docker-compose -f docker-compose_app.yml -f docker-compose_db.yml up -d
```
